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
* Degree in Field, University Name, Year
  - Additional details or honors
* Another Degree in Another Field, Another University, Year

Work experience
======
* Date: Position
  * Company/Institution Name
  * Duties included: Duty 1, Duty 2, ...
  * Supervisor: Supervisor Name

* Another Date: Another Position
  * Company/Institution Name
  * Duties included: Duty 1, Duty 2, ...
  * Supervisor: Supervisor Name
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Service or leadership role 1
* Service or leadership role 2
