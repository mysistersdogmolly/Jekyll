---
layout: default
title: Home
---

# Welcome to My Blog 🚀
This is my new site hosted on GitHub Pages using Jekyll.  
Check out my latest posts below:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
