---
layout: page
title: RC Cars
permalink: /rccars/
---

Racing radio controlled cars is a hobby of mine. I often get funny looks when I
mention this, but I like cars, I like speed, I like technology, and this has
all of those things!

I used to race before going to cégep (the Québec equivalent to college), which
was, um, in 1993. I was pretty decent at it, won some local club championships,
but it was on ovals, which is easier to pick up than the circuits they mostly
run on here in the UK, almost everything changed (motor and battery technology
we could only dream of!), and, well, it was over 20 years ago!

Now, I'm a newbie again, but having quite a bit of fun again, especially now
that I'm not rebuilding ball diffs, truing motor comms, cleaning and filing
brushes, conditioning NiCad batteries, and so on. ;-)

Here's a few things I learned while getting back into this, might be useful to
other newbies...

  <ul class="post-list">
    {% for article in site.rccars %}
      <li>
        <h2>
          <a class="post-link" href="{{ article.url | prepend: site.baseurl }}">{{ article.title }}</a>
        </h2>
	{% if article.summary %}{{ article.summary | markdownify }}{% endif %}
      </li>
    {% endfor %}
  </ul>

