---
layout: archive
title: "Code"
permalink: /code/
author_profile: true
classes: wide
---

Below you will find code which I have developed or to which I have contributed, with more detailed explanations avialble by clicking on the names.

*****

{% for post in site.code reversed %}
  {% include archive-single.html %}
{% endfor %}
