<p align="center">
  <img src="./assets/banner.svg" alt="LXY — frontend-focused full-stack developer" width="100%" />
</p>

# LXY

**Frontend-focused full-stack developer building AI applications, interactive web systems, and practical products with React and TypeScript.**

I care about readable interfaces, maintainable systems, and the less visible work that makes software dependable: testing, accessibility, documentation, and careful review.

[Explore my portfolio](https://lxy-lab.vercel.app) · [View my open-source contributions](#open-source) · [Email me](mailto:zerolxy612@gmail.com)

## Selected work

### [Xiangyu's AI Lab](https://lxy-lab.vercel.app)

An explorable pixel-art portfolio that presents AI application engineering and product work through a walkable research lab set in a future Hong Kong.

- React 19 and TypeScript own the readable content, navigation, accessibility, and contact surfaces.
- Phaser 3 owns movement, collision, proximity, and the spatial world; a typed event bridge connects both layers.
- Includes a content-first mobile experience, reduced-motion support, tests, and a documented asset pipeline.

[Live experience](https://lxy-lab.vercel.app) · [Source and engineering notes](https://github.com/zerolxy612/lxy-lab)

<a href="https://lxy-lab.vercel.app">
  <img src="https://raw.githubusercontent.com/zerolxy612/lxy-lab/main/public/assets/brand/og-xiangyu-ai-lab-v1.png" alt="Xiangyu's AI Lab — an explorable pixel-art portfolio" width="100%" />
</a>

### [DramaForge](https://drama-forge-web.vercel.app)

A Web3 and AIGC short-drama prototype where viewers advance branching stories and register reusable creative assets on Solana.

- Next.js 14, TypeScript, Tailwind CSS, and Zustand power the product interface.
- Rust and Anchor programs model dramas, story nodes, asset registration, and token rewards.
- The repository includes a system design document, local validator workflow, and contract-level project structure.

[Live prototype](https://drama-forge-web.vercel.app) · [Source and architecture](https://github.com/zerolxy612/lexihk-contract-demo)

## Open source

### [enisdenjo/graphql-ws — operation ID compatibility fix](https://github.com/enisdenjo/graphql-ws/pull/695)

Fixed WebSocket server subscription bookkeeping that rejected valid operation IDs such as `__proto__`, `constructor`, and `toString` as duplicates.

- Used null-prototype objects for the per-connection subscription registry during initialization and cleanup.
- Added protocol-level regression tests covering all three special operation IDs.
- Passed format, type, CodeQL, and the Node.js 20/22/24 × GraphQL 15/16/17 test matrix.
- Received maintainer approval and was merged into `master`.

[Read the merged pull request](https://github.com/enisdenjo/graphql-ws/pull/695) · [View the merge commit](https://github.com/enisdenjo/graphql-ws/commit/93c8ebf2096e31b5b6b06037d288732c00aa69a6)

### [Tencent/teamai-cli — prompt summary privacy fix](https://github.com/Tencent/teamai-cli/pull/685)

Fixed a privacy-sensitive persistence bug where raw prompt content could reach local logs without redaction.

- Applied redaction before summary truncation and persistence.
- Added regression coverage and end-to-end verification across multiple providers and agent event formats.
- Updated the English and Chinese documentation to describe persisted data accurately.
- Passed the project's full test and build checks, received maintainer approval, and shipped in [`v0.25.0-beta.5`](https://github.com/Tencent/teamai-cli/releases/tag/v0.25.0-beta.5).

[Read the merged pull request](https://github.com/Tencent/teamai-cli/pull/685) · [View the release](https://github.com/Tencent/teamai-cli/releases/tag/v0.25.0-beta.5)

## Engineering focus

- **Product frontend:** React, Next.js, TypeScript, responsive interfaces, and accessible interaction design
- **Interactive systems:** Phaser, state and event boundaries, browser audio, and spatial interfaces
- **Full-stack products:** Node.js, APIs, authentication, deployment, and Web3 integration
- **Quality and collaboration:** Vitest, end-to-end verification, debugging, code review, and technical documentation

## Current direction

I am building production-minded web products, exploring reliable AI application interfaces, and contributing tested fixes to active open-source projects.

## Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/zerolxy612/zerolxy612/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/zerolxy612/zerolxy612/output/snake-light.svg" />
  <img alt="GitHub contribution history" src="https://raw.githubusercontent.com/zerolxy612/zerolxy612/output/snake-dark.svg" width="100%" />
</picture>

## Contact

Interested in frontend engineering, full-stack product work, and open-source collaboration.

[zerolxy612@gmail.com](mailto:zerolxy612@gmail.com) · [GitHub](https://github.com/zerolxy612)
