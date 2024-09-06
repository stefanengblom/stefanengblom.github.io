---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

_See also:_ <a href="{{site.author.googlescholar}}">my Google Scholar
profile</a>, or DiVA records for [Author: Stefan
Engblom](http://uu.diva-portal.org/dice/table?query=authorName:Stefan%20Engblom&start=0&rows=100&sort=year%20desc).
Alternatively, [list of publications as a
pdf](../files/publ_Engblom.pdf).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
