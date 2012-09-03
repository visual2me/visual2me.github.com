---
layout: page
title: Welcome to visual2me's blog
comments: false
tagline: welcome
---
{% include JB/setup %}

## Welcome 

Post list:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

