---
layout: category
title: Lectures
---



<ul>
  {% for post in site.static_files %}
    {% if post.path contains 'pdf' %}
        <li>
            <a href="{{ site.baseurl }}{{ post.path }}">{{ post.name }}</a>
        </li>
    {% endif %}
  {% endfor %}
</ul>   