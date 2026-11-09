# Trulin

### The Context Trust Layer for AI Agents.

AI agents are only as reliable as the context they act on.

Trulin helps organizations establish whether information is trustworthy before it reaches AI agents. It transforms enterprise documents and connected sources into traceable claims, backed by evidence, validity, and provenance.

**We are building the trust layer between enterprise knowledge and AI execution.**

---

## What We're Building

Enterprise knowledge is constantly changing. Documents become outdated, sources conflict, and AI systems can confidently act on incorrect information.

Trulin addresses this problem by providing a structured context verification layer.

- **Claim Extraction** — Break enterprise information into atomic, traceable claims.
- **Evidence & Provenance** — Link claims to their original sources and supporting evidence.
- **Conflict Detection** — Identify inconsistencies across documents and information sources.
- **Validity Tracking** — Detect outdated or superseded information.
- **Human Review** — Enable human verification when confidence is insufficient.
- **Trust Decisions** — Evaluate context and return actionable decisions: `ALLOW`, `REQUIRE_REVIEW`, or `BLOCK`.

## How It Works

```text
Enterprise Documents & Data
            |
            v
     Context Ingestion
            |
            v
      Atomic Claims
            |
            v
 Evidence + Provenance
            |
            v
 Conflict & Validity Checks
            |
            v
      Trust Evaluation
            |
            v
 ALLOW | REQUIRE_REVIEW | BLOCK
            |
            v
       AI Agents
```

## Technology

**Backend:** Python, FastAPI, SQLAlchemy, Pydantic  
**Frontend:** Next.js, React, TypeScript, Tailwind CSS  
**Data:** PostgreSQL, pgvector  
**Storage:** S3-compatible object storage


## Our Direction

We believe the next generation of AI systems needs more than retrieval. It needs a reliable way to understand where information came from, whether it is still valid, and whether it should be trusted before taking action.

That's what we're building with Trulin.

---

*Building toward more trustworthy AI systems.*
