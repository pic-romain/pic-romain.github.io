---
permalink: /
title: "Romain Pic's Webpage"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a first year PhD Student at [LMB](https://lmb.univ-fcomte.fr/) (CNRS/UBFC).

My research is focused on combining Statistical Learning/Machine Learning and Extreme Value Theory to improve weather forecasting. I work with [Clément Dombry](https://cdombry.perso.math.cnrs.fr/) (LMB), [Philippe Naveau](https://www.lsce.ipsl.fr/Pisp/philippe.naveau/) (LSCE) and [Maxime Taillardat](https://www.umr-cnrm.fr/spip.php?article1211&lang=en) (CNRM/Météo France).

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
