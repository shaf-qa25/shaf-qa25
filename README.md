<!-- 
GitHub Action workflow to generate the contribution snake:
Create a file at .github/workflows/snake.yml with the following contents:

name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *" # Run every 12 hours
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5
    
    steps:
      - name: generate-github-contribution-grid-snake
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: shaf-qa25
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark&color_snake=#FF69B4&color_dots=#161b22,#f8bbd0,#ef93c4,#ff69b4,#c71585
            
      - name: push github-contribution-grid-snake to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
-->

<div align="center">
  <!-- Custom Gradient Header Banner (using the local banner.svg file) -->
  <img src="./banner.svg" width="100%" alt="Shafqa Fatma Banner" style="border-radius: 12px; margin-bottom: 20px;" />

  <br /><br />

  <!-- Centered Large Title -->
  <h1>Hey there, I'm Shafqa Fatma 👋</h1>

  <!-- Animated Typing Text -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=FF69B4&center=true&vCenter=true&width=500&lines=Full+Stack+Developer;IT+Undergrad+%40+AKGEC;Open+Source+Contributor" alt="Typing SVG" />
  </a>

  <br /><br />

  <!-- Pink GitHub Badges -->
  <p align="center">
    <a href="https://github.com/shaf-qa25">
      <img src="https://img.shields.io/github/followers/shaf-qa25?label=Followers&style=for-the-badge&logo=github&color=EF93C4&logoColor=white" alt="Followers" />
    </a>
    <a href="https://github.com/shaf-qa25">
      <img src="https://img.shields.io/github/stars/shaf-qa25?label=Stars&style=for-the-badge&logo=github&color=F8BBD0&logoColor=white" alt="Stars" />
    </a>
    <a href="https://github.com/shaf-qa25">
      <img src="https://komarev.com/normal-badge/?username=shaf-qa25&color=ff69b4&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile Views" />
    </a>
  </p>
</div>

<br /><hr /><br />

<!-- About Me Section with Wrapping Image (No Borders) -->
<img align="right" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExbWdtcmN0cWNpMHp1bWc3M3Y4cmk2MHphOHlseHhpdnJvM2p6b2phMCZlcD12MV9pbnRlcm5hbF9naWZfYnlfZ2lmcyZjdD1z/L13yI8917j5DTC67rP/giphy.gif" width="30%" alt="Coding Illustration" />

### 💫 About Me
I am a passionate **Full Stack Developer** and an IT undergraduate at **Ajay Kumar Garg Engineering College (2024-2028)**. Currently, I am expanding my skills as a **Frontend Developer Intern** at **MediKloud Tech** and contributing as a developer at **BDCOE**.

* 💼 Frontend Developer Intern at **MediKloud Tech** (developing responsive layouts and reusable UI modules)
* 🌱 Diving deep into **Prisma, Drizzle ORM, PostgreSQL, and FastAPI**
* 🚀 Passionate about building robust web apps, SaaS tools, and auditing ML models for fairness
* 💬 Ask me about **React, Next.js, TypeScript, and MongoDB**
* ✉️ Reach out to me: [**fatmashafqa4@gmail.com**](mailto:fatmashafqa4@gmail.com)

<br clear="right" />

<br /><hr /><br />

<!-- Tech Stack Section -->
<div align="center">
  <h3>🛠️ My Tech Stack</h3>
  <br />
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html,css,js,ts,cpp,py,react,nextjs,nodejs,express,postgres,mongodb,prisma,tailwind,git,github,postman,vercel,firebase&perline=10" alt="My Tech Stack" />
  </a>
</div>

<br /><hr /><br />

<!-- Stats Section -->
<div align="center">
  <h3>📊 GitHub Statistics</h3>
  <br />
  <table align="center" style="border: none; border-collapse: collapse;">
    <tr style="border: none;">
      <td align="center" style="border: none; padding: 10px;">
        <a href="https://github.com/shaf-qa25">
          <img src="https://github-readme-streak-stats.herokuapp.com/?user=shaf-qa25&background=0D1117&border=EF93C4&stroke=EF93C4&ring=FF69B4&fire=FF69B4&currRing=EF93C4&sideRing=EF93C4&sideNums=FFFFFF&currNums=FFFFFF&meta=F8BBD0&dates=F8BBD0" alt="GitHub Streak" />
        </a>
      </td>
    </tr>
    <tr style="border: none;">
      <td align="center" style="border: none; padding: 10px;">
        <a href="https://github.com/shaf-qa25">
          <img src="https://github-readme-activity-graph.vercel.app/graph?username=shaf-qa25&bg_color=0D1117&color=EF93C4&line=FF69B4&point=F8BBD0&area=true&hide_border=true" width="100%" alt="GitHub Activity Graph" />
        </a>
      </td>
    </tr>
  </table>
</div>

<br /><hr /><br />

<!-- Contribution Snake -->
<div align="center">
  <h3>🐍 Contribution Snake</h3>
  <br />
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/shaf-qa25/shaf-qa25/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/shaf-qa25/shaf-qa25/output/github-contribution-grid-snake.svg">
    <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/shaf-qa25/shaf-qa25/output/github-contribution-grid-snake.svg" width="100%">
  </picture>
</div>

<br /><hr /><br />

<!-- Connect Badge Section -->
<div align="center">
  <h3>🤝 Connect with Me</h3>
  <br />
  <p align="center">
    <a href="https://linkedin.com/in/shafqa-fatma-bb0111380" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-EF93C4?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:fatmashafqa4@gmail.com">
      <img src="https://img.shields.io/badge/Email-FF69B4?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
  </p>
</div>

<br />

<!-- Waving Footer (using local footer.svg) -->
<div align="center">
  <img src="./footer.svg" width="100%" alt="Footer Wave" />
</div>
