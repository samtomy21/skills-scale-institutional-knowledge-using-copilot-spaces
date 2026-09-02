# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Personas

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

## Extended Personas

## Stakeholder/Executive Sponsor

### Role Summary
Executive Sponsors provide business alignment, funding approval, and escalation authority. They represent business interests, make trade-off decisions at the executive level, and ensure projects align with organizational strategy.

### Responsibilities
- Provide business justification and strategic alignment for projects
- Approve project charter and major budget decisions
- Remove organizational blockers and escalations
- Represent the project at executive steering committees
- Validate project outcomes and business impact

### Goals
- Ensure projects deliver business value and ROI
- Maintain strategic alignment across portfolio
- Enable successful project delivery through organizational support

### Typical Communication
- Project kickoff and approval meetings
- Monthly or milestone-based executive updates
- Escalation resolution and decision forums
- Executive steering committee participation

### Interaction with Existing Roles
- Works with Project Managers to understand project status and remove blockers
- Partners with Product Managers to validate business value and outcomes
- Provides authority for resource decisions and trade-offs
- Ensures alignment with organizational strategy and priorities

---

## Technical Architect

### Role Summary
Technical Architects design and validate technical solutions to meet project requirements. They own system design decisions, identify technical risks, and ensure solutions align with organizational standards and long-term vision.

### Responsibilities
- Design technical solutions that meet functional and non-functional requirements
- Review architectural decisions and code designs for alignment with standards
- Identify and mitigate technical risks and dependencies
- Validate scalability, performance, and integration points
- Mentor developers on architectural patterns and best practices

### Goals
- Deliver architecturally sound, scalable solutions
- Reduce technical debt and rework
- Enable knowledge sharing and consistency across projects

### Typical Communication
- Technical design reviews with development team
- Architecture decision records (ADRs)
- Risk assessments during planning phase
- Integration planning with dependent systems

### Interaction with Existing Roles
- Works closely with Developers to validate implementation against design
- Partners with Product Managers to understand requirements before design
- Supports Project Managers by identifying technical dependencies and risks
- Collaborates with DevOps/Infrastructure Engineers on deployment architecture

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers ensure that projects meet security requirements, regulatory standards, and organizational policies. They assess risk, validate controls, and guide secure development practices.

### Responsibilities
- Review requirements for security and compliance implications
- Conduct security risk assessments during planning
- Validate that security controls are implemented in code and infrastructure
- Ensure compliance with industry standards and organizational policies
- Participate in incident response and post-incident reviews

### Goals
- Protect organizational and customer data
- Maintain regulatory compliance
- Enable secure development without slowing delivery

### Typical Communication
- Security reviews during planning and execution
- Risk assessments and mitigation plans
- Incident response coordination
- Security training and guidance

### Interaction with Existing Roles
- Partners with Project Managers on security timeline and risk management
- Advises Developers on secure coding practices
- Collaborates with QA on security testing strategies
- Works with DevOps on infrastructure security and monitoring

---

## UX/Design Lead

### Role Summary
UX/Design Leads define user experience, create design specifications, and validate usability. They ensure products are intuitive, accessible, and meet user needs throughout the development process.

### Responsibilities
- Conduct user research and define user personas and journeys
- Create wireframes, prototypes, and design specifications
- Validate usability through testing and feedback
- Ensure accessibility standards and design consistency
- Collaborate on design decisions and trade-offs

### Goals
- Deliver intuitive, user-friendly products
- Reduce usability issues and rework
- Ensure accessibility and inclusive design

### Typical Communication
- Design reviews and critique sessions
- User research findings and insights
- Design specifications and prototypes
- Usability testing results and recommendations

### Interaction with Existing Roles
- Partners with Product Managers to understand user needs and requirements
- Collaborates with Developers on design feasibility and implementation
- Works with QA on usability and accessibility testing
- Supports Project Managers by identifying design dependencies and timeline impacts

---

## DevOps/Infrastructure Engineer

### Role Summary
DevOps/Infrastructure Engineers manage deployment infrastructure, monitoring, and operational reliability. They enable teams to deploy, scale, and operate applications reliably and securely.

### Responsibilities
- Design and maintain deployment pipelines and infrastructure
- Manage cloud resources, databases, and infrastructure as code
- Implement monitoring, logging, and alerting systems
- Ensure security, performance, and cost optimization of infrastructure
- Support incident response and operational troubleshooting

### Goals
- Enable rapid, reliable deployments
- Maintain high availability and system performance
- Reduce operational overhead and infrastructure costs

### Typical Communication
- Infrastructure planning and architecture reviews
- Deployment planning and execution
- Monitoring dashboards and performance metrics
- Incident response and post-mortem reviews

### Interaction with Existing Roles
- Collaborates with Technical Architects on infrastructure design
- Works with Developers on deployment requirements and CI/CD pipelines
- Partners with Project Managers on deployment schedules and risk management
- Coordinates with Security/Compliance Officers on infrastructure security

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters/Agile Coaches facilitate agile ceremonies, remove impediments, and coach teams on agile practices. They enable team effectiveness and continuous improvement through agile methodologies.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Remove impediments and blockers to team progress
- Coach team members on agile practices and mindsets
- Track team metrics (velocity, burndown, cycle time)
- Foster psychological safety and continuous improvement culture

### Goals
- Maximize team productivity and delivery predictability
- Enable self-organizing, high-performing teams
- Drive continuous process improvement

### Typical Communication
- Daily standups and ceremony facilitation
- Velocity and burndown tracking
- Retrospective action items and follow-up
- One-on-one coaching and guidance

### Interaction with Existing Roles
- Supports Project Managers with ceremony facilitation and team coaching
- Works with Developers to remove blockers and optimize workflow
- Collaborates with Product Managers on backlog prioritization and planning
- Coaches all roles on agile principles and practices

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Core personas (Developers, Product Managers, Project Managers) are involved in all projects.
- Extended personas are engaged based on project-specific needs and organizational structure.
