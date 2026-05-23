# ✅ Definition of Done

A clear, agreed standard that every deliverable must meet before it can be called "done."

---

## 🎯 Why Definition of Done Matters

> "Done means released, not just developed."

A strong DoD:
- Eliminates ambiguity between dev, QA and PM
- Prevents half-finished work entering production
- Builds trust with stakeholders
- Improves sprint predictability and velocity

---

## 📋 Standard Definition of Done

### 💻 Development
- [ ] Code written and peer reviewed
- [ ] Code merged to main branch
- [ ] No critical bugs or blockers outstanding
- [ ] Technical debt logged in backlog if any shortcuts taken

### 🧪 Testing
- [ ] Unit tests written and passing
- [ ] Integration tests completed
- [ ] UAT completed and signed off by Product Owner
- [ ] Regression testing passed
- [ ] Performance testing completed where applicable

### ☁️ Azure & Infrastructure
- [ ] Deployed to staging environment successfully
- [ ] Azure resource tagging applied per governance standards
- [ ] RBAC roles configured and verified
- [ ] Monitoring and alerts configured in Azure Monitor
- [ ] Cost impact assessed and approved

### 🔒 Security
- [ ] Security review completed
- [ ] No high or critical vulnerabilities outstanding
- [ ] Data privacy requirements met
- [ ] Access controls verified
- [ ] Compliance requirements satisfied

### 📄 Documentation
- [ ] Technical documentation updated
- [ ] User documentation updated if applicable
- [ ] Release notes drafted
- [ ] Runbook updated for operational teams

### ✅ Stakeholder Sign-Off
- [ ] Product Owner acceptance received
- [ ] Business stakeholder demo completed
- [ ] Go-live approval obtained from relevant parties

---

## 🚀 Definition of Ready

> Before a story enters a sprint it must be "Ready":

- [ ] User story written in correct format
- [ ] Acceptance criteria clearly defined
- [ ] Story pointed and sized by the team
- [ ] Dependencies identified and resolved
- [ ] Design assets available if required
- [ ] Security and compliance requirements documented

---

## 📊 DoD by Story Type

| Story Type | Additional DoD Requirements |
|---|---|
| **Feature** | Demo recorded, release notes updated |
| **Bug Fix** | Root cause documented, regression test added |
| **Azure Infrastructure** | Cost estimate approved, governance checklist complete |
| **Security** | Security sign-off from InfoSec team |
| **Integration** | End-to-end test passed, API documentation updated |

---

## ⚠️ Common DoD Violations to Watch

| Violation | Impact | Prevention |
|---|---|---|
| "It works on my machine" | Fails in production | Deploy to staging before DoD |
| Skipping UAT | Stakeholder dissatisfaction | Make UAT non-negotiable |
| No documentation update | Knowledge gaps | Documentation in every DoD |
| Security review skipped | Compliance risk | Security check mandatory |
| No monitoring configured | Silent failures in prod | Azure Monitor setup in DoD |

---

## 🔄 Reviewing Your DoD

Review and update your DoD:
- At the start of each new project
- After major incidents or production issues
- Every quarter as the team matures
- When new compliance requirements emerge

---
*Maintained by [Sangeeth H P](https://github.com/psharshendra) | Azure Cloud PM*
