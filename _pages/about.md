---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "Publications"
author_profile: true
redirect_from: 
  - /publications/
  - /publications.html
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---
Blah
---
