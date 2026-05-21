# HIGH-ROI-ENGINEERING-CURRICULUM

> A practical backend/platform engineering curriculum optimized for:
>
> * Agoda
> * Booking.com
> * Uber
> * FAANG
> * Senior Backend Engineering Roles
>
> This is NOT an academic curriculum.
>
> This is a:
>
> # HIGH-ROI ENGINEERING CURRICULUM
>
> focused on:
>
> * distributed systems
> * backend engineering
> * platform engineering
> * scalability
> * reliability
> * system design
> * engineering maturity
> * interview preparation

---

# Goal

Target trajectory:

```text
Backend Engineer
    ↓
Senior Backend Engineer
    ↓
Platform / Distributed Systems Engineer
    ↓
International Product Company Engineer
```

Primary target companies:

* Agoda
* Booking.com
* Uber
* Atlassian
* Google
* Meta
* Stripe
* Datadog

---

# Curriculum Structure

| Phase   | Focus                                | Duration   |
| ------- | ------------------------------------ | ---------- |
| Phase 1 | Engineering Foundation               | 3–4 Months |
| Phase 2 | System Design + Platform Engineering | 3 Months   |
| Phase 3 | DSA + Interviews                     | Ongoing    |
| Phase 4 | Cloud Native + Spring                | 1–2 Months |

---

# PRIORITY LEGEND

| Priority         | Meaning                       |
| ---------------- | ----------------------------- |
| MUST MASTER      | Core career-changing material |
| VERY IMPORTANT   | Strong differentiator         |
| READ LATER       | Useful after foundations      |
| SKIP FOR NOW     | Low ROI initially             |
| NEVER PRIORITIZE | Avoid rabbit holes            |

---

# Repository Structure

```text
HIGH-ROI-ENGINEERING-CURRICULUM/
│
├── FAANG-like.md
├── FAANG.md
├── Product-based-companies.md
│
├── PHASE-1-ENGINEERING-FOUNDATION
├── PHASE-2-SYSTEM_DESIGN+PLATFORM_ENGINEERING
├── PHASE-3-DSA+INTERVIEWS
└── PHASE-4-CLOUD_NATIVE+SPRING
```

---

# Additional Guidance Files

* [`FAANG.md`](./FAANG.md)
* [`FAANG-like.md`](./FAANG-like.md)
* [`Product-based-companies.md`](./Product-based-companies.md)

---

# PHASE 1 — ENGINEERING FOUNDATION

## Duration

3–4 months

This is the MOST IMPORTANT phase.

---

# 1. Effective Java — Joshua Bloch

## PRIORITY: MUST MASTER

### Repository Link

* [`Effective Java`](./PHASE-1-ENGINEERING-FOUNDATION/1.Joshua%20Bloch%20-%20Effective%20Java-Addison-Wesley%20Professional%20%282018%29.pdf)

### Why This Matters

One of the highest ROI Java books for senior backend engineers.

Focus areas:

* immutability
* collections
* generics
* concurrency best practices
* API design
* streams
* defensive coding

Directly improves:

* code quality
* interview answers
* engineering maturity

---

# 2. Java Performance — Scott Oaks

## PRIORITY: VERY IMPORTANT

### Repository Link

* [`Java Performance`](./PHASE-1-ENGINEERING-FOUNDATION/1.Scott%20Oaks%20-%20Java%20Performance%20-%20In-Depth%20Advice%20for%20Tuning%20and%20Programming%20Java%208%2C%2011%2C%20and%20Beyond%20%5Btrue%20pdf%5D.%20%282020%2C%20O%27Reilly%29%20-%20libgen.li.pdf)

### Why This Matters

Most backend engineers never seriously study:

* JVM internals
* GC tuning
* memory optimization
* latency bottlenecks

Huge differentiator at senior backend level.

### Focus Areas

* JVM tuning
* garbage collection
* heap optimization
* profiling
* performance bottlenecks
* latency optimization

---

# 3. Java Concurrency in Practice

## PRIORITY: MUST MASTER

### Repository Link

* [`Java Concurrency in Practice`](./PHASE-1-ENGINEERING-FOUNDATION/2.Goetz%2C%20Brian_Peierls%2C%20Tim_Bloch%2C%20Joshua_Bowbeer%2C%20Joseph%20-%20Java%20concurrency%20in%20practice_%20Brian%20Goetz%20...%20%5Bet%20al.%5D-Addison-Wesley%20Professional%20%282006_2013%29.pdf)

### Why This Matters

Most backend engineers are weak in:

* thread safety
* synchronization
* memory visibility
* concurrent design

This separates:

* CRUD developers

from:

* real backend engineers

### Focus Areas

* synchronization
* locks
* concurrent collections
* executors
* deadlocks
* Java memory model

---

# 4. Designing Data-Intensive Applications (DDIA)

## PRIORITY: ABSOLUTE MUST

### Repository Link

* [`Designing Data-Intensive Applications`](./PHASE-1-ENGINEERING-FOUNDATION/3.Kleppmann%2C%20Martin%20-%20Designing%20data-intensive%20applications_%20the%20big%20ideas%20behind%20reliable%2C%20scalable%2C%20and%20maintainable%20systems%202018.pdf)

### Why This Matters

This is the distributed systems bible.

Directly relevant for:

* Agoda
* Uber
* Booking.com
* Platform Engineering

### Focus Areas

* replication
* partitioning
* consistency
* messaging
* Kafka concepts
* transactions
* stream processing
* distributed failures

---

# 5. System Design Interview — Alex Xu

## PRIORITY: VERY IMPORTANT

### Repository Links

* [`System Design Interview Volume 1`](./PHASE-1-ENGINEERING-FOUNDATION/5.Alex%20Yu%20-%20System%20Design%20Interview_%20An%20Insider%E2%80%99s%20Guide%20%282020%2C%20Independently%20published%29.pdf)

* [`System Design Interview Volume 2`](./PHASE-1-ENGINEERING-FOUNDATION/4.Alex%20Xu%2C%20Sahn%20Lam%20-%20System%20Design%20Interview_%20An%20Insider%27s%20Guide.%202-Byte%20Code%20%282022%29.pdf)

### Why This Matters

Provides:

* scalable architecture patterns
* interview-ready system design
* backend architecture tradeoffs

Read AFTER DDIA basics.

---

# 6. Building Microservices — Sam Newman

## PRIORITY: VERY IMPORTANT

### Repository Link

* [`Building Microservices`](./PHASE-1-ENGINEERING-FOUNDATION/6.Sam%20Newman%20-%20Building%20Microservices_%20Designing%20Fine-Grained%20Systems%20%282021%2C%20O%27Reilly%20Media%29%20-%20libgen.li.pdf)

### Why This Matters

Teaches real-world backend architecture.

Better ROI than:

* random framework tutorials
* basic Spring Boot CRUD content

### Focus Areas

* service boundaries
* decomposition
* resiliency
* observability
* deployment
* communication patterns

---

# PHASE 2 — SYSTEM DESIGN + PLATFORM ENGINEERING

## Duration

3 months

---

# 7. Site Reliability Engineering — Google

## PRIORITY: VERY IMPORTANT

### Repository Link

* [`Site Reliability Engineering`](./PHASE-2-SYSTEM_DESIGN%2BPLATFORM_ENGINEERING/1.Betsy%20Beyer%20-Site%20Reliability%20Engineering_%20How%20Google%20Runs%20Production%20Systems-O%E2%80%99Reilly%20Media%20%282016%29.pdf)

### Why This Matters

Critical for platform engineering mindset.

Most backend engineers never study this seriously.

### Focus Areas

* SLIs/SLOs
* incident management
* monitoring
* operational excellence
* scaling
* reliability

---

# 8. Software Engineering at Google

## PRIORITY: HIGH

### Repository Link

* [`Software Engineering at Google`](./PHASE-2-SYSTEM_DESIGN%2BPLATFORM_ENGINEERING/2.Titus%20Winters%2C%20Tom%20Manshreck%2C%20Hyrum%20Wright%20-%20Software%20Engineering%20at%20Google_%20Lessons%20Learned%20from%20Programming%20Over%20Time%20%282020%2C%20O%27Reilly%20Media%29%20-%20libgen.li.pdf)

### Why This Matters

Helps transition from:

* service-company mindset

to:

* product-company engineering mindset

### Focus Areas

* maintainability
* engineering process
* testing culture
* large-scale systems
* engineering maturity

---

# 9. Clean Architecture — Robert Martin

## PRIORITY: HIGH

### Repository Link

* [`Clean Architecture`](./PHASE-2-SYSTEM_DESIGN%2BPLATFORM_ENGINEERING/3.Robert%20C.%20Martin%20-%20Clean%20Architecture_%20A%20Craftsman%E2%80%99s%20Guide%20to%20Software%20Structure%20and%20Design-Prentice%20Hall%20%282017%29.pdf)

### Focus Areas

* maintainability
* layered design
* boundaries
* architecture thinking

### Why This Matters

Useful for:

* architecture thinking
* maintainable backend systems

Do NOT over-obsess over Uncle Bob ideology.

---

# 10. Refactoring — Martin Fowler

## PRIORITY: HIGH

### Repository Link

* [`Refactoring`](./PHASE-2-SYSTEM_DESIGN%2BPLATFORM_ENGINEERING/4.Martin%20Fowler%20-%20Refactoring_%20Improving%20the%20Design%20of%20Existing%20Code-Addison-Wesley%20Professional%20%282018%29.pdf)

### Why This Matters

Real companies mostly deal with:

* legacy systems
* migrations
* maintainability
* cleanup

### Focus Areas

* code smells
* maintainability
* refactoring patterns
* legacy code improvement

---

# 11. System Design at Google

## PRIORITY: READ LATER

### Repository Link

* [`System Design at Google`](./PHASE-2-SYSTEM_DESIGN%2BPLATFORM_ENGINEERING/5.System%20design%20at%20google%20%282022%2C%20openGenus%29%20-%20Toto.pdf)

### Why This Matters

Useful supplementary reading after:

* DDIA
* Alex Xu
* SRE

---

# PHASE 3 — DSA + INTERVIEW PREPARATION

## Duration

2–3 months parallel with system design

---

# 12. Cracking the Coding Interview

## PRIORITY: VERY IMPORTANT

### Repository Link

* [`Cracking the Coding Interview`](./PHASE-3-DSA%2BINTERVIEWS/1.Gayle%20Laakmann%20McDowell%20-%20Cracking%20the%20Coding%20Interview_%20189%20Programming%20Questions%20and%20Solutions%20%282015%2C%20CareerCup%29%20-%20libgen.li.pdf)

### Why This Matters

Still one of the best interview prep books.

Focus on:

* communication
* problem-solving patterns
* interview thinking

NOT memorization.

---

# 13. Elements of Programming Interviews

## PRIORITY: HIGH

### Repository Link

* [`Elements of Programming Interviews`](./PHASE-3-DSA%2BINTERVIEWS/2.Adnan%20Aziz%2C%20Tsung-Hsien%20Lee%2C%20Amit%20Prakash%20-%20Elements%20of%20Programming%20Interviews%20%282020%29%20-%20libgen.li.pdf)

### Why This Matters

Excellent for:

* algorithmic fluency
* coding interviews
* deeper problem-solving

Use selectively.

Do NOT over-grind.

---

# PHASE 4 — CLOUD NATIVE + SPRING

## Duration

1–2 months

---

# 14. Cloud Native Spring in Action

## PRIORITY: VERY IMPORTANT

### Repository Link

* [`Cloud Native Spring in Action`](./PHASE-4-CLOUD_NATIVE%2BSPRING/1.Thomas%20Vitale%20-%20Cloud%20Native%20Spring%20in%20Action%20with%20Spring%20Boot%20And%20Kubernetes%20%282022%2C%20MANNING%20Publications%29%20-%20libgen.li.pdf)

### Why This Matters

Directly relevant for:

* modern backend engineering
* Kubernetes
* scalable infrastructure
* platform engineering

### Focus Areas

* Spring Boot
* Kubernetes
* cloud-native systems
* resilience
* containerization

---

# 15. Spring Security in Action

## PRIORITY: HIGH

### Repository Link

* [`Spring Security in Action`](./PHASE-4-CLOUD_NATIVE%2BSPRING/2.Laurentiu%20Spilca%20-%20Spring%20Security%20in%20Action%2C%20Second%20Edition%20%282024%2C%20Manning%29%20-%20libgen.li.pdf)

### Why This Matters

Security knowledge strongly differentiates senior backend engineers.

### Focus Areas

* authentication
* authorization
* JWT
* OAuth2
* Spring Security internals

---

# Backend Engineering Topics To Master

## Distributed Systems

* replication
* partitioning
* CAP theorem
* eventual consistency
* transactions
* stream processing

---

## Backend Engineering

* API design
* caching
* queues
* retries
* idempotency
* rate limiting
* observability
* fault tolerance

---

## Infrastructure

* Docker
* Kubernetes
* CI/CD
* cloud fundamentals
* monitoring
* logging
* tracing

---

## Databases

* indexing
* query optimization
* sharding
* replication
* transactions
* NoSQL tradeoffs

---

# Recommended Study Order

## First 90 Days

1. Effective Java
2. Java Concurrency in Practice
3. DDIA basics
4. DSA consistency

---

## Next 90 Days

1. System Design Interview
2. Building Microservices
3. SRE
4. Mock system design

---

## Final Phase

1. Interview preparation
2. Resume optimization
3. Mock interviews
4. Applications + referrals

---

# What To Ignore Initially

Avoid spending large amounts of time on:

* advanced competitive programming
* obscure algorithms
* framework hype
* random YouTube tutorials
* excessive certifications

Focus on:

* backend fundamentals
* distributed systems
* engineering maturity
* production thinking

---

# Recommended Outcome

After completing this curriculum, you should be capable of targeting:

* Senior Backend Engineer
* Platform Engineer
* Distributed Systems Engineer

at companies like:

* Agoda
* Booking.com
* Uber
* Atlassian
* Google
* Meta

---

# Final Advice

The goal is NOT:

* becoming an academic computer scientist

The goal IS:

* becoming a high-impact backend/platform engineer capable of cracking Agoda/Uber/Booking.com/FAANG-level interviews.
