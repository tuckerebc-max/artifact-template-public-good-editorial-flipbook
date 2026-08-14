---
name: artifact-template-public-good-editorial-flipbook
description: "Create a presentation using the Public Good Editorial Flipbook template and its retained reference file. Use when the user selects this template, names Public Good Editorial Flipbook, or explicitly invokes $artifact-template-public-good-editorial-flipbook. Create square, hopeful editorial flipbooks for education research, public investment, and policy announcements using tactile collage imagery, strong serif-led hierarchy, evidence-grounded sequencing, human community symbolism, and a clear invitation to share and act."
---

# Public Good Editorial Flipbook

Create a presentation from this template. Keep the reference file unchanged.

## Workflow

1. Read `artifact-template.json` and resolve its paths relative to this skill directory.
2. Load [@presentations](plugin://presentations@openai-primary-runtime) and invoke its reference/template workflow with the retained file.
3. Treat the user's prompt and available sources as the content input. Do not invent facts merely to fill a template slot.
4. Clone or import the reference instead of replacing its visual system with generic defaults.
5. Render and verify the finished presentation, then return the final artifact.

## Fidelity

Preserve source slides, layouts, masters, typography, geometry, images, charts, tables, and recurring slide chrome.

User instructions control requested content and explicit deviations. The retained reference controls layout and formatting where the user has not requested a change.
