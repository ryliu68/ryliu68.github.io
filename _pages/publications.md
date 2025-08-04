---
layout: page
permalink: /publications/
title: Publications
description: My published papers and preprint.

nav: true
nav_order: 2
---
<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>Preprints</h2>

  {% bibliography -f preprint %}

</div>


<div class="publications">

<h2>Published</h2>

{% bibliography %}

</div>


