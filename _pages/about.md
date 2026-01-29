---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am Chao Zhou.

My research interests include near-field communications and movable antennas.


# 🔥 News
- *2024.11*: 🎉🎉 I received IEEE WCSP Best Paper Award for paper "[Channel Estimation for XL-IRS Assisted Wireless Systems with Double-sided Visibility Regions](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=Channel+Estimation+for+XL-IRS+Assisted+Wireless+Systems+with+Double-sided+Visibility+Regions&btnG=)", 2024.


你的思路非常正确！利用 CSS Counter 是在网页上实现 [J1], [C1] 这种特定格式自动编号的最专业做法。

不过，在 HTML 语法细节上有一点小瑕疵（多余的点号和未闭合的标签）。为了让排版更精美、更符合学术规范，我为你微调了代码：

HTML
<style>
  /* 基础列表样式重置 */
  .pub-list { list-style: none; padding-left: 0; }
  .pub-list li { margin-bottom: 10px; line-height: 1.5; }

  /* 期刊计数器 */
  .journals { counter-reset: j-section; }
  .journals li::before {
    counter-increment: j-section;
    content: "[J" counter(j-section) "] ";
    font-weight: bold;
    color: #2e6da4; /* 可选：给编号加点颜色更显眼 */
    margin-right: 5px;
  }

  /* 会议计数器 */
  .confs { counter-reset: c-section; }
  .confs li::before {
    counter-increment: c-section;
    content: "[C" counter(c-section) "] ";
    font-weight: bold;
    color: #d9534f;
    margin-right: 5px;
  }
</style>

# 📝 Publications 

### 📚 Journal Articles
<ul class="pub-list journals">
  <li>Liujia Yao, Changsheng You, **Chao Zhou**, Beixiong Zheng, and Weidong Mei, "[Position Optimization for Two-Layer Movable Antenna Systems](https://ieeexplore.ieee.org/document/11329408)," *IEEE Communications Letters*, 2026.</li>
  <li>Qianglong Dai, Yong Zeng, Huizhi Wang, Changsheng You, **Chao Zhou**, et al., "[A Tutorial on MIMO-OFDM ISAC: From Far-Field to Near-Field](https://ieeexplore.ieee.org/document/11328117)," *IEEE Communications Surveys & Tutorials*, 2026.</li>
</ul>

### 🤝 Conference Papers
<ul class="pub-list confs">
  <li>**Chao Zhou**, et al., "[Channel Estimation for XL-IRS Assisted Wireless Systems with Double-sided Visibility Regions](此处填链接)," in *Proc. IEEE WCSP*, 2024. 🏆 **(Best Paper Award)**</li>
</ul>





# 🎖 Honors and Awards
- *2021.10* More information coming soon. 
- *2021.09* More information coming soon.

# 📖 Educations
- *2019.06 - 2022.04 (now)*, More information coming soon.
- *2015.09 - 2019.06*, More information coming soon.

