---
layout: page
title: Test Title 
permalink: /reviews/
---
  
<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.h1 }}</a></h3>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More »</a>
    </article>
  {% endfor %}
</div>
