---
layout: default
---

# Welcome to My Blog

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.date | date_to_string }}</p>
  <p>{{ post.excerpt }}</p>
{% endfor %}
