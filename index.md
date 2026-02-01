---
layout: default
title: Home
---

<section class="hero">
  <div class="hero-container">
    <div class="hero-left">
      <div class="hero-image">
        <img src="{{ site.avatar | relative_url }}" alt="{{ site.title }}" class="hero-avatar">
      </div>
      <div class="hero-content">
        <h1 class="hero-name">{{ site.title }}</h1>
        <p class="hero-title">{{ site.position }}</p>
        <p class="hero-affiliation">
          <a href="https://www.infineon.com/" target="_blank">{{ site.affiliation }}</a>
        </p>
        <div class="hero-social">
          {% if site.github_link %}
          <a href="{{ site.github_link }}" class="social-link" target="_blank" title="GitHub">
            <i class="fab fa-github"></i>
          </a>
          {% endif %}
          {% if site.linkedin %}
          <a href="{{ site.linkedin }}" class="social-link" target="_blank" title="LinkedIn">
            <i class="fab fa-linkedin-in"></i>
          </a>
          {% endif %}
          <a href="mailto:{{ site.email }}" class="social-link" title="Email">
            <i class="fas fa-envelope"></i>
          </a>
        </div>
        <div class="about-text">
          <p>I am a Backend Engineer with an MSc in Computer Science from <a href="https://www.uni-saarland.de/" target="_blank">Saarland University</a>, and I enjoy solving problems by building reliable, scalable systems.</p>
          <p>Currently working on my Master's thesis at <a href="https://www.infineon.com/" target="_blank">Infineon Technologies</a>. Previously, I worked at <a href="https://www.anynines.com/" target="_blank">anynines</a> as a Cloud Platform Engineer, and at <a href="https://10pearls.com/" target="_blank">10Pearls</a> as a Software Engineer.</p>
        </div>
      </div>
    </div>

    <div class="hero-right">
      <div class="news-section">
        <h2 class="section-title">Timeline</h2>
        <div class="news-list-scroll">
          <div class="news-item">
            <span class="news-date">Jan 2026</span>
            <p class="news-content">Started Master's thesis at <a href="https://www.infineon.com/" target="_blank">Infineon Technologies</a>.</p>
          </div>
          <div class="news-item">
            <span class="news-date">Nov 2023</span>
            <p class="news-content">Joined <a href="https://www.anynines.com/" target="_blank">anynines</a> as Cloud Platform Engineer.</p>
          </div>
          <div class="news-item">
            <span class="news-date">Oct 2023</span>
            <p class="news-content">Started MSc Computer Science at <a href="https://www.uni-saarland.de/" target="_blank">Saarland University</a>.</p>
          </div>
          <div class="news-item">
            <span class="news-date">Jan 2023</span>
            <p class="news-content">Promoted to Software Engineer at <a href="https://10pearls.com/" target="_blank">10Pearls</a>.</p>
          </div>
          <div class="news-item">
            <span class="news-date">Jun 2022</span>
            <p class="news-content">Graduated from <a href="https://iba.edu.pk/" target="_blank">IBA</a> and joined 10Pearls.</p>
          </div>
          <div class="news-item">
            <span class="news-date">Jun 2021</span>
            <p class="news-content">Started as ML Engineer at Sofcom, built stock prediction models.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="home-main">
  <div class="home-main-container">
    <!-- Experience Section -->
    <div class="content-section">
      <h2 class="section-title">Experience</h2>
      <div class="exp-edu-list">
        <div class="exp-edu-card">
          <div class="exp-edu-header">
            <h3 class="exp-edu-title">Master Thesis</h3>
            <span class="exp-edu-date">Jan 2026 - Present</span>
          </div>
          <p class="exp-edu-org"><a href="https://www.infineon.com/" target="_blank">Infineon Technologies</a>, Neubiberg, Germany</p>
          <p class="exp-edu-desc">Working on my Master's thesis in collaboration with Infineon Technologies.</p>
        </div>
        <div class="exp-edu-card">
          <div class="exp-edu-header">
            <h3 class="exp-edu-title">Cloud Platform Engineer</h3>
            <span class="exp-edu-date">Nov 2023 - Oct 2025</span>
          </div>
          <p class="exp-edu-org"><a href="https://www.anynines.com/" target="_blank">anynines</a>, Saarbrücken, Germany</p>
          <p class="exp-edu-desc">Automated deployment cleanup, migrated Redis to Valkey in Go, optimized Dockerfiles with multi-stage builds, and streamlined CI/CD with Concourse. Built monitoring portal integrating Prometheus, Alertmanager, and Graphite.</p>
        </div>
        <div class="exp-edu-card">
          <div class="exp-edu-header">
            <h3 class="exp-edu-title">Software Engineer</h3>
            <span class="exp-edu-date">Jun 2022 - Oct 2023</span>
          </div>
          <p class="exp-edu-org"><a href="https://10pearls.com/" target="_blank">10Pearls</a>, Karachi, Pakistan</p>
          <p class="exp-edu-desc">Optimized SQL migrations reducing execution from hours to minutes. Resolved AWS gateway timeouts, developed REST APIs in Flask, and extended Odoo CRM features. Twice recognized with Developer Incentive Award.</p>
        </div>
        <div class="exp-edu-card">
          <div class="exp-edu-header">
            <h3 class="exp-edu-title">Machine Learning Engineer</h3>
            <span class="exp-edu-date">Jun 2021 - Feb 2022</span>
          </div>
          <p class="exp-edu-org"><a href="#">Sofcom</a>, Karachi, Pakistan</p>
          <p class="exp-edu-desc">Built predictive models for PSX stock prices using Python, pandas, and scikit-learn. Conducted data preprocessing, feature engineering, and model evaluation for production deployment.</p>
        </div>
      </div>
    </div>

    <!-- Education Section -->
    <div class="content-section">
      <h2 class="section-title">Education</h2>
      <div class="exp-edu-list">
        <div class="exp-edu-card">
          <div class="exp-edu-header">
            <h3 class="exp-edu-title">MSc Computer Science</h3>
            <span class="exp-edu-date">Oct 2023 - Present</span>
          </div>
          <p class="exp-edu-org"><a href="https://www.uni-saarland.de/" target="_blank">Saarland University</a>, Germany</p>
          <p class="exp-edu-desc">Focus on software systems and distributed computing. Currently working on Master's thesis at Infineon Technologies.</p>
        </div>
        <div class="exp-edu-card">
          <div class="exp-edu-header">
            <h3 class="exp-edu-title">BSc Computer Science</h3>
            <span class="exp-edu-date">2018 - 2022</span>
          </div>
          <p class="exp-edu-org"><a href="https://iba.edu.pk/" target="_blank">Institute of Business Administration (IBA)</a>, Pakistan</p>
          <p class="exp-edu-desc">Dean's List honoree. Recipient of SEEF Scholarship. Strong foundation in software engineering, databases, and algorithms.</p>
        </div>
      </div>
    </div>

    <!-- Technical Focus -->
    <div class="content-section">
      <h2 class="section-title">Technical Focus</h2>
      <div class="interests-grid">
        <div class="interest-card">
          <h3 class="interest-title">Backend Engineering</h3>
          <p class="interest-desc">Python, Ruby, Go, Elixir, Flask. Building reliable APIs and scalable backend services.</p>
        </div>
        <div class="interest-card">
          <h3 class="interest-title">Cloud & DevOps</h3>
          <p class="interest-desc">AWS, Docker, Concourse CI, microservices architecture, and infrastructure automation.</p>
        </div>
        <div class="interest-card">
          <h3 class="interest-title">Data Systems</h3>
          <p class="interest-desc">PostgreSQL, SQL optimization, data migrations, and database performance tuning.</p>
        </div>
      </div>
    </div>
  </div>
</section>
