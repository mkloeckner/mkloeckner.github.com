---
layout: page
title: hello github! 
---

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

