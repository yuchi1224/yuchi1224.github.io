---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="/files/cv.pdf" download class="btn btn--primary btn--large">Download Full CV (PDF)</a>

Education
======
* M.S. in Physics, National Taiwan University, 2025
* B.S. in Physics & Mathematics, National Taiwan University, 2023

## Research Interests
* Mathematical Physics
* High Energy Theory (Dualities, TQFT, etc.)
* Geometry and Topology in Physics

## Skills
* **Languages**: Python, C++, Mathematica
* **Tools**: LaTeX, GitHub
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
