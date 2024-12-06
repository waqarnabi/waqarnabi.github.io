---
layout: archive
title: "Publications"
permalink: publications/
author_profile: true
---

You can find my articles on  <u><a href="{{ site.author.googlescholar }}">my Google Scholar profile</a></u>

{% comment %}
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
{% endcomment %}


{% include base_path %}


{% comment %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %}
