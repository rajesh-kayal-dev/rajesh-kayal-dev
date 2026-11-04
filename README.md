<div align="center">

<img src="./assets/banner.svg" width="100%" alt="Rajesh Kayal — Backend Engineer" />


<img src="./assets/divider.svg" width="100%" alt="" />


### How I Build Products

<sub>Turning real-world problems into reliable, scalable and maintainable software.</sub>

```mermaid
%%{init: {
  "theme": "base",
  "themeVariables": {
    "fontFamily": "-apple-system, 'Segoe UI', Helvetica, Arial, sans-serif",
    "fontSize": "14px",
    "lineColor": "#388bfd"
  },
  "flowchart": { "curve": "basis", "nodeSpacing": 36, "rankSpacing": 48, "padding": 16, "htmlLabels": true }
}}%%
flowchart LR
    A("<b>01 · UNDERSTAND</b><br/>Problem and<br/>requirements")
    B("<b>02 · ARCHITECT</b><br/>System design and<br/>trade-offs")
    C("<b>03 · ENGINEER</b><br/>APIs and<br/>data flow")
    D("<b>04 · VALIDATE</b><br/>Testing and<br/>reliability")
    E("<b>05 · DELIVER</b><br/>Deploy and<br/>monitor")

    A --> B --> C --> D --> E
    E -. "Feedback and iteration" .-> A

    classDef stage fill:#0d1117,stroke:#388bfd,stroke-width:1.5px,color:#e6edf3
    classDef ship fill:#0d1117,stroke:#3fb950,stroke-width:1.5px,color:#e6edf3
    class A,B,C,D stage
    class E ship

    linkStyle 0,1,2,3 stroke:#388bfd,stroke-width:2px
    linkStyle 4 stroke:#22d3ee,stroke-width:1.5px,stroke-dasharray:5 4
```

<img src="./assets/divider.svg" width="100%" alt="" />


<h3 align="left">Featured Projects</h3>

<details>
<summary><strong>01 · Orderly</strong> — Real-Time Food Delivery Platform</summary>
<br>
<p align="center">
  <img src="assets/projects/01-orderly/01-orderly-app.webp" alt="Orderly mobile app screens: home with search and offer banner, menu with food items, and order confirmation with delivery estimate" width="48%" />
  <img src="assets/projects/01-orderly/02-orderly-web.webp" alt="Orderly web application on a laptop beside a phone showing live order tracking, with a service architecture sketch above" width="48%" />
</p>
<p>Real-time food delivery platform connecting customers, restaurants, and delivery partners. Focuses on domain-focused services, order workflows, Kafka-based event communication, and realtime updates.</p>
<p><strong>Tech Stack</strong><br><img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" /> <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" /> <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" /> <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" /> <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Apache Kafka" /> <img src="https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="Socket.IO" /></p>
<p><a href="https://github.com/rajesh-kayal-dev/orderly"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a> <a href="https://orderly-puce-rho.vercel.app/"><img src="https://img.shields.io/badge/Live_Demo-2EA44F?style=flat-square&logo=googlechrome&logoColor=white" alt="Live Demo" /></a> <a href="https://github.com/rajesh-kayal-dev/orderly/tree/9ddfd1df8b31df2fc2f3c941a005e31d60da77a8/docs"><img src="https://img.shields.io/badge/Docs-0969DA?style=flat-square&logo=readthedocs&logoColor=white" alt="Docs" /></a></p>
</details>

<details>
<summary><strong>02 · Drawzware</strong> — System Design &amp; Architecture Diagramming</summary>
<br>
<p align="center">
  <img src="assets/projects/02-drawzware/01-drawzware-workspace.webp" alt="Drawzware workspace on a laptop showing an e-commerce microservices architecture diagram with ER and sequence diagram panels" width="48%" />
  <img src="assets/projects/02-drawzware/02-drawzware-collaborative-canvas.webp" alt="Drawzware real-time collaborative canvas with a system diagram, AI suggestion and MCP integration panels" width="48%" />
</p>
<p>Modern visual system-design workspace for creating architecture, sequence, and ER diagrams. Supports structured diagramming and collaborative system-design workflows.</p>
<p><strong>Tech Stack</strong><br><img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" /> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" /> <img src="https://img.shields.io/badge/React_Flow-FF0072?style=flat-square&logo=reactflow&logoColor=white" alt="React Flow" /> <img src="https://img.shields.io/badge/Zustand-433E38?style=flat-square" alt="Zustand" /> <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" /> <img src="https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white" alt="shadcn/ui" /> <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white" alt="Zod" /></p>
<p><a href="https://github.com/rajesh-kayal-dev/Drawzware"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a> <a href="https://drawzware.vercel.app/"><img src="https://img.shields.io/badge/Live_Demo-2EA44F?style=flat-square&logo=googlechrome&logoColor=white" alt="Live Demo" /></a> <a href="https://github.com/rajesh-kayal-dev/Drawzware/tree/5799e456c3b518b54f11b8e094c86b7e9906d920/docs"><img src="https://img.shields.io/badge/Docs-0969DA?style=flat-square&logo=readthedocs&logoColor=white" alt="Docs" /></a></p>
</details>

<details>
<summary><strong>03 · Calby</strong> — Personal Desktop Assistant</summary>
<br>
<p align="center">
  <img src="assets/projects/03-calby/01-calby-dashboard.webp" alt="Calby dashboard on a laptop with voice assistant, reminders, calendar and personal memory panels" width="48%" />
  <img src="assets/projects/03-calby/02-calby-desktop-assistant.webp" alt="Calby desktop assistant greeting on a laptop with upcoming reminders, calendar and personal memory panels" width="48%" />
</p>
<p>Personal desktop assistant for voice-powered interactions, reminders, calendar scheduling, and contextual personal memory. Runs as a desktop application and connects everyday tasks in one place.</p>
<p><strong>Tech Stack</strong><br><img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" alt="Electron" /> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" /> <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" /> <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" /> <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" /> <img src="https://img.shields.io/badge/Google_Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Google Gemini API" /></p>
<p><a href="https://github.com/rajesh-kayal-dev/calby-desktop"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a> <a href="https://calby-mu.vercel.app/"><img src="https://img.shields.io/badge/Live_Demo-2EA44F?style=flat-square&logo=googlechrome&logoColor=white" alt="Live Demo" /></a> <a href="https://github.com/rajesh-kayal-dev/calby-desktop/tree/7a26e711c8b06f0f6ed215a22f454c872f9c3d6a/docs"><img src="https://img.shields.io/badge/Docs-0969DA?style=flat-square&logo=readthedocs&logoColor=white" alt="Docs" /></a></p>
</details>

<details>
<summary><strong>04 · CanIClone</strong> — AI-Assisted Product Research &amp; MVP Planning</summary>
<br>
<p align="center">
  <img src="assets/projects/04-caniclone/01-caniclone-product-analysis.webp" alt="CanIClone product analysis view" width="48%" />
  <img src="assets/projects/04-caniclone/02-caniclone-ideas-to-mvp.webp" alt="CanIClone product analysis of an example product with AI assistant research and a generated MVP prompt" width="48%" />
</p>
<p>AI-assisted development workspace for exploring products, understanding features and complexity, researching alternatives, and turning product context into focused prompts and MVP specifications.</p>
<p><strong>Tech Stack</strong><br><img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" /> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" /> <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" /> <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" /> <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" /> <img src="https://img.shields.io/badge/Firecrawl-FF6B35?style=flat-square" alt="Firecrawl" /> <img src="https://img.shields.io/badge/Vercel_AI_SDK-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel AI SDK" /></p>
<p><a href="https://github.com/rajesh-kayal-dev/CanIClone"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a> <a href="https://caniclone.vercel.app/"><img src="https://img.shields.io/badge/Live_Demo-2EA44F?style=flat-square&logo=googlechrome&logoColor=white" alt="Live Demo" /></a> <a href="https://github.com/rajesh-kayal-dev/CanIClone/tree/main/docs"><img src="https://img.shields.io/badge/Docs-0969DA?style=flat-square&logo=readthedocs&logoColor=white" alt="Docs" /></a></p>
</details>

<details>
<summary><strong>05 · BWC Clothing</strong> — E-Commerce Store</summary>
<br>
<p align="center">
  <img src="assets/projects/05-bwc-clothing/01-bwc-mobile.webp" alt="BWC Clothing storefront on three phones showing new arrivals, hoodies and a product page" width="48%" />
  <img src="assets/projects/05-bwc-clothing/02-bwc-web.webp" alt="BWC Clothing web storefront on a laptop showing a new arrivals collection and product listing" width="48%" />
</p>
<p>E-commerce website for an online clothing store, featuring user authentication, product browsing, shopping cart, wishlist, secure payment integration, and an admin dashboard.</p>
<p><strong>Tech Stack</strong><br><img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel" /> <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP" /> <img src="https://img.shields.io/badge/Blade-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Blade" /> <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" /> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" /></p>
<p><a href="https://github.com/rajesh-kayal-dev/bwcclothing"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a> <a href="https://bwcclothing.com/"><img src="https://img.shields.io/badge/Live_Demo-2EA44F?style=flat-square&logo=googlechrome&logoColor=white" alt="Live Demo" /></a></p>
</details>

<details>
<summary><strong>06 · Inwood Pizza</strong> — Local Pizzeria &amp; Online Ordering Website</summary>
<br>
<p align="center">
  <img src="assets/projects/06-inwood-pizza/01-inwood-app.webp" alt="Inwood Pizza mobile ordering screens showing pickup and delivery, pizza menu and cart" width="48%" />
  <img src="assets/projects/06-inwood-pizza/02-inwood-website.webp" alt="Inwood Pizza desktop website on a laptop with menu items and an order cart" width="48%" />
</p>
<p>Local pizzeria website and ordering experience for fresh pizza, online orders, private events, and catering. The supplied visual references show mobile ordering flows and the desktop website.</p>
<p><strong>Tech Stack</strong><br><img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" /> <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel" /> <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP" /> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" /> <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white" alt="Bootstrap" /></p>
<p><a href="https://www.inwoodpizzanyc.com/"><img src="https://img.shields.io/badge/Live_Demo-2EA44F?style=flat-square&logo=googlechrome&logoColor=white" alt="Live Demo" /></a> &nbsp;<em>GitHub and Docs are private</em></p>
</details>

<img src="./assets/divider.svg" width="100%" alt="" />

### Engineering Toolkit
<div align="center">

<a href="https://wndcd2ip52f5g.kimi.page/" target="_blank">
  <img
    src="./assets/tech-orbit-ui.svg"
    alt="Interactive Tech Universe — Global Technology Stack Preview"
    width="100%"
  />
</a>


</div>

### Let's Connect

<a href="https://rajesh-kayal-portfolio.vercel.app/"><img src="https://img.shields.io/badge/PORTFOLIO-000000?style=flat-square&logo=vercel&logoColor=3B82F6&labelColor=0A0A0B" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/rajesh110/"><img src="https://img.shields.io/badge/LINKEDIN-000000?style=flat-square&logo=linkedin&logoColor=3B82F6&labelColor=0A0A0B" alt="LinkedIn" /></a>
<a href="https://leetcode.com/u/rajesh_8001/"><img src="https://img.shields.io/badge/LEETCODE-000000?style=flat-square&logo=leetcode&logoColor=3B82F6&labelColor=0A0A0B" alt="LeetCode" /></a>
<a href="https://x.com/RajeshKayal_"><img src="https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=3B82F6&labelColor=0A0A0B" alt="X" /></a>

</div>
<img src="assets/footer.svg" alt="" width="100%" />