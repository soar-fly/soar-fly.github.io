---
layout: home
title: Home
---

# Welcome to My GitHub Pages

This is a modern Jekyll template for GitHub Pages with:

- Responsive design
- Clean typography
- SEO optimization
- Social media integration
- Syntax highlighting

## Recent Posts

{% for post in site.posts limit:3 %}
### [{{ post.title }}]({{ post.url }})
{{ post.date | date: "%b %-d, %Y" }}  
{{ post.excerpt | strip_html | truncatewords: 30 }}
{% endfor %}

[View all posts](/posts)