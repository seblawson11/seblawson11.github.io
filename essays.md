---
layout: page
title: Essays 
permalink: /essays/
---

<div id="home">
  <h1>Posts</h1>
  <hr />

  <ol class="posts">
    {% for post in paginator.posts.essays %}
      <li><a href="{{ post.url }}">{{ post.title }}</a> &raquo; <i><span>{{ post.date | date_to_string }}</span></i></li>
    {% endfor %}
  </ol>