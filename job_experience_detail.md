## Detailed Experience

### Trabian — Senior Platform Engineer
*December 2025 – Present*

Trabian is a software consultancy specializing in financial technology for credit unions and community banks. I build and maintain the cloud platforms that power financial integrations — Plaid connectivity, core banking adapters, payment processing, and account aggregation — for multiple financial institution clients.

**Platform Architecture**
- Multi-tenant API platforms serving financial institution clients, each with isolated data, credentials, and configuration
- Plaid integration services covering the full lifecycle: Link token creation, public token exchange, account aggregation, transaction sync, processor token management, identity verification, and webhook handling
- Core banking adapters for Q2 (Fiserv, SymXchange, jXchange) enabling real-time account queries, transaction posting, and member management
- Temporal workflow orchestration for durable, multi-step financial operations: daily ETL pipelines extracting data from Plaid and core banking systems, reporting aggregation across partners, and data warehouse delivery via S3/Snowpipe. Workflows use encrypted payloads (codec server), configurable retry policies, and structured activity logging for auditability

**Infrastructure & Security**
- Infrastructure as code with Pulumi (TypeScript) deploying across AWS and Azure: ECS Fargate services, Azure Functions, MongoDB Atlas, PostgreSQL, MSSQL, CDN/WAF, managed secrets
- Envelope encryption pattern: AES-256-GCM data encryption keys wrapped by RSA-2048 key encryption keys, with HMAC blind indexing for searchable encrypted fields
- OAuth 2.0 / OIDC authentication via Zitadel with scope-based authorization (root vs partner access tiers), JWT validation with JWKS rotation
- Network security: VPC peering, private subnets, WAF rules, TLS everywhere, IP allowlisting for core banking connections

**Compliance & Specification**
- Comprehensive specification vaults (MkDocs Material sites) with 130+ testable requirements in Given/When/Then format
- Traceability matrices mapping system capabilities to FFIEC, SOC 2 Type II, GLBA/Reg P, and PCI-DSS v4.0 regulatory controls
- Risk assessments, evidence inventories, change control logs, and production readiness checklists maintained as living documents
- Status badges on every requirement (Implemented, Partial, Planned, Gap) with direct code traceability links

**AI-Augmented Development**
- Spec-first development workflow: specification diffs written and reviewed before code, with concurrent spec and code PRs
- CI-triggered drift detection: Claude Code agents on GitHub Actions review PRs against the spec vault, flagging when code diverges from documented behavior
- Git-backed issue tracking (beads) with dependency graphs, blocking relationships, and handoff protocols enabling multi-session AI agent work
- DuckDB analytics on development data: velocity tracking, bug ratio trends, label entropy analysis, and automated delivery health reporting
- Integration with Linear for sprint planning: automated story point estimation from spec requirements using a powers-of-two scale calibrated to human work hours
- Multi-agent orchestration: parallel AI sessions working independent tasks in isolated git worktrees with structured handoff documents for context continuity

---

### Writing Sabbatical
*2021 – 2025*

Independent study in physics, mathematics, and machine learning.

---

### Emory Solutions — Contract Software Engineer
*December 2020 – January 2021*

Short consulting engagement analyzing a legacy industrial system with accumulated technical debt. Built a Django-based data-reporting application that surfaced operational insights previously buried in the system, reducing manual data-gathering effort for business stakeholders.

- Reverse-engineered complex business logic spread across multiple legacy subsystems
- Built a reporting dashboard with Django REST Framework + Vue.js frontend
- Deployed on AWS with Docker/Kubernetes

---

### Qbox — Contract Software Engineer
*February 2020 – September 2020*

Qbox operated a managed Elasticsearch hosting platform. I migrated the legacy infrastructure to a new cloud environment and built the CI/CD system for their next-generation microservice architecture.

- Terraform-based infrastructure migration with improved failover and maintainability
- Built CI/CD pipeline with TravisCI for automated testing and deployment of microservices
- Docker container orchestration on Kubernetes (AWS EKS)
- Python/Flask API services with Vue.js management console

---

### Lofty Labs — Software Engineer
*May 2015 – March 2019 (with gaps)*

Lofty Labs is a software consultancy in Northwest Arkansas. I worked on several client projects over four years, with the largest being a machine-learning-as-a-service platform.

**ML Platform (Primary Project)**
- Built core components of a multi-tenant ML pipeline: data ingestion, feature engineering, model training, and prediction serving
- Managed AWS deployments across multiple environments (dev, staging, production) with Terraform and Ansible
- Docker/Kubernetes orchestration for training jobs and API services
- Django REST backend with Celery task queues for asynchronous ML workloads

**Other Projects**
- Retail data ingestion pipeline for a retail analytics firm: automated weekly ETL from multiple retail data providers, normalizing disparate formats into a unified analytical schema
- Legal discovery system: large-scale email corpus ingestion, Elasticsearch indexing, and search/flagging interface for legal review teams
- Cloud migrations and DevOps improvements across multiple client engagements

---

### StackSearch — Co-Founder & CTO
*July 2012 – February 2014*

Co-founded a venture-backed startup building search-powered product discovery for e-commerce sites. Attended the Ark Challenge accelerator in Huntsville, AL. Built the core search technology (Elasticsearch-based product indexing with relevance tuning) and recruited the early engineering team.

---

### High Impact Analytics — Software Engineer
*April 2010 – August 2012*

Built a full-stack database application that automated weekly retail data ingestion and report generation for an independent retail analyst. The system enabled the client to scale from manually processing data for a handful of retail clients to serving dozens, with automated data pipelines, templated reports, and a web dashboard.

---

### Earlier Roles

**@ddress** (2011–2012): Junior full-stack developer on a geo-social media platform. Built backend services and frontend components on Google App Engine with Django. The platform featured sophisticated geo-hash search capabilities for location-based community groups.

**Mill Creek Software** (2008–2009): Trained as a junior developer with Microsoft's stack. Client projects included business management software for a summer camp company and a construction blasting company. First exposure to Python and Django alongside the C#.NET primary stack.
