---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* [Add your degree, institution, and year here]
* [Add additional degrees as needed]

Work Experience
======
* [Current Position]: [Title]
  * [Company/Organization]
  * [Brief description of responsibilities]
  * [Duration]

* [Previous Position]: [Title]
  * [Company/Organization]
  * [Brief description of responsibilities]
  * [Duration]

Skills
======
* [Add your technical skills]
* [Add your domain expertise]
* [Add other relevant skills]

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

Professional Activities
======
* [Add professional memberships, leadership roles, or service activities]
