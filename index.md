## Welcome on my homepage

I am a your software developper and wannabe software engineer. I'm currently stuying Computer Science at EPFL.

### Hire me!

You want to learn more about me and/or hire me? You can find my resume [here](https://files.zyuiop.net/resume.pdf) and you can contact me via my email [louis.vialar@protonmail.ch](mailto:louis.vialar@protonmail.ch). I am still studying, and I am therefore not available for full time jobs. I'd be happy to join for part time jobs or internships, mainly in Switzerland, Europe, or eastern Asia!

## Blog

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
