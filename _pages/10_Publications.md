---
layout: page
title: publications
permalink: /publications/
nav: true
---

[Google Scholar] seems to be the only database that takes into account [my papers][Google Scholar] from both mathematics and physics. You can find incomplete listings of my papers on the [arXiv], [MathSciNet] (access restricted), and [INSPIRE].  

Here are my **[lecture notes on Lagrangian Field Theory](../LFT/)**


[arXiv]: https://arxiv.org/a/blohmann_c_1.html
[MathSciNet]: http://mathscinet.mpim-bonn.mpg.de/mathscinet/search/publications.html?pg1=INDI&s1=722727
[INSPIRE]: http://inspirehep.net/search?p=exactauthor%3AC.Blohmann.1&sf=earliestdate
[Google Scholar]: https://scholar.google.com/citations?user=G4z5p40AAAAJ&hl=en

### books

<div class="publications">
    {% bibliography -f blohmann --query @book %}
</div>

### research papers

<div class="publications">
    {% bibliography -f blohmann --query @article || @incollection || @unpublished %}
</div>

### PhD thesis

<div class="publications">
    {% bibliography -f blohmann --query @phdthesis %}
</div>

### other publications

<div class="publications">
    {% bibliography -f blohmann_other %}
</div>
