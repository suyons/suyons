# Sooyoung Kim

**Infrastructure & Backend Engineer | Open to Remote Worldwide**

- Location: Seoul, Korea (UTC+9)
- Email: [suyons@cccs.uk](mailto:suyons@cccs.uk)
- Blog: [suyons.github.io](https://suyons.github.io)
- LinkedIn: [@suyons](https://www.linkedin.com/in/suyons)

---

## Summary

Infrastructure and platform engineer with experience across endpoint management,
enterprise IT support, application backend operations, and self-hosted DevOps.

I've built and operated full production systems from scratch — from database
schema and business logic to on-premise network design, compliance-constrained
deployment, and day-to-day operations. My environments have included air-gapped
financial networks, GMP-regulated pharmaceutical platforms, and military-scale
endpoint infrastructure.

Outside work, I run production-grade infrastructure on Proxmox VE — multiple
containerized services, Nginx reverse proxy, Cloudflare tunnel, all built from
scratch — to practice the patterns I can't always touch at work, and because I
like the craft. Everything I learn goes on my blog.

---

## Experience

### Application Support Engineer — Pharmaceutical · 2026–Present

- Deployed and operate the collaborative document platform for 200+ users
- Delivered under GMP validation constraints — every deploy gated by documented change control
- Cut deployment time from 10 min (manual) to 1 min via CI/CD pipeline
- Refactored legacy codebase from Node 16 to 24 to mitigate security vulnerabilities
- Migration of legacy database from MSSQL to MySQL, with zero data loss
- **Stack:** Node.js/Express, Redis, RabbitMQ, GitLab Runner, OnlyOffice Document Server

### Infrastructure & Middleware Engineer — Korean Financial Group SI · 2024–2026

- Owned the full stack from scratch on air-gapped network: DB schema design → business logic → network → deploy → operate
- Designed on-prem infrastructure for production and development environments
- Reduced average API response time from 1.5s to 0.3s through query optimization
- Built system serving 3 TPS for 1K+ users on Oracle 19c (5M rows), interacting with legacy systems
- **Stack:** Spring Boot, Oracle Database 19c, Apache/Tomcat, RHEL, JMeter, Enterprise Service Bus, Application Performance Monitoring

### Enterprise Technical Support Engineer — IT Outsourcing · 2023–2024

- Delivered front and back office IT support for global enterprise clients
- Resolved average of 20 tickets/day with under 1-hour resolution time
- Clients: L'Oréal, Calvin Klein, Richemont, Starbucks, and more
- **Stack:** Cisco Meraki, Jira, Microsoft Active Directory, ServiceNow

### Network & Endpoint Infrastructure Administrator — ROK Army · 2020–2022

- Admin for 1.5K+ endpoints across 7 subnets in a central IT control tower
- Enforced NAC/UTM/DRM policies in a classified environment with zero security incidents over 1 year
- Configured Cisco L2/L3 switches: VLANs, ACL, port configuration, network segmentation
- Resolved on-site endpoint incidents (Windows BSOD, malware)

---

## Personal Projects

### Home Lab · 2025–Present

- Running 4 containerized services on single Proxmox VE node at 99.9% uptime over 1 year
- Self-hosted containerized workloads behind an Nginx reverse proxy and Cloudflare DNS/CDN/security proxy
- Runs in production; documented at [suyons.github.io](https://suyons.github.io)

### Algo Trading · 2023–2026

- Built and operated automated trading systems across equities, forex, and crypto over 3 years
- Covered the full pipeline: signal design, backtesting, live execution, and broker API integration
- Ran against real financial stakes, which held the systems to production reliability standards
- 50+ strategies designed and backtested, with a focus on bias mitigation
- Backtested over 5 years of historical data / 10+ instruments

- [TradingView Indicators](https://github.com/suyons/tradingview-indicators) — Pine Script strategy and indicator library
- [cTrader FIX API](https://github.com/suyons/trading-ctrader) — low-latency order execution via FIX protocol
- [ATR Renko Crypto Bot](https://github.com/suyons/trading-atr-renko-gate) — volatility-based strategy on crypto markets
- [FastAPI Wrapped MT5](https://github.com/suyons/fastapi-wrapped-mt5) — REST API wrapper around MetaTrader5 for algo trading

---

## Tech Stack

### Infrastructure & OS

![Linux](https://img.shields.io/badge/Linux-RHEL-informational?style=flat&logo=redhat)
![Proxmox](https://img.shields.io/badge/Proxmox-VE-informational?style=flat&logo=proxmox)
![Docker](https://img.shields.io/badge/Docker-container-informational?style=flat&logo=docker)
![Cisco](https://img.shields.io/badge/Cisco-L2%2FL3_Switching-informational?style=flat&logo=cisco)

### Application

![Spring Boot](https://img.shields.io/badge/Spring_Boot-Java-informational?style=flat&logo=springboot)
![Node.js](https://img.shields.io/badge/Node.js-Express-informational?style=flat&logo=nodedotjs)
![FastAPI](https://img.shields.io/badge/FastAPI-Python-informational?style=flat&logo=fastapi)
![Oracle](https://img.shields.io/badge/Oracle-19c-informational?style=flat&logo=oracle)
![Redis](https://img.shields.io/badge/Redis-cache_+_cluster-informational?style=flat&logo=redis)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-message_queue-informational?style=flat&logo=rabbitmq)

### Web & Networking

![Nginx](https://img.shields.io/badge/Nginx-reverse_proxy-informational?style=flat&logo=nginx)
![Cloudflare](https://img.shields.io/badge/Cloudflare-DNS_CDN_proxy-informational?style=flat&logo=cloudflare)
![AWS](https://img.shields.io/badge/AWS-EC2_S3_RDS_ELB_Route53-informational?style=flat&logo=amazonaws)

### CI/CD

![GitLab](https://img.shields.io/badge/GitLab-self_hosted-informational?style=flat&logo=gitlab)
![GitLab Runner](https://img.shields.io/badge/GitLab_Runner-pipeline-informational?style=flat&logo=gitlab)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-pipeline-informational?style=flat&logo=githubactions)

---

## Certifications

- Engineer Information Processing (Korean national IT certification)

---

## Education

- Bachelor of Computer Science · National Examination · 2026
