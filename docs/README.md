# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation! This README provides an overview of our project delivery approach and quick links to key process docs.

## Summary of Project Management Processes

OctoAcme project management is built on **clear role definition and structured workflows** that ensure accountability and alignment across cross-functional teams. Our approach is grounded in principles of iterative delivery, clear ownership, transparency, and continuous improvement.

### Core Roles & Personas

The organization operates with clearly defined roles to prevent single points of failure:

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, write tests, and identify technical risks
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and strategic guidance

### Key Workflows

Our delivery approach follows a rhythmic cadence across five phases:

- **Initiation**: Validate business need, identify stakeholders, align on goals, and document the Project One-pager
- **Planning**: Break down work into shippable increments, define acceptance criteria, estimate scope, and plan releases
- **Execution & Tracking**: Run sprints/iterations with daily standups (15 min), weekly delivery syncs, and demos at milestone endpoints. Use GitHub Projects (Backlog → Ready → In Progress → In Review → QA → Done) with small PRs (≤400 lines), automated CI tests, and at least one approval before merging
- **Risk & Communication**: Maintain a risk register reviewed weekly, provide regular status reports using standardized templates, and follow clear three-level escalation paths (team → PM → Product Lead → Sponsor)
- **Release & Deployment**: Checklist-driven release planning, automated verification, smoke tests, and incident playbooks for rollback
- **Retrospective & Continuous Improvement**: Scheduled reviews after sprints/milestones/releases to capture learnings and drive actionable improvements with measured impact

### Communication Strategy

Multiple communication cadences ensure alignment at all levels:

- **Weekly PM-PdM syncs** keep product and delivery synchronized
- **Twice-weekly team standups** surface blockers early and maintain momentum
- **Monthly stakeholder updates** maintain visibility with leadership
- **Ad-hoc escalations** via three-level blocker escalation path
- **Risk Register reviews** at weekly syncs to prevent risks from compounding
- **Standardized status templates** covering progress, next steps, risks, and decisions needed

### Quality Assurance Practices

Quality is embedded throughout the delivery lifecycle, not siloed at the end:

- **Unit tests** for new logic, **integration tests** where applicable, and **end-to-end smoke tests** for critical flows
- **Automated CI** runs security scanning, linting, and test verification before any PR review
- **Definition of Done** documented upfront and enforced during sprint planning
- **Manual QA** validates feature acceptance when needed
- **Retrospectives** (45–75 minutes) capture learnings and convert them into tracked action items with owners, due dates, and measured impact

---

## Process Docs

Start with the **Project Management Overview** for a high-level introduction, then drill into the phase-specific docs based on where your project is in the lifecycle:

- [Project Management Overview](octoacme-project-management-overview.md) — Core principles, roles, lifecycle, and how to use these docs
- [Project Initiation Guide](octoacme-project-initiation.md) — Validate ideas, identify stakeholders, and create the Project One-pager
- [Project Planning](octoacme-project-planning.md) — Break down work, define acceptance criteria, estimate, and plan releases
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Run sprints, track progress, manage quality, and escalate blockers
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Maintain risk registers, communicate status, and escalate effectively
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Plan releases, deploy safely, and handle rollbacks
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive improvements
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed role descriptions and responsibilities

---

## Getting Started

**For new team members**: Start here to understand how OctoAcme runs projects, then read the **Project Management Overview** for deeper context.

**For project leads**: Use the phase-specific docs as checklists and guidance for your project (Initiation → Planning → Execution → Release → Retrospective).

**For continuous reference**: Bookmark this README as your home base for all current project management processes and updates. Keep the Project Charter updated in your project repo, and add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context.

---

*Last updated: May 2026*
