---
layout: archive
title: "CVs.pdf"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

* For Journalism
* For Finance
* For CompSci

&nbsp;

Education
======
* Bachelor of Journalism, The University of Hong Kong, 2025 (expected)

&nbsp;

Experience
======
* 

&nbsp;

Publications
======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
