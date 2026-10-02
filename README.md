<div align="center">

# Niccolò Piazzi

**Full-stack developer in training**  
Backend systems · Web & mobile applications · Developer tooling · Edge/IoT

I build projects with explicit architecture, reproducible environments, automated quality gates, and evidence-based delivery.

[Portfolio](https://pianic2.github.io/its-react-portfolio-web/) ·
[LinkedIn](https://www.linkedin.com/in/niccolo-piazzi) ·
[GitHub](https://github.com/pianic2)

</div>

---

## What I work on

My main focus is designing and shipping full-stack systems that remain understandable as they grow.

I work mostly with **Django, Java/Spring Boot, React, React Native/Expo, PostgreSQL and Docker**, with a strong interest in contract-first APIs, reusable developer tooling, AI-assisted engineering, and edge systems.

I am currently studying Full Stack Development at **ITS Prodigi** while using personal, academic and real-world projects to push beyond isolated exercises into complete, reviewable systems.

---

## Selected work

### [Full-stack Product Template](https://github.com/pianic2/template-fullstack)

An agent-first product baseline with a **Django API, React web client and Expo mobile app** sharing one generated OpenAPI contract.

`Django 5.2` · `React 19` · `Expo 57` · `PostgreSQL` · `OpenAPI` · `Orval` · `Docker`

Highlights:
- generated API clients instead of duplicated handwritten contracts;
- separate browser-session and mobile-token authentication boundaries;
- reproducible bootstrap, CI, security checks and deployment guidance;
- repository-local agent workflows with explicit ownership and review rules.

### Portfolio Platform — [Frontend](https://github.com/pianic2/its-react-portfolio-web) · [Backend](https://github.com/pianic2/personal-django-portfolio-web)

A bilingual portfolio split into a **React frontend** and a **Django/Wagtail content backend**.

`React` · `TypeScript` · `Django` · `Wagtail` · `PostgreSQL` · `OAuth 2.1` · `MCP`

The backend owns editorial content, APIs and a least-privilege MCP content surface; the frontend consumes that content through a typed, tested UI with automated quality and accessibility checks.

**Live:** https://pianic2.github.io/its-react-portfolio-web/

### [React Native Components](https://github.com/pianic2/personal-library-react-native-components)

A reusable, pre-stable React Native UI package built around components, design tokens and theme primitives.

`React Native` · `Expo` · `TypeScript` · `npm` · `CI`

The package is validated against the Expo 57 / React Native 0.86 line and is designed to be consumed through a governed public API rather than copied between applications.

**Package:** https://www.npmjs.com/package/@personal-library/react-native-components

### [ProofChain](https://github.com/pianic2/its-java-proofchain)

A digital-evidence chain-of-custody backend built as a feature-first modular monolith.

`Java 25` · `Spring Boot 4` · `PostgreSQL` · `Flyway` · `Testcontainers` · `OpenAPI`

It models operators, cases, evidence and append-only custody events, with hash-linked histories, deterministic verification, Docker-based execution and a single Maven quality gate.

### [HomeEdge AI Platform](https://github.com/pianic2/homeedge-ai-platform)

An edge-first smart-home project centered on an **ESP32-C3 node**, sensor integration and explicit hardware/firmware boundaries.

`ESP32-C3` · `ESP-IDF` · `C` · `IoT` · `Edge`

The project is deliberately evidence-driven: implemented capabilities, target architecture and unvalidated ideas are kept distinct instead of being presented as equivalent maturity.

---

## Engineering approach

I prefer systems with clear boundaries and verifiable behavior over large amounts of loosely connected code.

- **Model first:** define domain boundaries, data ownership and contracts before adding complexity.
- **Contract first:** use OpenAPI and generated clients when multiple consumers share the same backend.
- **Reproducible by default:** pin runtimes, automate setup, and make local/CI behavior converge.
- **Evidence before claims:** tests, CI, review notes and explicit limitations are part of the delivery.
- **AI as an engineering tool:** use scoped agents for planning, implementation and review, while keeping human decisions and verification explicit.
- **Design for change:** favor modular monoliths, reusable packages and clear interfaces before introducing distributed complexity.

---

## Core stack

**Backend**  
`Python` · `Django` · `Django REST Framework` · `Wagtail` · `Java` · `Spring Boot` · `PHP` · `Laravel` · `Node.js`

**Frontend & mobile**  
`TypeScript` · `React` · `React Native` · `Expo` · `Vite`

**Data & delivery**  
`PostgreSQL` · `OpenAPI` · `Orval` · `Docker` · `GitHub Actions` · `Render` · `Linux`

**Embedded & edge**  
`ESP32` · `ESP-IDF` · `C`

---

## Currently

- refining [RamoVerde](https://github.com/pianic2/work-ramoverde), with emphasis on design quality, simplicity and client value;
- evolving the full-stack template as a reusable foundation for future products;
- building React Native / Expo applications around a shared component library and typed backend contracts;
- experimenting with structured AI-agent workflows that keep context, cost and review boundaries under control.

---

If you want the fastest overview of my work, start with **[template-fullstack](https://github.com/pianic2/template-fullstack)**, **[ProofChain](https://github.com/pianic2/its-java-proofchain)** and the **[live portfolio](https://pianic2.github.io/its-react-portfolio-web/)**.
