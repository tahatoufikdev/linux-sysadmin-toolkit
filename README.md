# 🛠️ Linux SysAdmin Toolkit

> A collection of Bash scripts for automating Linux system administration tasks, oriented toward Cloud Engineering (AWS EC2).

[![Author](https://img.shields.io/badge/Author-TahaDEV-blue?style=flat)](https://tahatoufik.dev)
[![Platform](https://img.shields.io/badge/Platform-Linux-FCC624?style=flat&logo=linux&logoColor=black)](https://www.linux.org/)
[![Shell](https://img.shields.io/badge/Shell-Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/)
[![Cloud](https://img.shields.io/badge/Cloud-AWS-FF9900?style=flat&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/)

---

## 📋 Scripts

| Script | Description | Module |
|--------|-------------|--------|
| [`system-report.sh`](scripts/system-report.sh) | Full system report (CPU, RAM, disk, network, uptime) | Linux 01–05 |
| `user-manager.sh` | User/group management (create, delete, list, sudo) | Linux 06 — Coming |
| `server-hardening.sh` | Automated server hardening (SSH, firewall, fail2ban) | Linux 10 — Coming |
| `log-analyzer.sh` | Log analysis + pattern detection + alerts | Linux 12 — Coming |
| `backup-s3.sh` | Automated backup to AWS S3 | AWS — Coming |
| `nginx-setup.sh` | NGINX install + secure configuration | Linux 15 — Coming |

---

## 🚀 Usage

```bash
# Clone the repo
git clone https://github.com/TahaDEV/linux-sysadmin-toolkit.git
cd linux-sysadmin-toolkit

# Make scripts executable
chmod +x scripts/*.sh

# Run a script
./scripts/system-report.sh
```

---

## 📁 Structure

```
linux-sysadmin-toolkit/
├── scripts/          # All Bash scripts
├── docs/             # Documentation per script
└── README.md
```

---

## 🗺️ Roadmap

Built progressively alongside the **Linux Bootcamp** — one script per module completed.

- [x] `system-report.sh` — Modules 01–05
- [ ] `user-manager.sh` — Module 06
- [ ] `server-hardening.sh` — Module 10
- [ ] `log-analyzer.sh` — Module 12
- [ ] `backup-s3.sh` — AWS Module
- [ ] `nginx-setup.sh` — Module 15

---

## 👤 Author

**Taha TOUFIK (TahaDEV)** — Cloud Engineer in Training · Saudi Vision 2030

[![Portfolio](https://img.shields.io/badge/Portfolio-tahatoufik.dev-FF5722?style=flat)](https://tahatoufik.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-TahaTOUFIK-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/tahatoufik)
