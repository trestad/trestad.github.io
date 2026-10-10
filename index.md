---
layout: default
permalink: /
profile_intro: "I am currently a Ph.D. student at Gaoling School of Artificial Intelligence (GSAI) in Renmin University of China, expected to graduate in 2027. My research interests lie in <span class='hero__em'>foundation model pretraining / architecture / efficiency</span>."
redirect_from:
  - /about/
  - /about.html
---

<section class="section" id="news">
  <h1>News</h1>
  <ol class="timeline">
    <li>
      <span class="when">Oct 2026</span>
      <div class="what">KV-cache compression is not a free lunch: when <em>n</em> tokens are compressed into one cache entry, models spontaneously learn to keep only a single content-agnostic slot—inducing what we call <em>phase sensitivity</em>. We study this <a href="https://ultimatejupiter.github.io/blog/periodic-weak-spots/">theoretically and empirically</a>.</div>
    </li>
    <li>
      <span class="when">Jan 2026</span>
      <div class="what">Paper “<a href="https://openreview.net/forum?id=MpeyjgWbKt">ERC loss for MoEs</a>”, an auxiliary loss for MoE autonomy, accepted to ICLR 2026 <span class="mark">Oral</span></div>
    </li>
    <li>
      <span class="when">Oct 2025</span>
      <div class="what">Awarded National Scholarship for Doctoral Students <span class="mark">Ranked 1st in GSAI</span></div>
    </li>
    <li>
      <span class="when">Sept 2025</span>
      <div class="what">Paper “<a href="https://openreview.net/forum?id=JCTTLKEBza">PolarQuant</a>”, effective post-RoPE KV-cache quantization, accepted to NeurIPS 2025.</div>
    </li>
    <li>
      <span class="when">July 2025</span>
      <div class="what">Joined ByteDance Seed <span class="mark">Top Seed Intern</span></div>
    </li>
    <li>
      <span class="when">July 2025</span>
      <div class="what">Paper “<a href="https://aclanthology.org/2025.acl-long.1123/">HoPE</a>”, on why partial RoPE works, received the <span class="mark">ACL 2025 SAC Highlights Award</span></div>
    </li>
    <li>
      <span class="when">May 2025</span>
      <div class="what">Paper “<a href="https://icml.cc/virtual/2025/poster/46286">Autonomy-of-Experts Models</a>”, self-selecting MoE experts, accepted to ICML 2025.</div>
    </li>
  </ol>
</section>

<section class="section" id="honors">
  <h1>Honors and Awards</h1>
  <ol class="timeline">
    <li>
      <span class="when">2025</span>
      <div class="what">National Scholarship for Doctoral Students<span class="detail">1st-Ranked in GSAI</span></div>
    </li>
    <li>
      <span class="when">2025</span>
      <div class="what">ByteDance Top Seed Intern</div>
    </li>
    <li>
      <span class="when">2025</span>
      <div class="what">ACL 2025 SAC Highlights Paper Award<span class="detail">Top 1.5%</span></div>
    </li>
    <li>
      <span class="when">2025</span>
      <div class="what">CIE-Tencent Doctoral Student Research Incentive Program<span class="detail">HunYuan Large Language Model Special Project · 1 of 17 selected individuals nationwide</span></div>
    </li>
    <li>
      <span class="when">2024</span>
      <div class="what">CCF-Tencent Rhino-Bird Elite Talent Program<span class="detail">1 of 50 selected individuals nationwide</span></div>
    </li>
    <li>
      <span class="when">2023 – 2025</span>
      <div class="what">Outstanding Innovative Talents Cultivation Funded Programs<span class="detail">Renmin University of China</span></div>
    </li>
  </ol>
</section>

<section class="section" id="service">
  <h1>Academic Services</h1>
  <ol class="timeline">
    <li>
      <span class="when">Area Chair</span>
      <div class="what">EMNLP, ACL<span class="detail">ACL Rolling Review (ARR)</span></div>
    </li>
    <li>
      <span class="when">Reviewer</span>
      <div class="what">ICML <span class="mark">Gold</span>, ICLR, NeurIPS</div>
    </li>
  </ol>
</section>

<section class="section" id="internships">
  <h1>Internships</h1>
  <ol class="timeline">
    <li>
      <span class="when">2025.07 – Now</span>
      <div class="what"><a href="https://seed.bytedance.com/en/direction/llm">ByteDance Seed LLM</a>.</div>
    </li>
    <li>
      <span class="when">2024.05 – 2025.07</span>
      <div class="what">Tencent Hunyuan, mentored by <a href="https://ruobingxie.github.io/">Ruobing Xie</a>. We conducted a series of work on autonomous MoE experts.</div>
    </li>
    <li>
      <span class="when">2023.09 – 2024.05</span>
      <div class="what">Alibaba, Tongyi Lab.</div>
    </li>
    <li>
      <span class="when">2023.03 – 2023.09</span>
      <div class="what">Microsoft Research, <a href="https://www.microsoft.com/en-us/research/group/machine-learning-research-group/">Machine Learning Area</a>, mentored by <a href="https://scholar.google.co.jp/citations?user=tob-U1oAAAAJ&amp;hl=en">Xu Tan</a>. I am deeply grateful to Xu Tan for his patient and rigorous mentorship, which laid the foundation for my growth as a researcher. Our collaborative efforts on the <a href="https://github.com/microsoft/muzic">Muzic project</a> boast 5k stars on GitHub.</div>
    </li>
  </ol>
</section>

<section class="section" id="publications">
  <h1>Recent Publications</h1>
  <div class="pub-list">
    <article class="pub">
      <a class="pub-title" href="https://openreview.net/forum?id=MpeyjgWbKt">Coupling Experts and Routers in Mixture-of-Experts via An Auxiliary Loss</a>
      <p class="pub-authors">Ang Lv et al.</p>
      <p class="pub-venue"><span class="venue">ICLR 2026</span> <span class="mark">Oral</span></p>
    </article>
    <article class="pub">
      <a class="pub-title" href="https://openreview.net/forum?id=JCTTLKEBza">PolarQuant: Leveraging Polar Transformation for Efficient Key Cache Quantization and Decoding Acceleration</a>
      <p class="pub-authors">Songhao Wu* and Ang Lv* et al.</p>
      <p class="pub-venue"><span class="venue">NeurIPS 2025</span></p>
    </article>
    <article class="pub">
      <a class="pub-title" href="https://icml.cc/virtual/2025/poster/46286">Autonomy-of-Experts Models</a>
      <p class="pub-authors">Ang Lv et al.</p>
      <p class="pub-venue"><span class="venue">ICML 2025</span></p>
    </article>
  </div>
</section>
