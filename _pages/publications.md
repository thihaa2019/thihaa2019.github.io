---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

- **Optimal Dispatch of Hybrid Renewable–Battery Storage Resources: A Stochastic Control Approach.** T. Aung and M. Ludkovski. In Proc. 63rd IEEE Conf. on Decision and Contr., Dec. 2024.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
