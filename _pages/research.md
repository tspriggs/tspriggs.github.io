---
layout: single-portfolio
title: "Research"
permalink: /research/
author_profile: true
# header:
#   og_image: "research/ecdf.png"
---

My research falls into BLAH....

My other main research area uses Blah.

<!-- <nbsp> -->

{% include base_path %}

<!-- {% assign ordered_pages = site.research | sort:"order_number" %} -->

{% for post in site.research reversed %}
  {% include archive-single.html type="grid" %}
{% endfor %}
