# The Italian Covid-19 emergency
*A brief data analysis and visualization document on the current situation in the Italian region*

**Authors** 
_Roberto Ceraolo_ : robi.ceraolo@gmail.com +0039 3319999529
_Simone Giancola_ : simonegiancola09@gmail.com +0039 3314788683

We are absolutely not professionals, so any suggestion, either typo, code, writing, or analysis related is highly appreciated, and will be welcomed with enthusiasm. 
We are absolutely not professionals, so any suggestion, either typo, code, writing, or analysis related is highly appreciated, and will be welcomed with enthusiasm.

<h1>Table of Contents<span class="tocSkip"></span></h1>
<div class="toc"><ul class="toc-item"><li><span><a href="#Introduction" data-toc-modified-id="Introduction-1"><span class="toc-item-num">1&nbsp;&nbsp;</span>Introduction</a></span><ul class="toc-item"><li><span><a href="#Facts-in-short" data-toc-modified-id="Facts-in-short-1.1"><span class="toc-item-num">1.1&nbsp;&nbsp;</span>Facts in short</a></span></li><li><span><a href="#Purpose-and-reason-of-the-document" data-toc-modified-id="Purpose-and-reason-of-the-document-1.2"><span class="toc-item-num">1.2&nbsp;&nbsp;</span>Purpose and reason of the document</a></span></li><li><span><a href="#More-on-the-authors" data-toc-modified-id="More-on-the-authors-1.3"><span class="toc-item-num">1.3&nbsp;&nbsp;</span>More on the authors</a></span></li></ul></li><li><span><a href="#First-step:-data-exploration-and-cleaning" data-toc-modified-id="First-step:-data-exploration-and-cleaning-2"><span class="toc-item-num">2&nbsp;&nbsp;</span>First step: data exploration and cleaning</a></span></li><li><span><a href="#Second-Step:-Analysis" data-toc-modified-id="Second-Step:-Analysis-3"><span class="toc-item-num">3&nbsp;&nbsp;</span>Second Step: Analysis</a></span></li><li><span><a href="#Geographical-Plotting-attempt" data-toc-modified-id="Geographical-Plotting-attempt-4"><span class="toc-item-num">4&nbsp;&nbsp;</span>Geographical Plotting attempt</a></span></li><li><span><a href="#Approximation-attempt" data-toc-modified-id="Approximation-attempt-5"><span class="toc-item-num">5&nbsp;&nbsp;</span>Approximation attempt</a></span></li><li><span><a href="#Approximating-total_positives-al-over-the-country" data-toc-modified-id="Approximating-total_positives-al-over-the-country-6"><span class="toc-item-num">6&nbsp;&nbsp;</span>Approximating total_positives al over the country</a></span></li></ul></div>


## Introduction

### Facts in short
On the 31st of december the Chinese government informed WHO authorities that they had discovered in the city of Wuhan some strange penumonia cases, due to a virus never seen before.

From that moment onwards, it only took one month for the virus to be found inside the Italian borders, with the first two "turist patients" in Rome. In the following months, almost unnoticed, the Sars-CoV-2 crawled slowly underneath our lives becoming in a relatively small portion of 2020 the most demanding challenge of the recent years.

A more detailed description of the timeline of the virus can be easily found at the following Wikipedia link:

 [2019-2020 Coronavirus Pandemic](https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic)
 
### Purpose and reason of the document
The following document is neither a statement of facts, nor an attempt to predict the future. Any information of this kind extracted from the following pages is not a result of our purpose. All the chapters, graphs, and text paragraphs are an attempt to gain a greater understanding of the italian situation, done by exploiting the database kindly offered by the [Italian Civil Protection](http://www.protezionecivile.gov.it/), which stores data that is shared with citizens concerning the Covid-19 emergency.

The target readers are not necessarily academics, since the concepts proposed are more citizen oriented, rather than for intellectuals. As a rule of thumb, it is an interesting read for someone who would like to stay informed, and see some graphs which are not usually showed on TV or journals, or at least not all in one. For this reason we also decided to add some interactive features which allow users to explore the database, and plot what they like, hoping that the server we exploit will do the work. In the event that the reader is currently looking at a PDF and would still enjoy some interaction with it, we suggest to click on the following link:

REMINDER, PUT BINDER LINK FOR SHARING

The whole notebook does not take into account approximation methods and error theory, we as authors are completely aware of that, and would've enjoyed not doing so. However, being Bachelor students, we decided not to risk being completely mistaken in the world of statistical estimation, which we will hopefully master at the end of our studies. Both of us saw this work as more of a python-oriented exercise rather than statistics-oriented.

