---
layout: page
title: Gallery
permalink: /gallery/
---
{% for photo in site.photos %}
  <div class="photo">
    <img src="{{ photo.image_path }}" alt="{{ photo.title }}">{{ photo.title }}
    {{ photo.content }}
  </div>
{% endfor %}