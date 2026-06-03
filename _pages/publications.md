---
layout: page
permalink: /research/
title: research
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

{% include bib_search.liquid %}

---

## Publications

<div class="publications">
{% bibliography --query @article %}
</div>

---

## Working Papers

<div class="publications">
{% bibliography --query @unpublished %}
</div>

---

## Conference Papers

<div class="publications">
{% bibliography --query @inproceedings %}
</div>
