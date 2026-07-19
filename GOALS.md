# Navokoj Strategic Goal Board

Navokoj turns difficult operational constraints into verified decisions before a customer-defined deadline. These goals connect the product, runtime, evidence, and commercial workflow.

## Strategy Planning

### Vision

Make difficult operational decisions executable through one constraint runtime: submit the model, set the deadline, and receive the best verified decision available.

### Core Values

| Core Value | What It Means at Navokoj |
|---|---|
| **Useful before impressive** | Customer outcomes and working integrations matter more than abstract capability alone. |
| **Verified by default** | Returned decisions should expose feasibility, residual violations, provenance, and runtime evidence. |
| **Anytime and honest** | The runtime returns its best available result by the deadline and clearly distinguishes solved, feasible, partial, timeout, and unknown states. |
| **Engineering leverage** | Shared routing, repair, verification, billing, and deployment primitives should improve every workload. |

### Focus Areas

| Focus Area | Strategic Question |
|---|---|
| **Customer decisions** | Which expensive scheduling, allocation, verification, or policy decision can Navokoj improve first? |
| **Runtime quality** | Can the system produce a useful, inspectable result within the customer’s time and resource budget? |
| **Trust and operations** | Can a customer understand what happened, verify the result, and reconcile the cost? |
| **Distribution and adoption** | Can a developer discover, access, test, and integrate Navokoj without a long procurement cycle? |

### Measures of Progress

| Measure | Signal of Progress |
|---|---|
| Customer value | Verified improvement against a real incumbent workflow |
| Runtime quality | Feasible-result rate, time-to-first-result, deadline success, and verification coverage |
| Product trust | Reconciled billing, stable API contracts, reproducible artifacts, and clear failure states |
| Adoption | First successful solve, repeat usage, API credit consumption, pilots, and retained workloads |

### Tactics

| Tactic | Action |
|---|---|
| Start with one painful workflow | Work directly with a scheduling, allocation, or verification operator and model their actual constraints. |
| Ship the smallest useful integration | Prefer a narrow adapter, verified output, and export path over a broad unfinished platform feature. |
| Use evidence in the product loop | Attach inputs, configuration, runtime, assignment, verification, and billing metadata to important results. |
| Keep the payment path explicit | Use GitHub Sponsors as the developer access rail, provision credits clearly, and show the authoritative usage record. |
| Close the feedback loop | Convert customer failures and residual violations into routing, diagnostics, repair, and model-adapter improvements. |

### Decision Filter

Before starting a major initiative, answer:

1. Which customer decision does this improve?
2. Which measurable result will change?
3. How will the result be verified?
4. Does it improve adoption, reliability, economics, or reusable runtime capability?

Work that cannot answer these questions belongs in research exploration, not the committed product plan.

## Stakeholder Analysis

Navokoj’s execution depends on matching communication and involvement to each stakeholder’s influence and interest.

### Keep Satisfied

High influence, variable day-to-day interest. Keep these stakeholders confident that Navokoj is commercially controlled and technically dependable.

| Stakeholder | What They Need | Engagement |
|---|---|---|
| Executive sponsors and investors | Clear market wedge, evidence, risk control, and progress toward revenue | Short operating updates, milestone evidence, and explicit decisions needed |
| Enterprise buyers and procurement leaders | Security, deployment, pricing, support, and contractual clarity | Targeted architecture, security, billing, and deployment materials |
| Design-partner executives | Measurable operational improvement without disruption | Pilot scorecards, acceptance criteria, and outcome reviews |

### Key Players

High influence and high interest. Work with these stakeholders continuously because they shape product direction and adoption.

| Stakeholder | What They Need | Engagement |
|---|---|---|
| Operations leads | Better schedules, allocations, or decisions within real deadlines | Discovery calls, representative workloads, and weekly pilot feedback |
| Technical evaluators | Reliable APIs, predictable limits, reproducible results, and integration support | Hands-on evaluation, verifier output, API examples, and issue tracking |
| Platform and infrastructure teams | Stable deployment, observability, capacity controls, and secure data boundaries | Architecture reviews, runbooks, incident paths, and deployment tests |

### Monitor

Lower influence and lower current interest. Track signals without over-investing in bespoke engagement.

| Stakeholder | What to Watch | Engagement |
|---|---|---|
| Broader developer audience | Documentation usage, first solves, repeat requests, and support questions | Public docs, examples, changelog, and lightweight feedback channels |
| Research and open-source community | Reproducibility, benchmark interest, and technical discussion | Public evidence, NitroSAT releases, papers, and issue responses |
| Adjacent vendors and ecosystem observers | Competitive movement and possible integration opportunities | Periodic market review and selective technical conversations |

### Keep Informed

Lower influence but meaningful interest. Provide enough context to support trust, referrals, and future adoption.

| Stakeholder | What They Need | Engagement |
|---|---|---|
| Developers and technical followers | A clear way to understand, try, and evaluate Navokoj | API docs, examples, evidence links, and transparent result semantics |
| Hiring candidates and collaborators | Product direction, engineering standards, and meaningful work | Careers page, architecture overview, and project updates |
| Academic and technical readers | Access to research context and reproducible artifacts | Research links, benchmark manifests, and open-source material |

### Stakeholder Operating Rules

1. Keep key players close to the actual workload, not only to presentations.
2. Give high-influence stakeholders evidence tied to decisions, risks, and outcomes.
3. Turn repeated questions from informed audiences into better documentation.
4. Reclassify stakeholders when a pilot, procurement process, or partnership changes their influence or interest.

## Navokoj Mandala

Use this as a decomposition tool: keep **Navokoj** at the center, then expand one surrounding dimension into eight actionable work items before committing to implementation.

### Central Theme

**Navokoj: an anytime constraint runtime for verified decisions before the deadline.**

### Eight Dimensions

| Dimension | Eight Work Items |
|---|---|
| **Customer problems** | Scheduling, workforce rostering, logistics, allocation, policy enforcement, cloud placement, configuration, agent execution |
| **Model inputs** | CNF, WCNF, Boolean expressions, native XOR, finite-domain models, schedules, incremental updates, domain adapters |
| **Execution engines** | CPU, SUTRA, NitroSAT V2, NitroSAT V3 streaming, GPU, Q-State, repair, exact or external handoff |
| **Decision quality** | Hard feasibility, soft objective, residual violations, diagnostics, anytime progress, timeout behavior, assignment stability, independent verification |
| **Evidence** | Input hash, solver commit, configuration, hardware, raw output, verifier result, runtime record, billing record |
| **Operations** | API limits, routing, queueing, observability, rate limits, deployment modes, incident response, capacity planning |
| **Commercial system** | GitHub Sponsors access, credit provisioning, usage pricing, wallet accounting, pilots, enterprise contracts, support, expansion |
| **Technical moat** | Geometry-aware routing, continuous dynamics, structural repair, streaming scale, native constraint handling, verification, accumulated workload knowledge, reusable integrations |

### Mandala Review Questions

For any new initiative, identify:

1. Which central customer decision it improves.
2. Which of the eight dimensions it changes.
3. Which neighboring dimensions must change with it.
4. What concrete result proves the work is complete.

## Navokoj Sailboat Retrospective

Use this retrospective to discuss the current state of the product and team without collapsing every issue into a status label.

### Destination

Where Navokoj is trying to go:

- Ship a dependable anytime constraint runtime for production workloads.
- Launch repeatable customer workflows, beginning with scheduling and allocation.
- Convert developer access into recurring API usage, paid pilots, and enterprise deployments.
- Make every important result verifiable, inspectable, and financially reconcilable.

### Wind: What Is Pushing Navokoj Forward

- Strong solver portfolio spanning CPU, GPU, finite-domain, repair, and streaming execution.
- SUTRA and NitroSAT provide distinct low-latency and large-scale operating regimes.
- Native verification, evidence artifacts, and explicit timeout semantics build trust.
- Public documentation, benchmarks, open-source NitroSAT, and the evidence ledger create technical reach.
- GitHub Sponsors provides a low-friction developer access and credit workflow.
- Customer interest in expensive scheduling, allocation, verification, and policy decisions.

### Anchors: What Is Slowing Navokoj Down

- Too many possible markets competing for attention before one wedge is fully developed.
- Customer discovery and real workload deployment lagging behind engineering output.
- Billing, tier limits, routing, and deployment contracts requiring continual alignment.
- Inconsistent historical documentation and benchmark provenance across solver generations.
- Founder bandwidth and the risk of adding infrastructure faster than it can be operated.
- Integration work that remains specific to each customer instead of becoming reusable adapters.

### Reefs: Hidden Risks Ahead

- Overpromising universal solver superiority instead of defining the workloads where Navokoj wins.
- Returning heuristic or partial results without clearly distinguishing them from exact proofs.
- A customer receiving a feasible schedule that is difficult to explain or export into existing systems.
- Payment claims, wallet balances, or usage ledgers diverging from actual compute consumption.
- Sensitive customer models, API keys, or deployment artifacts crossing the wrong trust boundary.
- Single-person dependency across solver research, infrastructure, customer support, and commercial operations.
- Public evidence becoming too broad or complex for a buyer to understand quickly.

### Sun: Wins Worth Celebrating

- Navokoj has become a product surface rather than only a research solver.
- The runtime spans interactive CNF, weighted models, finite-domain workloads, GPU execution, repair, and streaming scale.
- Public evidence includes reproducibility material, verification records, and large benchmark campaigns.
- NitroSAT gives the ecosystem an open-source adoption and research layer.
- The API has explicit billing, routing, capacity, and result semantics.
- The product story has moved from “a solver” toward “verified constraint decisions before the deadline.”

### To-Do: Actions After the Discussion

| Priority | Action | Completion Signal |
|---|---|---|
| P0 | Select one initial customer wedge and name the buyer | One written ideal-customer profile and target list |
| P0 | Run a real workload through the API with the customer | Verified before/after result and acceptance criteria |
| P0 | Reconcile production billing end to end | Request, preauthorization, charge, wallet debit, and ledger agree |
| P1 | Package one short customer-facing evidence report | Model, deadline, result, verification, and business outcome in one artifact |
| P1 | Define the supported result contract | Clear semantics for solved, feasible, partial, timeout, unknown, and error |
| P1 | Reduce operational single points of failure | Runbook, deployment path, access ownership, and incident procedure |
| P2 | Convert repeated integration work into adapters | Reusable input, output, verification, and export modules |
| P2 | Review public claims against the evidence ledger | Every headline claim points to an inspectable artifact or is removed |

## Navokoj Team Culture Guide

### Introduction

Navokoj is built by a small, cross-functional team working across mathematical research, systems engineering, product design, infrastructure, and customer deployment. The team should stay curious and ambitious while making work understandable, testable, and useful to someone outside the lab.

### What We Value

| Value | Practice |
|---|---|
| **Be self-driven** | Take ownership of a problem from definition through implementation, verification, documentation, and handoff. |
| **Embrace candidness** | Surface weak results, unclear requirements, operational risks, and uncomfortable customer feedback early. |
| **Do, observe, learn** | Prefer a small executed experiment or customer test over extended speculation. Record what happened. |
| **Stay grounded** | Connect technical decisions to customer outcomes, operating cost, reliability, and the deadline the user cares about. |

### Team Evolution

Navokoj should evolve through visible stages rather than invisible accumulation of complexity:

1. Research mechanism
2. Reproducible experiment
3. Reliable runtime path
4. Customer-shaped integration
5. Verified production workflow
6. Repeatable commercial product

At each stage, preserve the evidence and lessons from the previous stage. Do not promote an experimental capability into a product promise without a clear contract and verification path.

### Our Platforms and Sections

| Area | Responsibility |
|---|---|
| **Constraint runtime** | Model intake, routing, deadlines, result semantics, and verification |
| **Solver engines** | CPU, GPU, SUTRA, NitroSAT, Q-State, repair, and exact handoff paths |
| **Scheduling and domain adapters** | Translate customer data into constraints and verified business outputs |
| **Evidence system** | Preserve inputs, configuration, assignments, proofs, artifacts, and provenance |
| **Billing and access** | Sponsors credits, API keys, wallet accounting, limits, and settlement |
| **Deployment and security** | SaaS, private, air-gapped, secrets, licenses, observability, and updates |
| **Product and documentation** | API contract, examples, pricing, use cases, and customer-facing language |
| **Research and open source** | Public NitroSAT, papers, benchmarks, and technical community work |
| **Customer deployment** | Workload discovery, pilot execution, integration, training, and feedback |

### Learning and Collaboration

| Practice | Expected Behavior |
|---|---|
| **Shared knowledge and team sensemaking** | Write down decisions, assumptions, failure modes, and reusable patterns instead of keeping them in private context. |
| **Research and hybrid culture** | Let mathematical ideas meet software experiments, customer constraints, and operational evidence. |
| **Building products that identify customer pain** | Start from the operator’s expensive decision, then shape the model, runtime, and interface around it. |
| **Work in the open where appropriate** | Share public evidence and open-source work while protecting customer data, credentials, and the commercial moat. |

### Collaboration Norms

- Prefer small, reviewable changes with a clear owner and completion signal.
- Treat a failed experiment as useful when its input, configuration, and outcome are preserved.
- Review interfaces between teams and systems, not only the code inside one component.
- Make requests, blockers, and decisions explicit; do not rely on silent context.
- Leave the next person a runnable command, a verified artifact, or a clear explanation.

## Six Thinking Hats

Use the hats to separate kinds of thinking during product, engineering, and customer decisions. The team should avoid mixing optimism, fear, evidence, and implementation details into one unstructured debate.

### Problem Statement

**How should Navokoj turn a difficult constraint problem into a useful, verified decision before the customer’s deadline while remaining reliable, explainable, and commercially sustainable?**

| Hat | Navokoj Questions |
|---|---|
| **Blue: Process** | What decision are we making? What is in scope? Which evidence, owner, deadline, and decision rule will close the discussion? |
| **White: Facts** | What do the input, benchmark, customer interview, API trace, billing ledger, and verifier actually show? What is still unknown? |
| **Red: Intuition** | What feels promising, confusing, risky, or exciting to the customer and team? What concern is being felt before it can be fully articulated? |
| **Black: Risks** | Could the result be partial, unverifiable, unaffordable, insecure, too difficult to integrate, or misleadingly positioned? |
| **Yellow: Benefits** | What customer outcome, latency improvement, reliability gain, adoption signal, or technical leverage could this create? |
| **Green: Alternatives** | What smaller experiment, different engine, customer adapter, API contract, pricing path, or deployment model could work better? |

### How to Use the Hats

1. Start with the Blue hat to define the decision and timebox.
2. Gather White-hat facts before debating the story.
3. Use Red-hat reactions to surface user and team concerns.
4. Apply Black-hat scrutiny to reliability, evidence, security, and economics.
5. Use Yellow-hat reasoning to identify the highest-value outcome.
6. Finish with Green-hat alternatives and a concrete next experiment.
7. Return to Blue and record the owner, action, evidence required, and review date.

### Decision Record

Every significant decision should leave behind:

- The chosen option and rejected alternatives.
- The customer or operational problem being addressed.
- Evidence and assumptions used.
- Risks accepted or mitigated.
- The next action, owner, and deadline.
- The signal that will cause the decision to be revisited.

### Example: Should a Large Scheduling Request Route to H100?

**Decision:** A customer submits a large workforce scheduling model with a 60-second deadline. Should Navokoj route it from CPU/L4 execution to H100 execution?

| Hat | Example Discussion |
|---|---|
| **Blue** | Define the decision: choose the execution path for this workload while preserving the deadline, billing contract, and hard-feasibility guarantee. Review the decision after the benchmark run. |
| **White** | The model has 1.4 million variables, 8 million CNF clauses, 60 seconds of budget, and a hard-constraint mask. H100 capacity supports the model; CPU and L4 do not. |
| **Red** | The customer is worried about cost and wants confidence that the larger GPU will materially improve the schedule rather than merely change the invoice. The team is excited because this resembles a workload where the GPU path performed well. |
| **Black** | H100 pricing may exceed the customer’s budget. The model may still return only a partial result. A routing bug could authorize one hardware tier and charge another. Hard constraints must be independently verified. |
| **Yellow** | H100 may deliver a better verified schedule within the deadline, reduce manual repair, and establish a reusable large-scheduling route for future customers. |
| **Green** | Run a short estimate or bounded comparison, return a cost preview, allow a customer-selected budget, and retain the best verified incumbent. Consider streaming CPU or a staged L4-to-H100 handoff as alternatives. |
| **Blue: Decision** | Route to H100 only after capacity and balance checks pass, record the reason and expected charge, verify hard constraints, and compare the result against the customer’s baseline. |

**Decision record:**

- **Chosen option:** H100 with a 60-second budget and explicit preauthorization.
- **Evidence required:** request dimensions, routing decision, runtime, billing ledger, assignment, and independent hard-constraint verification.
- **Owner:** Runtime and customer-integration owner.
- **Review signal:** Revisit if H100 does not improve time-to-feasible or schedule quality enough to justify its cost.

## 1. Prove Customer Value

**Goal:** Make Navokoj useful for expensive operational decisions, starting with scheduling and allocation.

| Objective | Expected Result |
|---|---|
| Turn one real customer workflow into a repeatable model | A customer-shaped scheduling or allocation integration runs end to end through the API |
| Return useful decisions under explicit deadlines | Every supported request returns a best-known assignment, status, residual violations, and runtime metadata |
| Demonstrate economic improvement | At least one pilot records a measurable improvement in time-to-solution, feasibility, quality, or operational cost |

## 2. Make the Runtime Trustworthy

**Goal:** Make every Navokoj decision inspectable, reproducible, and operationally safe.

| Objective | Expected Result |
|---|---|
| Preserve hard-constraint semantics | Hard feasibility is checked independently before a result is marked feasible or solved |
| Make billing exact and explainable | Preauthorization, runtime charge, wallet debit, and ledger metadata use the same normalized workload dimensions |
| Operate reliably across execution modes | CPU, L4, H100, finite-domain, repair, and streaming routes expose consistent status and timeout semantics |

## 3. Convert Access Into Adoption

**Goal:** Turn public technical interest into API usage, paid compute, and design-partner relationships.

| Objective | Expected Result |
|---|---|
| Keep developer access simple | GitHub Sponsors credits, API-key provisioning, documentation, and first request form one understandable path |
| Reduce time to first successful solve | A new developer can move from the docs to a verified API result without personal solver expertise |
| Build a focused partner pipeline | Secure conversations, representative workloads, and pilot commitments in one initial wedge such as workforce scheduling |

## 4. Compound the Technical Advantage

**Goal:** Build a constraint runtime whose breadth, evidence, and operating knowledge improve with every workload.

| Objective | Expected Result |
|---|---|
| Route workloads to the right execution regime | Native Boolean, weighted, finite-domain, GPU, repair, and streaming paths are selected by model shape and deadline |
| Preserve a durable evidence trail | Important results include inputs, configuration, runtime, assignment, verification, and artifact links |
| Expand the reusable platform surface | Customer integrations produce better adapters, diagnostics, verification workflows, and deployment options without exposing the commercial moat |

## Operating Rule

Every objective should produce a visible result: a customer workflow, a verified artifact, a reliable API behavior, a paid usage signal, or a reusable platform capability. Research and infrastructure work should connect to at least one of these outcomes.
