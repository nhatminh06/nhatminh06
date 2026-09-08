# Minh Pham

Computer Science and Mathematics student at the University of Minnesota, Twin Cities, interested in **distributed systems, backend infrastructure, databases, networking, and AI systems**.

I like building systems where correctness matters under concurrency, failures, retries, resource constraints, and real operational conditions. Most of my recent projects focus on understanding the mechanisms behind infrastructure rather than only assembling existing tools.

## Areas of Focus

- **Distributed systems** — consensus, replication, scheduling, leases, failure recovery
- **Backend and database systems** — transactions, concurrency control, messaging, reliability
- **Systems programming** — networking, storage engines, Linux, low-level debugging
- **Platform engineering** — CI/CD, Kubernetes, GitOps, observability, infrastructure as code
- **AI systems** — accelerator modeling, inference performance, ML infrastructure

## Featured Projects

| Project | What I Built | Focus |
|---|---|---|
| [**ForgeCI**](https://github.com/nhatminh06/forgeci) | Self-hosted distributed CI engine with DAG scheduling, remote runners, PostgreSQL-backed job leasing, immutable source snapshots, artifacts, caching, durable logs, and native GitHub integration. | Distributed systems, scheduling, concurrency, Go, PostgreSQL |
| [**PgSentry**](https://github.com/nhatminh06/pgsentry) | PostgreSQL reliability engineering lab for studying automatic failover, replication durability, network partitions, migration risk, backup recovery, and operational alerting using real multi-VM failure experiments. | PostgreSQL, HA, distributed coordination, failure engineering |
| [**TensorForge**](https://github.com/nhatminh06/tensorforge) | AI accelerator performance-modeling toolkit for studying GEMM, Transformer, and Conv2D workloads across PE arrays, SRAM capacity, tiling strategies, DRAM traffic, and measured hardware performance. | AI systems, computer architecture, performance modeling, Python |
| [**QuorumKV**](https://github.com/nhatminh06/quorumkv) | Distributed key-value store implementing Raft consensus, replication, snapshots, membership changes, ReadIndex, crash recovery, and real-process cluster testing. | Consensus, distributed systems, Go |
| [**Wirestack**](https://github.com/nhatminh06/wirestack) | User-space networking stack implementing TCP behavior including retransmission, adaptive RTO, flow and congestion control, NewReno, SACK, DNS resolution, HTTP, and Linux TAP interoperability. | Networking, protocols, systems programming, C++ |
| [**CommerceCore**](https://github.com/nhatminh06/commercecore) | Correctness-first e-commerce backend exploring inventory contention, transactional checkout, idempotency, payment ambiguity, Kafka delivery, transactional outbox, reconciliation, and remote-service failures. | Java, Spring Boot, PostgreSQL, Kafka, gRPC |

## More Systems Work

- [**PageDB**](https://github.com/nhatminh06/pagedb) — educational database engine written in C with pages, buffer management, table storage, catalog, query execution, SQL planning, TCP protocol, and a Java client.
- [**AEIGS**](https://github.com/nhatminh06/aeigs) — security-focused GitOps private cloud built with FluxCD, Kubernetes, Cilium, Kyverno, SOPS, Authentik, Prometheus, Loki, Grafana, and Hubble.
- [**Linux Kernel Lab**](https://github.com/nhatminh06/linux-kernel-lab) — custom Linux kernel environment with BusyBox, QEMU, kernel debugging, and character-device development in C.
- [**MatchSense**](https://github.com/nhatminh06/matchsense) — real-time football analytics platform using Go, Python, Kafka, Redis, Kubernetes, GitOps, and distributed observability.
- [**Market Pulse**](https://github.com/nhatminh06/market-pulse) — analytical data platform built around Apache Iceberg, Trino, dbt, Airflow, Terraform, and MinIO.

## What I Like to Study

A recurring question across my projects is:

> What actually happens when the normal path stops being normal?

That has led me to experiment with:

- concurrent transactions and race conditions
- process crashes and restart recovery
- network partitions and quorum loss
- duplicate and reordered messages
- stale distributed workers
- ambiguous remote operations
- storage durability and recovery
- protocol retransmission and congestion
- memory and compute bottlenecks
- observability during real failures

I try to make those behaviors measurable through tests, failure injection, benchmarks, and reproducible experiments instead of describing them only at the architecture level.

## Experience

- **DevSecOps Engineering Intern** — VietinBank
- **Full-stack Engineering Intern** — FPT Software

## Technical Focus

**Languages:** Go, Java, C, C++, Python, TypeScript  
**Systems:** Linux, TCP/IP, Raft, PostgreSQL, Kafka, gRPC  
**Infrastructure:** Kubernetes, Docker, Terraform, FluxCD, ArgoCD  
**Observability:** Prometheus, Grafana, Loki, OpenTelemetry, Jaeger  
**AI / ML:** PyTorch, MLflow, accelerator performance modeling, model serving

## Contact

- Email: [mphamnhat2006@gmail.com](mailto:mphamnhat2006@gmail.com)
- LinkedIn: [linkedin.com/in/minhpham2418](https://linkedin.com/in/minhpham2418)
- Portfolio: [minhpham06.com](https://minhpham06.com)
- GitHub: [github.com/nhatminh06](https://github.com/nhatminh06)
