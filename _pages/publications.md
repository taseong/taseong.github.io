---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 2
---

See also my <a href="https://scholar.google.com/citations?user={{ site.scholar_userid }}">Google Scholar</a> profile.

{% include bib_search.liquid %}

<div class="publications">

  <h1>conference & journal articles</h1>
  {% bibliography -q @*[manuscript=false]* %}

</div>

<div class="publications">

  <h1>preprints</h1>
  {% bibliography -q @*[manuscript=true]* %}

</div>
