# Polysophic

Polysophic is a self-hostable, repository-driven documentation platform for composing one or more Git-backed content sources into a configured, branded documentation experience.

A Polysophic project can combine repositories with different responsibilities—for example, commercial documentation in one repository and technical documentation in another—while selecting specific branches, directories, and source subsets from each.

```text
Polysophic Instance
    ↓
Projects
    ↓
Repository Connections
    ↓
Repository Sources
    ↓
Collections / Content Model
    ↓
Documentation Configuration
    ↓
Branded Documentation Experience
    ↓
Publication
```

At a high level, Polysophic is designed around:

- multiple repository sources;
- Git-backed content;
- project-level configuration;
- collections and filtering;
- configurable navigation;
- a consistent documentation UI;
- white labeling;
- Markdown and Nuxt Content-based rendering;
- self-hosting; and
- publishing.

Source repositories remain independently owned and versioned. Polysophic connects, reconciles, configures, renders, and publishes their content without requiring that content to be moved into Polysophic-owned repositories.
