# Joseph Tracy

Infrastructure and enterprise storage engineer in Seattle. More than two decades in production operations, currently working backline escalation on enterprise distributed NAS platforms and moving deliberately into automation and systems design.

The writing and the current work live at **[revisualized.com](https://revisualized.com)**.

---

## How I work

What I bring is judgment between tools rather than a count of them. Knowing when a problem wants a script, when it wants configuration management, and when it wants orchestration is a different skill from knowing the syntax of all three, and it is the part that holds up when a change has to be safe to run twice against a production system. That judgment came out of production incidents rather than out of a course.

Backline escalation means work arrives already escalated: production-impacting outages, Severity 1 recovery against aggressive deadlines, and accounts where the technical fault and the customer relationship have to be repaired in the same engagement. Alongside casework I facilitate corrective-action reviews, mentor engineers on escalation handling and troubleshooting method, and route field-observed failure patterns back to platform engineering.

My specialization sits in the support-connectivity and observability layer: telemetry and call-home channels, event notification and SMTP alerting, health-check diagnostics, certificate and management-plane failures, and the platform job subsystem. Not the filesystem, protocol, networking, or directory-services layers.

---

## What I publish here

Small operational tools, each built for a problem that recurs, each published with its source and its tests. No frameworks. A tool that only its author can run has not been finished.

The standards are consistent across everything current in this account:

- Safe to run twice against a live system
- Fails closed, with the failure legible to whoever finds it at 3am
- Dependencies checked before work begins, not discovered halfway through
- Tests that can fail, rather than confidence in the output

If you are evaluating whether I ship, read the test suites before the source.

---

## Capability, tiered honestly

**What I can be held to.** Systems design and the reasoning behind the design. Shell and scripting craft in Bash and PowerShell, with Pester coverage on the PowerShell I ship rather than confidence in its output. Incident, escalation, and failure-mode analysis under real time pressure. Runbook and troubleshooting-guide authoring that survives handoff between shifts and regions. Linux and Windows systems administration, and enterprise storage at scale.

**What I am applying, framed as practice rather than authority.** Containers and Docker. Observability and monitoring design, built on production experience with SolarWinds Orion, SCOM, Datadog, and PagerDuty. I write about these as applied practice and say so when a piece documents a first pass rather than a settled approach.

**What I am building toward.** Ansible, Kubernetes, Terraform at depth, cloud at depth, and GitOps. I learn these in public and I do not claim them.

---

## Education and training

Network Design and Administration at Seattle Central College, 117 credits, covering the Cisco routing and switching track, Windows Server administration, UNIX, and the CompTIA A+, Network+, and Linux+ subject areas. Vocational certificate in Computer Services from Centennial Job Corps Center.

Instructor-led technical training since: Red Hat System Administration I and II (RH124 and RH134, v8 and v9.3) and RH024. Red Hat Ansible Basics (DO007). PowerScale administration, advanced administration, and advanced Bash scripting for OneFS. Kepner-Tregoe structured problem solving, 45 hours.

These are course completions, not exams. I have not sat EX200 and I do not claim RHCSA.

---

## About this account

Older repositories here are coursework from earlier study and do not represent current work. The tooling I build day to day runs inside customer environments and is not publishable, so what appears here is built independently, against public documentation and my own lab, on my own hardware and my own time.

[revisualized.com](https://revisualized.com) · [LinkedIn](https://linkedin.com/in/josephtracy)
