---
layout: default
title: 首页
permalink: /
---
<div class="home">
  <div class="site-header-container {% if site.cover %}has-cover{% endif %}" {% if site.cover %}style="background-image: url({{ site.cover | prepend: site.baseurl }});"{% endif %}>
    <div class="scrim {% if site.cover %}has-cover{% endif %}">
      <header class="site-header">
        <h1 class="title">{{ site.title }}</h1>
        {% if site.subtitle %}<p class="subtitle">{{ site.subtitle }}</p>{% endif %}
      </header>
    </div>
  </div>
  <div class="site-header-container has-cover" style="background-image: url(/assets/header_image2.jpg);">
    <div class="scrim has-cover" style="background: rgba(33,33,33,0.3);">
      <header class="site-header">
        <h1 class="title">主要方向</h1>
        <p class="subtitle">具有认知能力的人工智能系统研究，提高机器学习的可信赖水平</p>
      </header>
    </div>
  </div>
  <div class="site-header-container has-cover" style="background-image: url(/assets/header_image3.jpg);">
   <div class="scrim has-cover" style="background: rgba(33,33,33,0.3);">
     <header class="site-header">
        <h1 class="title">理论研究</h1>
        <p class="subtitle">
          <ol>
            <li>认知计算：模拟认知过程，注重过程与结果的充要关系，追求计算结果在哲学与数学上的可解释性； 主要应用方向为：形式概念分析，医学大数据分析。</li>
            <li>机器学习：传统分类器研究与深度学习研究，注重结果的可用性。与认知计算结合，提升学习结果的可信性。主要应用方向为：以帕金森病为代表的机器诊断。</li>
            <li>机器视觉：模拟视觉感知与分析过程。包括可见光分析与红外热像分析，目前以医学工程应用为主。</li>
            <li>工业数据传感与分析：以android、FPGA为实现平台，侧重工业数据的传感器采集、传输与分析，实现工业现代化。</li>
          </ol>
        </p>
      </header>
    </div>
  </div>
</div>
