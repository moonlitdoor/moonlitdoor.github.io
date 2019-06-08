---
layout: post
title:  Delete Remote Git Tags
date:   2019-06-07 14:40:56
tags: [Git]
---

How many times have I pushed a git tag to GitHub and then realized that I made a
mistake? Too many to count. It is kind of embarrassing. Fortunately it is not frequent
enough that I have memorized how to delete that tag.

So write it down.
-----------------

{% highlight bash %}
git tag -d 0.7.8
git push origin :refs/tags/0.7.8
{% endhighlight %}

Simple.
-------
