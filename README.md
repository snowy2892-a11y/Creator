# Creator

**An AI-powered platform for transforming textual worlds into structured knowledge and interactive 3D environments.**

## 1. Introduction

WorldForge AI is an experimental project that aims to transform novels, scripts, fictional settings, and other textual materials into structured and explorable virtual worlds.

The project combines natural language processing, knowledge graphs, AI-assisted scene generation, and interactive 3D technologies.

Its long-term goal is to build a system that can understand a fictional world, reconstruct its entities and relationships, generate explorable environments, and evolve the world based on user interactions.

## 2. Core Concept

The proposed workflow is:

```text
Text Input
    |
    v
Text Processing
    |
    v
AI Understanding
    |
    v
World Knowledge Graph
    |
    v
3D World Generation
    |
    v
NPCs and User Interaction
    |
    v
Interaction Analysis
    |
    v
World Evolution
```

## 3. Development Roadmap

### V0.1 — Text-to-World Knowledge

- Load TXT and Markdown files.
- Extract entities such as characters, locations, organizations, and events.
- Extract keywords and semantic tags.
- Identify relationships between entities.
- Export structured JSON data.

### V0.2 — Knowledge Graph and 3D Generation

- Build a structured world knowledge graph.
- Match entities with 3D assets.
- Generate basic explorable scenes.

### V0.3 — NPC and Interaction

- Create basic NPC profiles.
- Implement dialogue and interaction.
- Record user interaction events.

### V1.0 — Dynamic World Evolution

- Analyze interaction records.
- Generate world modification proposals.
- Maintain world consistency and version history.

## 4. Technology Stack

| Component | Planned Technology |
|---|---|
| Backend | Python, FastAPI |
| NLP | Transformers, PyTorch |
| Knowledge Graph | NetworkX, PostgreSQL |
| Frontend | React, TypeScript |
| 3D Engine | Three.js |
| 3D Assets | Blender, GLB |
| Version Control | Git, GitHub |

## 5. Project Status

**Current stage: Initial development**

The project is currently focused on building the text-processing and world-knowledge extraction pipeline.

## 6. Design Principles

- Preserve the original source material.
- Distinguish confirmed facts from AI-generated inferences.
- Keep the world knowledge structured and traceable.
- Allow users to review and approve important world changes.
- Build the system incrementally and modularly.

## 7. License

License to be determined.
