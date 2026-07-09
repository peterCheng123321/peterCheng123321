<!--
  Profile README — mirrors LightSpace / petercheng.dev
  https://petercheng.dev
-->

<!-- Header: single SVG (banner + signal) so alignment stays locked -->
<p align="center">
  <a href="https://petercheng.dev">
    <img src="assets/banner.svg" alt="Zhongquan (Peter) Cheng — Software engineer & researcher · petercheng.dev" width="880" />
  </a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&duration=3200&pause=900&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=880&height=48&lines=Building+reliable+backends+%26+applied+ML;Open+to+Summer+2026+%C2%B7+WashU+MS+CS" alt="Building reliable backends and applied ML" />
</p>

<p align="center">
  <a href="https://petercheng.dev"><strong>petercheng.dev</strong></a>
  &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/petercheng/">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="mailto:chengzhongquan0630@gmail.com">Email</a>
  &nbsp;·&nbsp;
  <a href="https://petercheng.dev/resume.pdf">Résumé</a>
</p>

<table align="center" width="880">
  <tr>
    <td align="right" width="18%"><strong>Now</strong></td>
    <td width="4%"></td>
    <td align="left">M.S. CS, WashU · Backend @ <a href="https://undergraduation.com">Undergraduation.com</a></td>
  </tr>
  <tr>
    <td align="right"><strong>Focus</strong></td>
    <td></td>
    <td align="left">Backend · Applied ML · Computer Vision</td>
  </tr>
  <tr>
    <td align="right"><strong>Based</strong></td>
    <td></td>
    <td align="left">St. Louis — prev. Syracuse, Shanghai</td>
  </tr>
  <tr>
    <td align="right"><strong>Open to</strong></td>
    <td></td>
    <td align="left">Summer 2026 internships &amp; research</td>
  </tr>
</table>

<p align="center">
  <img src="assets/divider.svg" alt="" width="880" />
</p>

### § 00  ·  About

I build backend systems and ML pipelines at the intersection of reliable engineering and applied research: distributed request pipelines and LLM infrastructure at Undergraduation.com, sensor-based depression detection at Syracuse, and medical-imaging segmentation at WashU’s AI for Health Institute.

A habit of picking up the hard part of the stack — and then finishing it.

<p align="center">
  <img src="assets/divider.svg" alt="" width="880" />
</p>

### § 01  ·  Experience

<!-- Numbered timeline cards — no nested markdown lists (those break inside tables) -->

<table>
  <tr>
    <td width="56" valign="top" align="center">
      <br/>
      <code>01</code>
    </td>
    <td valign="top">
      <br/>
      <strong>Backend Intern</strong> · Undergraduation.com<br/>
      <sub>Sep 2025 — Present · Distributed systems · LLM infra · Security</sub>
      <br/><br/>
      • Distributed SSE + serverless request pipeline — 50+ concurrent users, zero blocking<br/>
      • Fault-tolerant LLM gateway with failover &amp; latency-based A/B routing — 99.9% uptime<br/>
      • PostgreSQL composite-key caching — <strong>−40%</strong> redundant queries<br/>
      • Row-Level Security + middleware — zero cross-tenant leakage on vector search
      <br/><br/>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <p align="center"><img src="assets/divider.svg" alt="" width="820" /></p>
    </td>
  </tr>
  <tr>
    <td width="56" valign="top" align="center">
      <br/>
      <code>02</code>
    </td>
    <td valign="top">
      <br/>
      <strong>Computer Vision Researcher</strong> · AI for Health Institute, WashU<br/>
      <sub>Jan 2025 — Jun 2026 · Medical imaging · Segmentation · Video pipelines</sub>
      <br/><br/>
      • Meta Sapien + OpenCV pipeline — segmentation masks across <strong>10,000+</strong> clinical frames<br/>
      • FFmpeg high-speed extraction — <strong>−60%</strong> preprocessing latency on 50+ hrs of footage<br/>
      • Dynamic exposure workflow — <strong>+80%</strong> human detection in low-light scenes
      <br/><br/>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <p align="center"><img src="assets/divider.svg" alt="" width="820" /></p>
    </td>
  </tr>
  <tr>
    <td width="56" valign="top" align="center">
      <br/>
      <code>03</code>
    </td>
    <td valign="top">
      <br/>
      <strong>Research Assistant</strong> · Salekin Lab, Syracuse University<br/>
      <sub>Feb 2024 — May 2025 · Mobile sensing · Deep learning · Clinical partnership</sub>
      <br/><br/>
      • Android multi-modal IMU collection framework (Kotlin, Factory pattern)<br/>
      • Dockerized ML training — environment setup <strong>2 hrs → 5 min</strong><br/>
      • Hybrid CNN-LSTM on high-frequency IMU — <strong>87%</strong> depression-biomarker accuracy<br/>
      • HIPAA-aligned data handling with clinical partners
      <br/><br/>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <p align="center"><img src="assets/divider.svg" alt="" width="820" /></p>
    </td>
  </tr>
  <tr>
    <td width="56" valign="top" align="center">
      <br/>
      <code>04</code>
    </td>
    <td valign="top">
      <br/>
      <strong>Data Science Intern</strong> · Asia Pulp &amp; Paper<br/>
      <sub>May 2023 — Jun 2023 · Forecasting · ETL · Warehouse optimization</sub>
      <br/><br/>
      • XGBoost sales forecasting with lag features — <strong>92%</strong> prediction accuracy<br/>
      • Automated ETL against the data warehouse — <strong>−40%</strong> extraction latency<br/>
      • High-dimensional transaction analysis for Shanghai-region strategy
      <br/><br/>
    </td>
  </tr>
</table>

<p align="center">
  <img src="assets/divider.svg" alt="" width="880" />
</p>

### § 02  ·  Selected work

| # | Project | Stack | |
|:-:|:---|:---|:-:|
| `01` | **[Patient-Monitoring Vision Pipeline](https://petercheng.dev/projects/patient-vision)** — overhead clinical video, sequence-error detection | Python · PyTorch · Meta Sapien · OpenCV · FFmpeg | [→](https://petercheng.dev/projects/patient-vision) |
| `02` | **[Engineering Course Scheduler](https://petercheng.dev/projects/course-scheduler)** — prereq-aware, conflict-free timetables | React · Node.js · AWS | [→](https://petercheng.dev/projects/course-scheduler) |
| `03` | **[ATS — Application Tracker](https://petercheng.dev/projects/application-tracker)** — Gmail ingestion + AI triage · *2nd place, Syracuse Tech Challenge* | React · Node · PostgreSQL · Gmail API | [→](https://petercheng.dev/projects/application-tracker) |
| `04` | **[IMU Depression-Signal Collector](https://petercheng.dev/projects/imu-collector)** — scheduled multi-modal sensing for Salekin Lab | Android · Kotlin · Signal Processing | [→](https://petercheng.dev/projects/imu-collector) |
| `05` | **[Library VR](https://petercheng.dev/projects/library-vr)** — gesture-driven campus library onboarding | Unity · C# · VR | [→](https://petercheng.dev/projects/library-vr) |

<p align="center">
  <img src="assets/divider.svg" alt="" width="880" />
</p>

### § 03  ·  Studies & stack

<table>
  <tr>
    <td width="50%" valign="top">

**Education**

**Washington University in St. Louis**  
M.S. Computer Science · Aug 2025 — May 2027  
GPA 3.7/4.0 · Algorithms, Distributed Systems, ML, CV

**Syracuse University**  
B.S. Computer Science · Sep 2021 — May 2025  
2nd Place · Syracuse Tech Challenge (AI for Mental Health)  
Senior Workshop Lead · CuseHacks 2023–2025

</td>
    <td width="50%" valign="top">

**Competencies**

`Python` `TypeScript` `Java` `C/C++` `C#` `SQL` `R`

`PyTorch` `TensorFlow` `scikit-learn` `XGBoost` `OpenCV`  
`pandas` `NumPy` `LLM orchestration`

`Node` `React` `Next.js` `PostgreSQL` `Redis` `Pinecone`  
`AWS` `Docker` `Android` `Unity` `FFmpeg`

</td>
  </tr>
</table>

<p align="center">
  <img src="assets/divider.svg" alt="" width="880" />
</p>

### § 04  ·  Elsewhere

<p align="center">
  <a href="https://petercheng.dev"><strong>petercheng.dev</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/peterCheng123321">GitHub</a>
  &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/petercheng/">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="mailto:chengzhongquan0630@gmail.com">Email</a>
  <br/><br/>
  <sub>A good email beats a bad meeting. · Open to Summer 2026</sub>
</p>
