# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Project Sponsors / Business Owners

### Role Summary
Project Sponsors or Business Owners connect project delivery to organizational strategy. They provide direction and authority for major business decisions and help secure the support needed to achieve project outcomes.

### Responsibilities
- Confirm the business outcomes, strategic alignment, and expected value of the project
- Secure sponsorship, funding, and organizational support
- Make or escalate decisions about significant scope, priority, and resource trade-offs
- Remove organizational blockers that the delivery team cannot resolve
- Review progress and decide whether the project remains aligned with business needs

### Goals
- Realize the intended business outcomes and value
- Ensure timely decisions and adequate organizational support
- Keep significant risks and trade-offs visible to decision-makers

### Typical Communication
- Project kickoff and milestone reviews
- Steering or governance updates and escalation discussions
- Business case, decision, and outcome reviews

### Interaction with Existing Roles
- Align with the Product Manager on desired business outcomes, priorities, and changes to scope
- Partner with the Project Manager on governance, milestone status, escalations, and organizational dependencies
- Provide Developers with business context through the Product Manager rather than directing implementation work

---

## Engineering Leads / Technical Leads

### Role Summary
Engineering Leads guide technical delivery and help the team make sound engineering decisions. They coordinate technical work while enabling Developers to own implementation.

### Responsibilities
- Guide architecture, technical design, and engineering standards
- Validate technical feasibility, estimates, and delivery approaches
- Coordinate engineering work and technical dependencies across Developers or teams
- Identify technical risks and recommend mitigations
- Support code quality, maintainability, and production readiness

### Goals
- Deliver secure, reliable, maintainable technical solutions
- Make technical decisions and risks visible early
- Enable Developers to deliver effectively and consistently

### Typical Communication
- Technical design discussions and architecture decision records
- Engineering planning, estimation, and code reviews
- Risk, dependency, and readiness updates with project and product leads

### Interaction with Existing Roles
- Coach and coordinate Developers while leaving implementation ownership with the people doing the work
- Work with the Product Manager to assess technical options and explain the impact of product trade-offs
- Work with the Project Manager to align sequencing, estimates, dependencies, and technical status with the project plan

---

## Quality Engineers / Test Leads

### Role Summary
Quality Engineers or Test Leads coordinate quality practices and provide evidence about whether a solution meets its requirements and is ready for release.

### Responsibilities
- Define a test strategy covering relevant functional and non-functional risks
- Plan and coordinate exploratory, regression, and automated testing
- Clarify testability and quality expectations before and during implementation
- Track defects, quality risks, and validation results
- Provide a clear quality and release-readiness assessment

### Goals
- Detect important defects and quality risks early
- Provide reliable evidence that acceptance criteria are met
- Support a predictable, quality-focused release decision

### Typical Communication
- Test plans, test results, and defect reports
- Quality reviews during planning and execution
- Release-readiness updates and risk escalations

### Interaction with Existing Roles
- Collaborate with Developers to design tests, automate appropriate checks, and diagnose defects
- Work with the Product Manager to clarify acceptance criteria and agree what evidence demonstrates success
- Coordinate with the Project Manager and Engineering Lead on validation dependencies, defect impact, and readiness; report quality evidence to inform release decisions

---

## UX / Research Leads

### Role Summary
UX or Research Leads bring user research, design, accessibility, and usability expertise into project decisions so that delivered solutions address user needs.

### Responsibilities
- Plan and conduct user research and communicate findings
- Develop and validate user journeys, interaction designs, and prototypes
- Identify usability and accessibility needs and risks
- Incorporate user feedback into design recommendations
- Coordinate design inputs and validation with delivery milestones

### Goals
- Ensure solutions address evidenced user needs
- Improve usability and accessibility
- Reduce the risk of building features that are difficult to use or do not solve the intended problem

### Typical Communication
- Research findings, personas, journey maps, and design specifications
- Design reviews and usability or accessibility evaluations
- Planning discussions about research, design, and validation dependencies

### Interaction with Existing Roles
- Partner with the Product Manager to connect user evidence, product priorities, and success measures
- Work with Developers and the Engineering Lead to assess design feasibility and preserve intended user experience during implementation
- Coordinate research and design milestones with the Project Manager and surface dependencies or timing risks

---

## Operations / Release Owners

### Role Summary
Operations or Release Owners coordinate operational readiness and the transition of a solution into production and ongoing support.

### Responsibilities
- Confirm deployment environments, configuration, and operational prerequisites
- Coordinate release plans, deployment checks, and rollback procedures
- Ensure monitoring, alerting, support ownership, and runbooks are ready
- Identify operational risks and communicate incidents or release blockers
- Coordinate post-release verification and support handoff

### Goals
- Release changes safely and predictably
- Maintain service reliability and effective incident response
- Ensure teams can support and monitor the delivered solution

### Typical Communication
- Release checklists and deployment plans
- Operational readiness reviews and support handoff documentation
- Monitoring, incident, and post-release updates

### Interaction with Existing Roles
- Coordinate with Developers and the Engineering Lead on deployment requirements, technical readiness, and rollback plans
- Work with the Project Manager on release timing, dependencies, stakeholder communications, and escalation paths
- Align with the Product Manager on launch objectives and communicate post-release observations relevant to outcomes

---

## Role Collaboration
- A role describes accountability, not necessarily a separate person; in smaller teams, one person may hold multiple roles.
- When responsibilities are combined, teams should still name the accountable person for key decisions, handoffs, and escalations.
- Sponsors provide business direction, Product Managers own product priorities, Project Managers coordinate delivery, and engineering, quality, UX/research, and operations leads provide their respective expertise. These roles collaborate and surface trade-offs rather than silently transferring one another's accountabilities.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
