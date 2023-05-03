---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

Evaluating the Health of Higher Education System
======
During my undergraduate study, I once participated in a methmatical modelling project, which aimed at designing a mechanism to evaluate the degree of health of a nation's higher education system and provide with some policy recommendations for improvement.

For the evaluation model, we Divided the measurement of health of higher education into 3 dimensions, each with various corresponding indicators reflecting the degree of health of the system: 
* Education Quality: graduation rate, percentage of international faculty and students, student faculty ratio, papers published, etc 
* Educational Funding: proportion of national higher education expenditure, ratio of budget per capita to GDP per capita, etc 
* Education Equality: enrollment rate, sex ratio, average tuition to GDP per capita, etc

Based on these dimensions and indicators, we applied entropy weight method to assign weights of each indicators and then got an quantitative index measuring the health of higher education system. By Calculating the membership function, the samples were allocated to 3 classes, which are unhealthy, mediately healthy and healthy.

For the next part, we built a connection between human capital and the health of higher education system. Thus, we applied and improved the Lucas Human Capital model to simulate the long-term effect of recommended policies. We firstly applied regression models to calculate the variables from the indicators above, and we iterated the traditional two-period Lucas human capital model to do long term simulation. Finally, took China as an example, we successfully simulated and quantified the effect of policies aimed at improving the health of higher education system. 

The original paper is attached as below for details!
[Evaluating the Health of Higher Education System](https://drive.google.com/file/d/1-R65ymHykhTdiU25CWBaKbhOTHrmATCr/view?usp=sharing)

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}




