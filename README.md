# Argo CD — Learning Guide

This repository is a structured learning guide for Argo CD. It contains notes, walkthroughs, and examples grouped by topic to help you learn Argo CD concepts, setup, and advanced usage patterns such as ApplicationSets and App-of-Apps.

## Repository Purpose

- **Audience**: engineers and operators learning Argo CD and GitOps patterns.
- **Contents**: curated lessons, configuration examples, and explanations covering installation, application definitions, sync strategies, repositories, and advanced features.

## Top-level Structure

The repository is organized by topic folders. Key folders and their purpose:

- `1- Core Concepts/`: Introductory materials and architecture overviews.
- `2- Setting-Up Argo CD/`: Install and CLI instructions.
- `3- Application/`: How to define Applications, tool detection, Helm, Kustomize, and multi-source setups.
- `4- Projects/`: Why projects matter and how to create/manage them.
- `5- Repositories/`: Working with Git/Helm/private repos and credentials.
- `6- Sync Policies and Options/`: Automated sync, pruning, self-healing, and other sync options.
- `7- Tracking Stragtegies/`: Strategies for tracking upstream changes.
- `8- Diffing Customiztion/`: Custom diffing behavior and examples.
- `9- Sync Phases and Waves/`: Hooks, phases, and sync wave examples.
- `10- Remote Kubernetes Clusters/`: How to define and use remote clusters with Argo CD.
- `11- ApplicatioSet/`: ApplicationSet concepts and generators (including Pull Request generator).
- `12- App of Apps/`: App-of-Apps pattern and examples.

Each numbered folder includes subpages covering focused topics (for example, `1- Core Concepts/1- intro to Agro CD`).

## How to Use This Repo

- **Browse**: Open the repository in your editor (VS Code recommended) and navigate the numbered folders to follow a learning path.
- **Search**: Use your editor search to find keywords like `ApplicationSet`, `Helm`, `sync`, or `projects`.
- **Examples**: Look inside section folders for small example manifests and commands you can adapt to test in a cluster.

## Quick Commands

View the README and list files:

```bash
ls -la
sed -n '1,120p' README.md
```

Commit this README locally:

```bash
git add README.md
git commit -m "docs: add repository README"
git push
```

## Contributing

- Add new notes or examples as new numbered subfolders or files inside the relevant topic folder.
- Keep file names readable and prefixed with a short number where ordering matters (the repo already uses a numbered structure).
- If you want help restructuring or adding content, open an issue or create a draft PR.

## Next Steps (suggested learning path)

1. Read `1- Core Concepts/1- intro to Agro CD` to get oriented.
2. Follow `2- Setting-Up Argo CD/1- Installation Options` to install a local Argo CD instance.
3. Explore `3- Application/` to learn how to define and sync apps.

---

If you'd like, I can expand this README with badges, a short glossary, or direct links to specific files and examples. Tell me what you'd like to see next.
