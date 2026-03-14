---
title: "Intelligence Heterogeneous Computing Lab"
layout: single
permalink: /pages/team
author_profile: true
---

<style>

.page__title {
  font-size: 1.25rem;
  display: flex;
  align-items: center;
  gap: 0.0rem;
}

.page__title::after {
  content: "";
  display: inline-block;
  width: 160px;
  height: 36px;
  background: url("/assets/images/imperial_logo.png") no-repeat center / contain;
  margin-left: -2rem;
}

/* ===== research themes ===== */
.research-themes {
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
  margin: 0.75rem 0 1.5rem 0;
}

.research-theme-card {
  display: flex;
  flex-direction: row;
  align-items: stretch;
  border-radius: 8px;
  border: 1px solid rgba(255, 255, 255, 0.12);
  background: rgba(255, 255, 255, 0.03);
  cursor: pointer;
  transition: box-shadow 0.2s ease, transform 0.2s ease, border-color 0.2s ease, background-color 0.2s ease;
  overflow: hidden;
}

.research-theme-card:hover,
.research-theme-card.active {
  transform: translateY(-1px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.4);
  border-color: rgba(255, 255, 255, 0.25);
  background: rgba(255, 255, 255, 0.06);
}

.research-theme-content {
  flex: 1;
  min-width: 0;
  padding: 0.4rem 0.75rem;
}

.research-theme-figure {
  flex-shrink: 0;
  width: 235px;
  position: relative;
  overflow: hidden;
  background: rgba(255, 255, 255, 0.08);
  margin: 0;
}

.research-theme-figure img {
  width: 100%;
  height: 100%;
  min-height: 90px;
  object-fit: contain;
  display: block;
}

@media (max-width: 640px) {
  .research-theme-card {
    flex-direction: column;
  }

  .research-theme-figure {
    width: 100%;
    height: 140px;
  }
}

.research-theme-title {
  font-weight: 700;
  font-size: 0.95rem;
  margin: 0 0 0.2rem 0;
}

.research-theme-list {
  list-style: disc;
  padding-left: 1.1rem;
  margin: 0;
  font-size: 0.82rem;
  line-height: 1.35;
}

.research-theme-list li {
  margin-bottom: 0.1rem;
}

.research-theme-list li:last-child {
  margin-bottom: 0;
}

/* ===== people grid ===== */
.team-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 1rem;
  margin-top: 1rem;
}

@media (max-width: 900px) {
  .team-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

.team-card {
  background: rgba(255, 255, 255, 0.03);
  border: 1px solid rgba(255, 255, 255, 0.12);
  border-radius: 14px;
  padding: 1rem;
  text-align: center;
  transition: opacity 0.25s ease, transform 0.25s ease, box-shadow 0.25s ease;
}

.team-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 10px 24px rgba(0,0,0,0.08);
}

.team-card.faded {
  opacity: 0.18;
}

.team-photo {
  width: 60px;
  height: 60px;
  border-radius: 50%;
  object-fit: cover;
  margin: 0 auto 0.8rem auto;
  display: block;
}

.team-name {
  font-size: 0.55rem;
  font-weight: 700;
  margin-bottom: 0.2rem;
}

.team-role {
  font-size: 0.55rem;
  color: #666;
  margin-bottom: 0.6rem;
}

.team-topics {
  display: flex;
  flex-wrap: wrap;
  gap: 0.35rem;
  justify-content: center;
}

.team-topic {
  font-size: 0.8rem;
  padding: 0.2rem 0.5rem;
  background: rgba(255, 255, 255, 0.08);
  border-radius: 999px;
}

.team-note {
  margin-top: 0.5rem;
  font-size: 0.88rem;
  color: rgba(255, 255, 255, 0.7);
}
</style>


<p style="text-align:center; margin: 0 0 0.5rem -0.5rem;">
  <img src="/assets/images/imperial_building.png" alt="Imperial College London" style="max-width: 520px; width: 100%; border-radius: 10px; box-shadow: 0 8px 24px rgba(0,0,0,0.35);">
</p>

## Research Themes
<div class="research-themes">
  <!-- Row 1: Efficient Agent -->
  <div class="research-theme-card" data-topic="efficient-agent">
    <div class="research-theme-content">
      <div class="research-theme-title">Efficient / Edge Agent</div>
      <ul class="research-theme-list">
        <li>
          <strong>Efficient ML:</strong>
          <a href="https://arxiv.org/pdf/2509.26432?">ICLR'26</a>,
          <a href="https://arxiv.org/pdf/2503.12649">ICCV'25</a>,
          <a href="https://aclanthology.org/anthology-files/anthology-files/pdf/findings/2025.findings-emnlp.120.pdf">EMNLP'24</a>,
          <a href="https://arxiv.org/pdf/2410.13461">ICLR'24</a>
        </li>
        <li>
          <strong>AI Reasoning:</strong>
          <a href="https://arxiv.org/pdf/2509.00195">ASPLOS'26</a>,
          <a href="https://arxiv.org/pdf/2505.11730">NeurIPS'25</a>
        </li>
      </ul>
    </div>
    <figure class="research-theme-figure">
      <img src="/assets/images/themes/theme-1.png" alt="Efficient and Edge Agent">
    </figure>
  </div>

  <!-- Row 2: Domain-Specific Accelerators -->
  <div class="research-theme-card" data-topic="ml-accelerator">
    <div class="research-theme-content">
      <div class="research-theme-title">Domain-Specific Accelerators and Machine Learning Systems</div>
      <ul class="research-theme-list">
        <li>
          <strong>Reconfigurable Accelerators:</strong>
          <a href="https://ieeexplore.ieee.org/document/10609569">ISCA'24</a>,
          <a href="https://arxiv.org/pdf/2505.11730">MICRO'22</a>,
          <a href="https://dl.acm.org/doi/abs/10.1145/3489517.3530451">DAC'22</a>, 
          <a href="https://arxiv.org/pdf/2105.09163">DAC'21</a>, 
        </li>
        <li>
          <strong>Machine Learning Systems:</strong>
          <a href="https://os-hxfan.github.io/">MLSys'26</a>,
          <a href="https://arxiv.org/pdf/2509.00195">ASPLOS'26</a>,
          <a href="https://arxiv.org/pdf/2310.11096">MICRO'23</a>,
          <a href="https://arxiv.org/pdf/2308.06849">DAC'23</a>
        </li>
        <li>
          <strong>FPGA-based Acceleration:</strong>
          <a href="https://ieeexplore.ieee.org/abstract/document/8825127">ASAP'19 (Best Paper Nominee)</a>,
          <a href="https://www.doc.ic.ac.uk/~wl/papers/18/fpt18hf.pdf">FPT'18 (Best Paper Nominee)</a>
        </li>
      </ul>
    </div>
  </div>

  <!-- Row 3: Quantum Computing (last) -->
  <div class="research-theme-card" data-topic="quantum-computing">
    <div class="research-theme-content">
      <div class="research-theme-title">Quantum Computing</div>
      <ul class="research-theme-list">
        <li>
          <strong>Quantum Design Automation:</strong>
          <a href="https://arxiv.org/pdf/2504.14557">DAC'25</a>,
          <a href="https://dl.acm.org/doi/pdf/10.1145/3489517.3530403">DAC'22</a>
        </li>
        <li>
          <strong>Classical Quantum Simulation:</strong>
          <a href="https://ieeexplore.ieee.org/abstract/document/11408466">HPCA'26</a>,
          <a href="https://arxiv.org/pdf/2503.19894">DAC'25</a>
        </li>
      </ul>
    </div>
    <figure class="research-theme-figure">
      <img src="/assets/images/themes/theme-3.png" alt="Quantum Computing">
    </figure>
  </div>
</div>

## Team Members

<div class="team-grid">
  <div class="team-card" data-topics="efficient-agent ml-accelerator quantum-computing">
    <img class="team-photo" src="/assets/images/Fan.jpg" alt="Hongxiang Fan">
    <div class="team-name">Hongxiang Fan</div>
    <div class="team-role">PI / Research Lead</div>
    <div class="team-note">
        <a href="https://scholar.google.com/citations?user=iBT_uw4AAAAJ&hl=en" target="_blank" rel="noopener">
        <i class="fab fa-fw fa-google"></i>
        </a>
        &nbsp;|&nbsp;
        <a href="https://www.linkedin.com/in/hongxiang-fan-9a6311149/?originalSubdomain=uk" target="_blank" rel="noopener">
        <i class="fab fa-linkedin"></i> 
        </a>
    </div>
  </div>

  <div class="team-card" data-topics="efficient-agent ml-accelerator">
    <img class="team-photo" src="/assets/images/team/Mark_Chen.png" alt="Member 1">
    <div class="team-name">Mark (Hao) Chen</div>
    <div class="team-role">PhD Student <br> (2024 Fall)</div>
    <div class="team-note">
        <a href="https://scholar.google.com/citations?user=O6ajbEoAAAAJ&hl" target="_blank" rel="noopener">
        <i class="fab fa-fw fa-google"></i>
        </a>
        &nbsp;|&nbsp;
        <a href="https://www.linkedin.com/in/mark-hao-chen/" target="_blank" rel="noopener">
        <i class="fab fa-linkedin"></i> 
        </a>
    </div>
  </div>

  <div class="team-card" data-topics="efficient-agent ml-accelerator">
    <img class="team-photo" src="/assets/images/team/Zhiwen_Mo.png" alt="Member 2">
    <div class="team-name">Zhiwen Mo</div>
    <div class="team-role">PhD Student <br> (2025 Spring)</div>
    <div class="team-note">
        <a href="https://scholar.google.com/citations?user=rzG0eHwAAAAJ&hl=en" target="_blank" rel="noopener">
        <i class="fab fa-fw fa-google"></i>
        </a>
        &nbsp;|&nbsp;
        <a href="https://www.linkedin.com/in/zhiwen-mo-954513351/" target="_blank" rel="noopener">
        <i class="fab fa-linkedin"></i> 
        </a>
    </div>
  </div>

  <div class="team-card" data-topics="quantum-computing">
    <img class="team-photo" src="/assets/images/team/Abbas.jpeg" alt="Member 3">
    <div class="team-name">Abbas Bracken Ziad</div>
    <div class="team-role">PhD Student <br> (2025 Fall)</div>
    <div class="team-note">
        <a href="https://scholar.google.com/citations?user=i3pFH8MAAAAJ&hl=en" target="_blank" rel="noopener">
        <i class="fab fa-fw fa-google"></i>
        </a>
        &nbsp;|&nbsp;
        <a href="https://www.linkedin.com/in/abbasbrackenziad/?originalSubdomain=uk" target="_blank" rel="noopener">
        <i class="fab fa-linkedin"></i> 
        </a>
    </div>
  </div>

  <div class="team-card" data-topics="efficient-agent ml-accelerator">
    <img class="team-photo" src="/assets/images/team/Guoyu_Li.jpeg" alt="Member 4">
    <div class="team-name">Guoyu Li</div>
    <div class="team-role">PhD Student <br> (2025 Fall)</div>
    <div class="team-note">
        <a href="https://os-hxfan.github.io/" target="_blank" rel="noopener">
        <i class="fab fa-fw fa-google"></i>
        </a>
        &nbsp;|&nbsp;
        <a href="https://www.linkedin.com/in/guoyu-li-74696633b/?originalSubdomain=uk" target="_blank" rel="noopener">
        <i class="fab fa-linkedin"></i> 
        </a>
    </div>
  </div>


  <div class="team-card" data-topics="ml-accelerator">
    <img class="team-photo" src="/assets/images/team/Euan.jpeg" alt="Member 5">
    <div class="team-name">Euan Turner</div>
    <div class="team-role">Incoming PhD Student, MEng<br> (2026 Fall)</div>
    <div class="team-note">
        <a href="https://os-hxfan.github.io/" target="_blank" rel="noopener">
        <i class="fab fa-fw fa-google"></i>
        </a>
        &nbsp;|&nbsp;
        <a href="https://www.linkedin.com/in/euan-turner-209a7a200/?originalSubdomain=uk" target="_blank" rel="noopener">
        <i class="fab fa-linkedin"></i> 
        </a>
    </div>
  </div>

  <div class="team-card" data-topics="quantum-computing">
    <!-- <img class="team-photo" src="/assets/images/team/Guoyu_Li.jpeg" alt="Member 6"> -->
    <div class="team-name">Charlie Campbell </div>
    <div class="team-role">Incoming PhD Student, MEng <br> (2026 Fall)</div>
    <div class="team-note">
        <a href="https://os-hxfan.github.io/" target="_blank" rel="noopener">
        <i class="fab fa-fw fa-google"></i>
        </a>
        &nbsp;|&nbsp;
        <a href="https://www.linkedin.com/in/charlie-campbell-641a38188/?originalSubdomain=uk" target="_blank" rel="noopener">
        <i class="fab fa-linkedin"></i> 
        </a>
    </div>
  </div>

  <div class="team-card" data-topics="efficient-agent">
    <img class="team-photo" src="/assets/images/team/Guanxi_Lu.png" alt="Member 7">
    <div class="team-name">Guanxi LU</div>
    <div class="team-role">Incoming PhD Student, MEng <br> (2026 Fall)</div>
    <div class="team-note">
        <a href="https://scholar.google.com/citations?user=7G4CFD8AAAAJ&hl=en&oe=CP1251" target="_blank" rel="noopener">
        <i class="fab fa-fw fa-google"></i>
        </a>
        &nbsp;|&nbsp;
        <a href="https://www.linkedin.com/in/guanxi-lu-79a8ab238/" target="_blank" rel="noopener">
        <i class="fab fa-linkedin"></i> 
        </a>
    </div>
  </div>

  <div class="team-card" data-topics="quantum-computing">
    <img class="team-photo" src="/assets/images/team/Shuang_Liang.jpeg" alt="Member 8">
    <div class="team-name">Shuang Liang</div>
    <div class="team-role">Research Assistant </div>
    <div class="team-note">
        <a href="https://os-hxfan.github.io/" target="_blank" rel="noopener">
        <i class="fab fa-fw fa-google"></i>
        </a>
        &nbsp;|&nbsp;
        <a href="https://www.linkedin.com/in/shuang-liang-icl/?originalSubdomain=uk" target="_blank" rel="noopener">
        <i class="fab fa-linkedin"></i> 
        </a>
    </div>
  </div>


  <div class="team-card" data-topics="quantum-computing">
    <!-- <img class="team-photo" src="/assets/images/team/Jubo_Xu.jpeg" alt="Member 6"> -->
    <div class="team-name">Jubo Xu</div>
    <div class="team-role">Incoming PhD Student, RA <br> (2026 Fall) </div>
    <div class="team-note">
        <a href="https://os-hxfan.github.io/" target="_blank" rel="noopener">
        <i class="fab fa-fw fa-google"></i>
        </a>
        &nbsp;|&nbsp;
        <a href="https://github.com/Jubo-Xu" target="_blank" rel="noopener">
        <i class="fab fa-linkedin"></i> 
        </a>
    </div>
  </div>


</div>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const themeCards = document.querySelectorAll(".research-theme-card");
  const teamCards = document.querySelectorAll(".team-card");

  function applyFilter(topic) {
    teamCards.forEach(card => {
      const topics = (card.dataset.topics || "").split(" ");
      if (topic === "all" || topics.includes(topic)) {
        card.classList.remove("faded");
      } else {
        card.classList.add("faded");
      }
    });
  }

  function clearFilter() {
    teamCards.forEach(card => card.classList.remove("faded"));
    themeCards.forEach(card => card.classList.remove("active"));
  }

  themeCards.forEach(card => {
    const topic = card.dataset.topic;

    card.addEventListener("mouseenter", () => {
      clearFilter();
      card.classList.add("active");
      applyFilter(topic);
    });

    card.addEventListener("mouseleave", () => {
      clearFilter();
    });

    card.addEventListener("click", () => {
      const isActive = card.classList.contains("active");
      clearFilter();
      if (!isActive) {
        card.classList.add("active");
        applyFilter(topic);
      }
    });
  });
});
</script>
