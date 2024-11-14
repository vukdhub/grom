---
Title: Load
Template: analysis
---

Titel på rapporten
=======================

Skriv en eller två rader om vad uppgiften handlar om.

Selection
-----------------------

I selected websites that I frequently use and that have a high volume of daily visitors on both mobile and desktop screens. These websites are: 
1. Pescanik <a href="https://www.pescanik.net">https://www.pescanik.net</a>
2. Sveriges Radio <a href="https://sverigesradio.se">https://sverigesradio.se</a>
3. N1 Info <a href="https://n1info.rs">https://n1info.rs</a>


Method
-----------------------

As part of my method, I will use the Google PageSpeed Insights tool to assess each site's score. This will help me understand which elements and types of data or code impact the overall page performance on both mobile and desktop views. I will then use the browser's developer tools to measure loading times and the number of elements on three different pages for each site. All findings will be recorded in a Google Sheet for reference.

Resultat
-----------------------

Pescanik

<img src="%assets_url%/img/pescanik.png" width="300" height="300" />
I measured three different pages—Home, English, and Knjiga. The loading time varied based on the elements on each page, and while the overall score is well-optimized for desktop, it’s somewhat lower for mobile.
<div class="sheet">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQzLcGGceYPkapSyYuI38LZxPCYpMpYdSL7GfW24TgoujU3b56e5AktAOwEl1pKYXkLCKb3ZryRU_Lo/pubhtml?gid=2042024564&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
</div>

Sverige Radio

<img src="%assets_url%/img/sverigeradio.png" width="300" height="300" />
Sveriges Radio has a fast-loading website with smaller-sized elements, making all three pages quick to load and lightweight. The Google PageSpeed score is high for desktop and falls within the mid-range for mobile.
<div class="sheet">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQzLcGGceYPkapSyYuI38LZxPCYpMpYdSL7GfW24TgoujU3b56e5AktAOwEl1pKYXkLCKb3ZryRU_Lo/pubhtml?gid=1214139737&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
</div>

N1

<img src="%assets_url%/img/n1.png" width="300" height="300" />
As a daily news site with high traffic, N1 is slow and poorly optimized for mobile devices. It’s cluttered with banners and information-heavy images, resulting in slow loading times and a high number of elements.

<div class="sheet">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQzLcGGceYPkapSyYuI38LZxPCYpMpYdSL7GfW24TgoujU3b56e5AktAOwEl1pKYXkLCKb3ZryRU_Lo/pubhtml?gid=1376371584&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
</div>

###Summary of Results
From the performance tests, it’s clear that Sveriges Radio leads in efficiency, with the fastest loading times and minimal element sizes across all three pages. Both N1 and Pescanik display notable contrasts between desktop and mobile optimization scores, though N1 performs the slowest overall due to its large, image-heavy content and numerous banners, which heavily impact mobile performance. Pescanik has moderate scores and loading times, performing better than N1 but still showing room for improvement on mobile.

Analys
-----------------------

The most common areas for improvement across these sites include:

1. Mobile Optimization: The mobile scores were consistently lower than desktop scores. Streamlining content, deferring non-essential scripts, and compressing images could significantly enhance mobile performance.
2. Reducing Resource Size: Sites like N1, with heavy images and banner content, could benefit from image compression and conditional loading (lazy loading) to reduce initial load times.
3. Minimizing Requests: Reducing the number of elements loaded per page, especially by combining CSS and JavaScript files, could help all three sites improve load times.

####Ranking and Test Winner
Based on the measurements, the ranking of sites is as follows:

1. Sveriges Radio: The clear winner with consistently low loading times, minimal element sizes, and high scores, especially on desktop.
2. Pescanik: Moderate performance, reasonable load times, though not fully optimized for mobile.
3. N1: Ranked last due to its high load times, large element sizes, and lower scores, particularly on mobile.
Winner: Sveriges Radio stands out for its fast, efficient design and balanced performance across desktop and mobile.

###Load Time Threshold
A loading time of under 1 second is my benchmark for a fast website. Among the tested sites, only Sveriges Radio consistently meets this threshold across all three pages, while Pescanik and N1 struggle to maintain sub-second loads. Overall, Sveriges Radio feels fast and smooth, while Pescanik and especially N1 could benefit from targeted optimization to improve user experience.

Referenser
-----------------------

- https://pagespeed.web.dev
- https://developer.apple.com/safari/tools/
- https://developer.chrome.com/docs/devtools

Övrigt
-----------------------

Written by Vuk Dajic