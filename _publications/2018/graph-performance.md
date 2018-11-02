---
authors: [Tom Horak, Ulrike Kister, Raimund Dachselt]
award:
date: 2018-10-21
doi:
keywords:
pages:
pdf: https://imld.de/cnt/uploads/Horak-2018-Graph-Performance.pdf
poster: https://imld.de/cnt/uploads/Horak-2018-Graph-Performance-Poster.pdf
projectpage:
publisher:
slides:
teaser:
thumb: assets/graph-performance.thumb.png
title: "Comparing Rendering Performance of Common Web Technologies for Large Graphs"
toappear:
type: Poster
video: https://youtu.be/dLkB_ZobDLU
venue: Poster Program of the 2018 IEEE VIS Conference
venue-short: VIS '18

abstract: >
    <p>In this work, we compared the established web-technologies SVG, Canvas, and WebGL regarding their performance for large visualizations.
       Specifically, we compared these technologies by analyzing the achievable frames per second (FPS) in exemplary implementations of a tree visualization with increasing number of elements.</p>
       <p>We found that SVG and Canvas almost perform on par, with performance drops starting at around 10,000 graphical elements, while WebGL performs slightly better when showing text elements and stays almost unaffected by increasing node quantities without text elements.
       Finally, we discuss additional strategies to improve the performance in certain situations.</p>

bibtex: >
    @InProceedings{Horak2018c,
       author    = {Tom Horak and Ulrike Kister and Raimund Dachselt},
       title     = {Comparing Rendering Performance of Common Web Technologies for Large Graphs},
       booktitle = {Poster Program of the 2018 IEEE VIS Conference},
       series    = {VIS '18},
       year      = {2018},
       location  = {Berlin, Germany}
    }

---

## Poster
This work was presented as a poster at the IEEE VIS 2018 conference:

![poster](../assets/graph-performance.poster.png){:style="width:100%"}