---
layout: page
title: Domů
---

# Vítejte
v Najt Vejl

## Posty

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

