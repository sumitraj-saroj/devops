## 📅 DevOps Day 02: Software Development Lifecycle (SDLC)

To understand what a DevOps engineer automates, you first have to understand the foundational phases of the **Software Development Lifecycle (SDLC)**. The ultimate end goal of any SDLC model is to **deliver a high-quality product** to the customer efficiently.

### Core Phases of SDLC

[Image of software development lifecycle phases]

#### 📑 1. Planning & Defining

- Gathering customer requirements, features, and constraints for the product (e.g., building an e-commerce application).
- **Key Deliverable:** **SRS (Software Requirement Specification) Document**. This details all data points collected during the planning phase.

#### 🎨 2. Designing Phase

Before code is written, the architecture must be designed and vetted at two key levels:

- **HLD (High-Level Design):** Focuses on macro-architecture—system modules, service maps, databases, and general data flows.
- **LLD (Low-Level Design):** Focuses on micro-architecture—specific class logic, database schemas, object-oriented designs, and exact API boundaries.

#### 💻 3. Building Phase (Development)

- Developers (`Dev`) take the design blueprints and write the actual source code.
- The written code is pushed to a central repository like **Git** (Source Code Management).

#### 🧪 4. Testing Phase (Quality Engineering)

- Once built, the software is compiled and handed over to the **QE (Quality Engineering) / QA** team.
- They run strict functional, security, and performance test suites against the build to trace bugs.

#### 🚀 5. Deployment & Production

- The finalized, tested code moves out of testing environments directly onto the staging or **Production Server**.
- The application goes live via its domain (e.g., `example.com`), allowing end **Customers** to access it.

---

### ⚙️ The DevOps Engineer's Role

The traditional transitions between **Building ➔ Testing ➔ Deployment** were notoriously friction-heavy and manual.

A DevOps Engineer steps into this cycle to **automate and fasten the entire process**. By writing infrastructure-as-code, building CI/CD pipelines, and integrating tools, they make sure a developer’s code passes testing boundaries and deploys to production seamlessly with minimal human intervention.
