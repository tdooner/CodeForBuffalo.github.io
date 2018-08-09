---
title: Who We Are
author: Code for Buffalo
layout: default
permalink: /who-we-are/
---

#### Local Civic Innovators and Creative Problem-Solvers

We are civic-minded residents committed to working with local government and the Buffalo community to make our region stronger. We’re here to help and eager to learn from professional public servants. While we’re advocates for open government (we can’t build apps without open data!), we’re non-partisan and public-minded.

We are a group of organizers and activists, software developers and data scientists, designers and researchers, project managers and public servants, and many more passionate community members.

We work in partnership with government, non-profit, and technical partners to deploy technology to improve quality of life for all residents. We strive to achieve this by helping enhance public services to be <em>better, faster, and cheaper</em> and have the greatest impact for the greatest amount of people who have the greatest need.

---

#### Diversity and Inclusion
*Building a better Buffalo needs __all__ of Buffalo.*

We welcome people of any gender identity or expression, race, skin color, ethnicity, age, size, nationality, sexual orientation, ability level, neurotype, religion, culture, political opinion, education level, and identity. We welcome activists, artists, bloggers, crafters, coders, wannabe-coders, designers, entrepreneurs, journalists, teachers, ordinary people, extraordinary people, and everyone in between.

In the wise words of Jane Jacobs,
> "Cities have the capability of providing something for everybody, only because, and only when, they are created by everybody.”

---

#### Code for Buffalo Leadership
Code for Buffalo is powered by volunteers just like you. The Core Team organizes events, manages strategic partnerships, and ensures fluid communication among cross-functional project teams. We oversee volunteer management, organizational sustainability, and day-to-day operations.

##### Help lead Code for Buffalo with us!

Come join us as we build the civic tech community and a better Buffalo! We’re looking for diverse voices to contribute to the team and provide important perspectives so that our work engages the diverse population of Buffalo. You do not need to be a Code for Buffalo regular and you **definitely** do not need to be a coder. Instead, you should have an interest in improving civic outcomes and at least some interest in technology. You should be able to think creatively about civic and strategic issues. If you're interested in learning more about joining the team, reach out to [leadership@codeforbuffalo.org](mailto:leadership@codeforbuffalo.org?subject=Meetup%20Suggestion)


<div class="row">
  {% for member in site.data.senior_leadership %}
    <div class="col-xs-4">
      <img class="img-responsive img-circle" src="/images/headshots/{{ member.headshot }}">
      <h4>{{ member.name }}</h4>
      <h5>{{ member.title }}</h5>
      <ul class="list-unstyled horizontal-icons text-center">
        <li><a href="mailto:{{ member.email }}?subject=Code%20for%20Buffalo"><i class="fas fa-envelope"></i></a></li>
        <li><a href="https://twitter.com/{{ member.twitter }}"><i class="fab fa-twitter" target="_blank"></i></a></li>
        <!--li><a href="https://github.com/{{ member.github }}"><i class="fab fa-github" target="_blank"></i></a></li-->
        <li><a href="{{ member.linkedin }}"><i class="fab fa-linkedin" target="_blank"></i></a></li>
      </ul>
    </div>
        <!-- if last column in row -->
          {% if forloop.counter | divisibleby:"4" and not forloop.last %}
            </div><div class="row">
          {% endif %}
  {% endfor %}
</div>

## We are Code for Buffalo.

Est. 2018, Buffalo, NY. The Code for America Brigade of Western New York

{% comment %}
<!--

{% include about/innovators.html %}
{% include about/advisory.html %}
-->
{% endcomment %}
