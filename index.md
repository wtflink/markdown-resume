---
layout: resume
title: Chia-Jui Chang's resume
---

## Ray Chang

Email: [wtflink515@gmail.com](mailto:wtflink515@gmail.com) | [GitHub](https://github.com/wtflink) | [Linkedin](https://www.linkedin.com/in/chia-jui-chang/)

## Summary

Senior backend engineer with 7+ years of experience building distributed systems, chatbot platforms, and developer tooling. Specialized in Node.js and Python, with a track record of delivering scalable services on Kubernetes and AWS. Currently available for freelance and contract engagements.

## Professional Experience

### Senior Backend Developer @ *[Appier](https://www.appier.com/)*

`Mar 2022 - Mar 2024`

- Contributed to a platform serving a retail client with 4.65M monthly active users and 5M offline data records ingested per day.
- Participated in a major microservices rearchitecture of the campaign pipeline, decomposing a monolithic system into independently deployable services (segmentation, creative composition, campaign orchestration) across a 38-repo codebase maintained by a team of 10.
- Bootstrapped a short URL and server-side tracking system from the ground up, enabling more reliable attribution for marketing analytics.
- Built a performance testing harness that generated 145 million records in a single day to validate system throughput under load.
- Led integration of a third-party SMS messaging system, expanding the platform's outbound channel coverage.
- Executed multiple proof-of-concept projects: LLM-generated content integration into a CMS, Redis bloom filter vs. hashmap benchmark for high-cardinality deduplication, and third-party messaging vendor evaluation.

### Technical Team Lead @ *[YOCTOL.AI](https://yoctol.ai/tw/)*

`May 2021 – Dec 2021`

- Led a flat, partially remote engineering team of ~5 developers, handling task assignment, recruitment, interviews, and onboarding.
- Operated and maintained a distributed system on Kubernetes, covering development, versioning, debugging, deployment, and monitoring.
- Independently led a zero-downtime migration across Azure Kubernetes Service clusters: 120 running pods, services averaging 500 RPM, using Kubernetes tooling and [Velero](https://velero.io/) for state backup and restore.
- Established team documentation practices to improve knowledge transfer and reduce onboarding friction.

### Software Developer @ *[YOCTOL.AI](https://yoctol.ai/tw/)*

`May 2018 – May 2021`

- Monitored PostgreSQL performance, identified bottlenecks, and optimized slow queries to improve system throughput.
- Implemented backend features via GraphQL, integrating databases, event brokers, and third-party services.
- Maintained distributed system reliability by triaging and resolving production errors.
- Built and maintained integration and end-to-end test suites, keeping coverage above team-defined thresholds.
- Extended the chatbot platform to support both LINE and Facebook Messenger, contributing to the core framework based on production experience.
- Tracked and integrated new features released by LINE and Facebook to keep user-facing experiences current.

### Chatbot Developer @ *[YOCTOL.AI](https://yoctol.ai/tw/)*

`Nov 2017 – Dec 2019`

- Built multiple production chatbots on the [Bottender](https://github.com/Yoctol/bottender) framework; contributed bug fixes and feature improvements back to the open-source project.
- Maintained the Yoctol official customer-service chatbot.
- Built a campaign chatbot for a leading Taiwanese telecom that handled 60,000 requests in a 5-minute window without degradation.
- Built a dual-platform (LINE + Facebook) customer-service chatbot for the same telecom client.
- Built an NLU-based customer-service chatbot for a major Taiwanese banking and insurance group.
- Built a dental clinic chatbot CMS from scratch, and deployed it on Kubernetes with appropriate operational design.

## Technical Experience

### Side Projects

- *[usb-lab](https://github.com/wtflink/usb-lab)* — Reverse-engineered a monitor's USB KVM interface to build a macOS-compatible driver in Node.js. Analyzed USB signals between the OS and the monitor to identify the KVM command protocol, then implemented a driver on top of [libusb](https://github.com/libusb/libusb) to allow toggling input sources programmatically — filling a gap where no macOS driver existed.

### Open Source

- *[Bottender](https://github.com/Yoctol/bottender)* — Started as a user of this multi-platform messaging framework, then grew into an active contributor. Contributions spanned identifying business use cases, improving developer experience, writing documentation, fixing bugs, and implementing new features.

## Education

### Bachelor's degree, Computer Science and Information Engineering @ National Cheng Kung University (Tainan, Taiwan)

`2011 – 2016`

Kept a broad academic scope beyond the core curriculum, taking courses in philosophy, psychology, and social practice. This cross-disciplinary approach has carried over into how I approach engineering: balancing technical rigor with communication and team dynamics.

## Skills

- **Proficient**
  - Node.js
  - Python
  - PostgreSQL
  - GraphQL
  - Docker
  - Git & GitHub
  - Debugging
- **Familiar with**
  - MongoDB
  - MySQL
  - Redis
  - RabbitMQ
  - Kubernetes
  - AWS
  - Azure
  - Prometheus & Grafana
  - Testing (integration & E2E)
  - Remote Collaboration
  - Agile / SCRUM
- **Basic understanding**
  - Golang
  - React
  - Apache Kafka
