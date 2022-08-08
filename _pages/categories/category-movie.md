---
title: "영화 리뷰"
layout: archive
permalink: categories/movie
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.Movie %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}
