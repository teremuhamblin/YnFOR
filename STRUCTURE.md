# 📁 Structure du dépôt
- YnFOR branche main

```text
YnFOR/
│
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md
│   │   ├── feature_request.md
│   │   └── config.yml
│   │
│   ├── workflows/
│   │   ├── ci.yml
│   │   ├── security-scan.yml
│   │   └── build.yml
│   │
│   ├── PULLREQUESTTEMPLATE.md
│   └── DISCUSSION_TEMPLATE.md
│
├── Docs/
│   ├── architecture.md
│   ├── install.md
│   ├── roadmap.md
│   ├── changelog.md
│   └── README.md
│
├── YnFOR/
│   ├── core/
│   │   ├── engine.py
│   │   ├── utils.py
│   │   └── config.py
│   │
│   ├── modules/
│   │   ├── reconnaissance/
│   │   │   ├── whois.py
│   │   │   ├── dns.py
│   │   │   └── headers.py
│   │   │
│   │   ├── analysis/
│   │   │   ├── parser.py
│   │   │   └── report.py
│   │   │
│   │   └── export/
│   │       ├── json_export.py
│   │       └── yaml_export.py
│   │
│   ├── cli/
│   │   ├── main.py
│   │   └── commands.py
│   │
│   └── init.py
│
├── tests/
│   ├── test_core.py
│   ├── test_modules.py
│   └── test_cli.py
│
├── scripts/
│   ├── ynfor.sh
│   └── deploy.sh
│
├── LICENSE
├── README.md
├── requirements.txt
└── setup.py
```

---

### 🧭 Résumé des zones principales

>>.github/
Templates + workflows CI/CD + discussions → ton dépôt est professionnel et standardisé.

>>Docs/
Documentation complète : architecture, installation, roadmap, changelog.

>>YnFOR/
Le package Python principal :
- core/ → moteur interne, utils, config  
- modules/ → reconnaissance, analyse, export  
- cli/ → interface en ligne de commande  
- init.py → initialisation du package

>>tests/
Tests unitaires pour chaque partie du framework.

>>scripts/
Scripts shell pour automatisation et déploiement.

>>Racine
README, licence, setup, requirements.

---
