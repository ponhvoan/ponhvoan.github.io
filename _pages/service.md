---
layout: page
permalink: /service/
nav_url: /service/
title: Academic Service
nav_title: Service
nav: true
nav_order: 3
_styles: |
  .post-description {
    display: none;
  }

  .service-section-title {
    font-size: 2.15rem;
    font-weight: 400;
    margin: 2rem 0 1rem;
  }

  .service-card {
    background: var(--global-card-bg-color);
    border: 1px solid var(--global-divider-color);
    border-radius: 0.35rem;
    box-shadow: 0 6px 18px rgba(0, 0, 0, 0.08);
    padding: 0.4rem 0.85rem;
  }

  .service-group + .service-group {
    margin-top: 2rem;
  }

  .service-group-title {
    font-size: 1.15rem;
    font-weight: 500;
    margin: 0.15rem 0 0.7rem;
  }

  .service-list {
    list-style: none;
    margin: 0;
    padding: 0;
  }

  .service-item {
    align-items: baseline;
    border-top: 1px solid var(--global-divider-color);
    display: flex;
    gap: 1rem;
    justify-content: space-between;
    padding: 0.7rem 0.75rem;
  }

  .service-item:first-child {
    border-top: 0;
  }

  .service-item-main {
    color: var(--global-text-color);
    font-size: 0.95rem;
  }

  .service-item-meta {
    color: var(--global-text-color-light);
    flex-shrink: 0;
    font-size: 0.92rem;
    padding-left: 1rem;
    text-align: right;
  }

  @media (max-width: 767.98px) {
    .service-item {
      align-items: flex-start;
      flex-direction: column;
      gap: 0.3rem;
    }

    .service-item-meta {
      padding-left: 0;
      text-align: left;
    }
  }
---

<div class="service-card">
  <section class="service-group">
    <h2 class="service-group-title">Journal Reviewer</h2>
    <ul class="service-list">
      <li class="service-item"><span class="service-item-main">Journal of Artificial Intelligence Research</span></li>
    </ul>
  </section>
</div>

<h2 class="service-section-title">Teaching</h2>

<div class="service-card">
  <section class="service-group">
    <h2 class="service-group-title">Teaching Assistant</h2>
    <ul class="service-list">
      <li class="service-item">
        <span class="service-item-main">Introduction to Research</span>
        <span class="service-item-meta">NTU; Fall 2024, Fall 2025</span>
      </li>
      <li class="service-item">
        <span class="service-item-main">Object-Oriented Design and Programming</span>
        <span class="service-item-meta">NTU; Spring 2024, Fall 2025</span>
      </li>
      <li class="service-item">
        <span class="service-item-main">Foundations of Mathematics</span>
        <span class="service-item-meta">NTU; Fall 2022</span>
      </li>
      <li class="service-item">
        <span class="service-item-main">Introduction to Computational Thinking</span>
        <span class="service-item-meta">NTU; Fall 2022</span>
      </li>
    </ul>
  </section>
</div>
