---
layout: page
title: Home
permalink: /
---

<section class="hero">
  <h1>MSCA SPRING Doctoral Network</h1>
  <p>
    Preparing the next generation experts in critical entities resilience design.
  </p>
  <p class="hero-meta">
    Horizon Europe – Marie Skłodowska-Curie Actions (MSCA) Doctoral Network<br>
    Grant Agreement No. 101227080 (SPRING)
  </p>
  <div class="hero-actions">
    <a href="{{ '/doctoral-projects/' | relative_url }}" class="button">
      View doctoral projects (DC1–DC15)
    </a>
    <a href="{{ '/project/' | relative_url }}" class="button-secondary">
      Learn more about the project
    </a>
  </div>
</section>

<section class="highlights">
  <h2>What is SPRING?</h2>
  <p class="section-intro">
    The project aims to develop an innovative research and training programme to train fifteen doctoral candidates, who will collectively engage in an ambitious interdisciplinary research project focusing on aspects related to the resilience design, real-time monitoring and control, anomaly detection and isolation, and incident response, in geographically distributed systems of cyber-physical systems. <br><br>
    
    The PhD topics will investigate open research questions about the use of systems and control theory, formal methods, explainable AI, data-driven approaches, and human-centered design to build safe and resilient societal-scale critical entities. The project will also promote industrial excellence by offering opportunities to the researchers for testing their tools and frameworks in real-world scenarios, provided by the industrial partners. <br><br>
    
    In this line, industrial partners will provide scenarios focusing on water, energy and transportation services, inspired by a real deployment using state-of-the-art and innovative IoT components. The research outcomes that will be validated in the context of these use cases will be reusable with other critical entities in other sectors. <br><br>
  </p>
</section>

<section class="recruitment-callout" style="background: var(--eu-blue-soft); border-left: 4px solid var(--eu-blue); padding: 1.5rem 2rem; margin: 2rem 0; border-radius: var(--radius);">
  <h2 style="margin-top: 0; color: var(--eu-blue);">Applications Open</h2>
  <p style="margin-bottom: 0.5rem;"><strong>Application deadline:</strong> 1st April 2026</p>
  <p style="margin-bottom: 0.5rem;"><strong>Position starting date:</strong> September 2026</p>
<!--  <p style="margin-top: 0.8rem; margin-bottom: 0; font-size: 0.95rem; color: var(--text-muted);">More details about the application and recruitment process are given in Open Positions tab.</p> -->
  <div style="margin-top: 1rem;">
    <a href="{{ '/doctoral-projects/' | relative_url }}" class="button">Apply for these positions</a>
  </div>
</section>

<section class="latest-news">
  <h2>Latest News</h2>
  <ul class="news-list">
    {% for post in site.posts limit:3 %}
      <li>
        <span class="news-date">{{ post.date | date: "%d %b %Y" }}</span>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </li>
    {% else %}
      <li>No news posts yet. Add one in the <code>_posts</code> folder.</li>
    {% endfor %}
  </ul>
</section>
