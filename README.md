<!--
  nimraa9090 — GitHub Profile README
  Place this file in a repo named exactly "nimraa9090" (same as your username)
  to make it render on your profile page: https://github.com/nimraa9090
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,100:1E3A8A&height=180&section=header&text=Nimra%20%7C%20AI%20%26%20Full%20Stack%20Engineer&fontSize=32&fontColor=ffffff&fontAlignY=35&desc=Founder%20%26%20Solo%20Developer%20%40%20Goniaa&descAlignY=52&descSize=16" width="100%"/>

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-goniaa.pk-0F172A?style=flat-square)](https://goniaa.pk)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white)](#)

</div>

<br/>

## About Me

I'm an AI/Full Stack engineer building **[Goniaa](https://goniaapk.vercel.app/)**, a fashion e-commerce ecosystem I designed, built, and shipped solo — a public storefront, an AI-powered brand management dashboard, and a native mobile app, all in production with real users and real data.

- 🎓 BS Artificial Intelligence @ Hazara University (Expected June 2027)
- 🛠️ Currently building **Goniaa** end-to-end: storefront → AI ops dashboard → mobile app
- 🧠 Comfortable across the stack: Next.js/TypeScript frontends, Supabase/Postgres backends, LLM-powered internal tools, and React Native mobile
- 📈 Interested in applied ML, agentic tooling, and building products that actually ship — not just notebooks
- 🌍 Open to remote roles with US/UK startups

---

## Tech Stack

<div align="center">

**Languages**
<br/>
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Frontend & Mobile**
<br/>
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Backend & Data**
<br/>
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

**AI / ML**
<br/>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_API-F55036?style=for-the-badge&logo=groq&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

**Tools & Platforms**
<br/>
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

</div>

---

## Current Focus

-  Shipping v2 of the **Goniaa AI Brand Manager** — an 11-tab operations dashboard that uses an LLM (Groq / Llama 3.3 70B) to help run a real e-commerce brand
-  Stabilizing the **Goniaa mobile app** (React Native + Expo SDK 54) ahead of a public release
-  Studying applied system design — moving from "it works" to architecture that scales
-  Preparing for AI/Full Stack internships and junior roles at product-focused startups

---

## Featured Projects

### Goniaa — AI-Powered Fashion E-Commerce Ecosystem
**Founder & Solo Developer** · Live in production

A full ecosystem, not a demo: a public storefront customers actually buy from, an internal AI-driven dashboard that runs the brand's operations, and a companion mobile app — architected, built, and shipped end-to-end by one person.

| | |
|---|---|
| **Storefront** | Next.js 15 storefront on Vercel — [goniaa.pk](https://goniaapk.vercel.app/) |
| **AI Brand Manager** | 11-tab internal dashboard (analytics, inventory, content, ops) powered by the Groq API (Llama 3.3 70B) for AI-assisted decision-making |
| **Mobile App** | React Native (Expo SDK 54) companion app |
| **Data Layer** | Supabase (Postgres, Auth, Storage) |

**Engineering highlights**
- Designed and implemented an 11-tab dashboard from a blank repo to production, including auth, data modeling, and an LLM integration layer
- Diagnosed and resolved a production-blocking React error (recharts #130) by replacing the charting layer with custom CSS-based charts
- Root-caused a recurring `CSSStyleDeclaration` crash traced to JSX spread operators in style props, and eliminated it by refactoring to reusable styled components
- Fixed Supabase auth misconfiguration and replaced deprecated dependencies to unblock the build

**[Live Site](https://goniaapk.vercel.app/)** · **[Dashboard Demo Video](#)** · **[Mobile APK](#)** · **[Case Study Repo](https://github.com/nimraa9090/goniaa-ecosystem)**

---

### Medical Image Classification — Blood Smear Analysis (CNNs + XAI)
Deep learning pipeline classifying red blood cell abnormalities on the AneRBC dataset. Benchmarked custom CNNs against transfer learning (MobileNetV2, ResNet18, DenseNet121), reaching **82.7%** accuracy with DenseNet121, and added Grad-CAM explainability to visualize model decisions.

**Stack:** PyTorch · Transfer Learning · Grad-CAM
**[Repo →](https://github.com/nimraa9090/Annemia-dignoses-system)**

---

###  Reinforcement Learning Suite
DQN and tabular Q-learning agents trained on classic control environments (CartPole, Lunar Lander, FrozenLake), covering exploration strategies, reward shaping, and convergence analysis.

**Stack:** Python · PyTorch/Gymnasium
**[Repo →](https://github.com/nimraa9090/AI-projects)**

---

### NLP Toolkit — Fake News & Spam Detection, Summarization
A set of NLP models covering classification (fake news, spam) and text summarization, built to compare classical ML pipelines against transformer-based approaches.

**Stack:** Python · scikit-learn · NLP
**[Repo →](https://github.com/nimraa9090/AI-projects)**

---

## GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=nimraa9090&show_icons=true&theme=default&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nimraa9090&layout=compact&hide_border=true" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=nimraa9090&hide_border=true" />

</div>

---

## Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=nimraa9090&theme=minimal&hide_border=true" width="100%"/>

</div>

---

## Let's Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/Website-goniaa.pk-0F172A?style=for-the-badge)](https://goniaa.pk)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](#)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1E3A8A,100:0F172A&height=100&section=footer" width="100%"/>
