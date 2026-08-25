---
layout: page
permalink: /research/
title: Research
description: Working papers and works in progress.
nav: true
nav_order: 1
---

<!-- Bibsearch -->
{% include bib_search.liquid %}

<div class="publications">

  <h2>Working Papers</h2>
  {% bibliography --query @*[category=working] --group_by none %}

  <h2>Work in Progress</h2>
  {% bibliography --query @*[category=wip] --group_by none %}

</div>
