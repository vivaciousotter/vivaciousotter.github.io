---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

---

This is a test

<ul>
  {% for application in site.applications %}
    <li>
      <a href="{{ application.url }}">{{ application.title }}</a>
    </li>
  {% endfor %}
</ul>
