---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can download my resume [here](files/resume.pdf) and cv [here](files/cv.pdf)

Education
======
* B.S. in Computer Science, Shenzhen University University, 2017

Work experience
======
* Spring 2018: Research Assistant
  * Shenzhen University
  * Duties included: Developing Industry AI, Investigate new loss function
  * Supervisor: Professor Yu

* Fall 2016: Research Assistant
  * Shenzhen Institute of Advanced Technology
  * Duties included: Develop Recommendation and Image Recognition Algorithm.
  * Supervisor: Professor Liu
  
Skills
======
* Deep Learning
* Computer Vision
  * Familiar with PyTorch and Tensorflow.
  * Semantic Segmentation, Recognition and etc.
  * Auto Labeling, Training and Deployment.
* Python, TypeScript, Go and some other programming languages.

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
