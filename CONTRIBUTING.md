# Contributing to GYESME

Thank you for your interest in contributing to GYESME! We welcome contributions that improve modularity, restore optional functionality, or enhance the user experience while preserving a minimal default environment.

This guide explains how to get started, submit contributions, and interact with the project in a way that keeps GYESME maintainable and consistent.

---

## Getting Started

1. **Fork the repository**  
   Use the "Fork" button on GitHub to create a personal copy of the repository.

2. **Clone your fork locally**  
   ```
   git clone git@github.com:<your-username>/GYESME.git
   cd GYESME
   ```

3. **Create a new branch for your work**  
   Branches should be descriptive of the feature or fix:  
   ```
   git checkout -b feature/<feature-name>
   git checkout -b fix/<bug-name>
   ```

4. **Install any dependencies**  
   Follow the instructions in the README or project documentation for building/testing modules.

---

## Workflow

1. Pick an issue from the [Project Board](Projects) → **Backlog** column.  
2. Move the issue to **To Do** when you start planning your work.  
3. Move the issue to **In Progress** once you begin coding or documenting.  
4. Submit a **Pull Request (PR)** when your changes are ready for review.  
5. Move the card to **Review / PR** column for peer review.  
6. After approval and merging, move the card to **Done**.

---

## Pull Request Guidelines

- PRs should be submitted to the `main` branch of your fork and target `main` in the main repository.  
- Each PR should focus on **one logical change** (feature, bug fix, or documentation improvement).  
- Include a **clear title** and **description** explaining what the PR does and why.  
- Reference the issue your PR addresses using `#<issue-number>` in the description.  
- Ensure **modular behavior**: features should be opt-in where possible, and disabling a feature should not break the default experience.  
- Follow the existing **code style and formatting**.

---

## Labels Guide

Use the following labels when creating issues or PRs:

| Label | Purpose | Suggested Use |
|-------|---------|---------------|
| `good first issue` | Beginner-friendly tasks | Small tasks suitable for first-time contributors |
| `enhancement` | Optional feature or module | Any improvement or addition to existing functionality |
| `modular-feature` | Modular, opt-in feature | Features that can be enabled or disabled without affecting the default experience |
| `testing` | Verification or automated tests | Testing, QA, or bug verification work |
| `research` | Documentation or investigation | Tasks involving analysis, documentation, or exploration |
| `UX` | User experience enhancements | Interface improvements, workflow refinements |

> Use multiple labels if your contribution spans categories (e.g., `enhancement` + `UX`).

---

## Coding Standards

- Follow GNOME and GTK coding conventions where applicable.  
- Write **clear, maintainable code**; prioritize readability over cleverness.  
- Document new features, modules, and configuration options thoroughly.  
- Respect modularity: **opt-in features should not interfere with default behavior**.

---

## Testing

- Verify that all enabled and disabled features behave correctly.  
- Ensure compatibility across supported distributions and init systems.  
- Include test cases for new features where possible.

---

## Reporting Issues

- Use the **Issues** tab to report bugs, propose features, or request documentation improvements.  
- Provide a **detailed description** including steps to reproduce (for bugs) or rationale (for features).  
- Assign relevant **labels** and **milestone** if applicable.

---

## Communication

- Use **Issues** and **Pull Requests** for asynchronous discussion.  
- Participate in **Project Board planning** and review sessions when possible.  
- Respectfully discuss design decisions and feature trade-offs.

---

## License

All contributions are licensed under **GPL-3.0**, in line with GYESME’s license.
