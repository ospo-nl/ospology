---
markmap:
  initialExpandLevel: 2
  maxWidth: 400
---

# 🧭 OSPO Mindmap - [Beschikbaar in meerdere talen](https://github.com/todogroup/ospology/tree/main/ospo-mindmap/Content)

## 🙋 Rollen

- Governance
- Project Management
- Licenties
- Security
- Betrokkenheid van Community
- Trainen van Ontwikkelaar
- Individuele Bijdrager 
- Open Source Adviseur

## 🚀 Gedrag

### Samenwerking in de Sector

- `Definitie` OS is voor een specifieke industrie een manier om efficienter te worden door het delen van kosten en innovatie voor industrie-specifieke behoefte
- `Voorbeeld` EU Automotive industrie

### Sectoroverstijgende Samenwerking

- `Definitie` Werk op fundamentele technologie problemen verspreid over verschillende sectoren
- `Voorbeeld:` Bloomberg heeft samengewerkt met Microsoft om bij te dragen aan TypeScript

### Standaarden om samen te werken

- `Definitie` Ondersteuning voor relevante standaarden in open source projecten en het geven van feedback aan gelijkesoortige organisaties voor standaarden
- `Voorbeeld:`Het aanmoedigen en sturen van deelnemers van orgsanisaties om deel te nemen aan zowel de Let's Encrypt gemeenschap als de IETF standaarden om gebruik te maken van CME, TLS en ander werk regelateerd aan X.509 certificaten

### Begeleiding van grote projecten

- `Definitie` Vorm of faciliteer het formeren van grote, complexe open source projecten buiten een organisatie en/of Lanceer OS als publiek beschikbare projecten
- `Voorbeeld` Comcast begeleid het Apache Traffic Control Project

### Open Source Eerst

- `Definitie` Het helpen van de organisatie om OSS comsumptie te prioriteren en het maken van OS als eerste keuze
- `Voorbeeld` OSPOs die samenwerken met CTO's en bedrijfsstrategen om open source projecten en mogelijkheden op de kaart te zetten

### Technologie Strategie Experts

- `Definitie` Evaleer werkbare open source technologien en help senior IT Manager om een technologie roadmap neer te leggen
- `Voorbeeld` OSPOs die acteren als interne OS consultant om teams en ontwikkelaars te helpen

### Software Bedrijf

- `Definitie` 
- More likely to incubate or participate in big projects and more likely
to have dedicated developers working exclusively on OS
- `Voorbeeld` Software bedrijven die de basis vormen van het ontwikkelteam van het Linux Project

## 🌱  Grootte

- Groot Team (voltijd)
- Klein Team (voltijd)
- Virtueel team (niet Voltijd)
- Virtueel voltijdsteam met virtuele deelnemers vanuit andere teams
- Enkele Voltijder die meerdere teams besturen

## 🧩 Verantwoordelijkheden

### 📘 Ontwikkelen en Uitvoeren Open Source Strategie

- Open Source community, bijdragen en leiderschap
- Compliance
- InnerSource
- Behandeling van vragen vanuit klanten, medewerkers, investeerders of community deelnemers
- Risico tolerantie
  - Open-sourcing van organisatie code
  - Vrijgeven van code met bekende open source problemen (licentie/security)
  - Vrijgeven van code die impact heeft op het merk, 
  - Releasing code which may impact the organization's brand, product differentiatie o intellectueell eigendoms portfolio
- Bedrijfsontwikkeling
  - Fusies en Overnames (M&A)
  - Ge-Outsourcde ontwikkeling (inhuur)
- Software aanschaf
- Marketing
- Communicatie
- Groei en behoud van open source talent

### 🔍 Overzicht Open Source Compliance

#### Compliance Overwegingen
- Voldoen aan de open source licentie voorwaarden
  - het mixen van code
    - Bijdragen faciliteren
    - Het bijhouden van wijzigingen
  - Delivery methoden
    - Container
      - Container receipe (Dockerfile)
      - Container image
    - Hardware
    - SDK
      - Deliverable met dependencies
      - Deliverable downloads dependencies door installatie
      - Gebruiker van het product levert dependencies op
    - RESTful API
    - SaaS
    - Web Applicatie
- Faciliteer het effectief gebruik van open source in eigendomsmatige producten of diensten
- Voldoen aan contractuele verplichtingen van externe software leveranciers of klanten
- Beschermen van intellectueel eigendom van organisaties
  - Open source met gepaste zorgvuldigheid behandelen voor overnamescts)
  - Controleer of nieuwe open source projecten in organisaties geen inbreuk maken op handelsmerken van derden
- Veilig houden van productie
- De productdifferentiatie van de organisatie beschermen
  - Controleer of handelsgeheimen in de code aanwezig zijn die worden geopensourced


#### Trainen van Ontwikkelaars
- Training & Certificering
  - [Open Source Licensing Basics for Software Developers (LFC191)](https://training.linuxfoundation.org/training/open-source-licensing-basics-for-software-developers/)
  - [Introduction to Open Source License Compliance Management (LFC193)](https://training.linuxfoundation.org/training/introduction-to-open-source-license-compliance-management-lfc193/)
  - [Implementing Open Source License Compliance Management (LFC194)](https://training.linuxfoundation.org/training/implementing-open-source-license-compliance-management-lfc194/)

#### Software Inventarisatie

- Security Standaard
- Licentie Compliance Policies


### 📝 Vaststellen en Verbeteren van Open Source Policies and Processen

##### Policies

- Gebruik van open source en open source compliance policies
  - Forken van een open source project
  - Kopieren van open source licenties bestanden/snippets in de codebase van de organisatie
  - Mixen van code (in eigendom c)
  - Mixing code (eigendom en OSS eigendom van derden) en distributie als product of service (sdk, REST API, SaaS, etc.)
  - Gebruik maken van standalone open source tools (e.g. Firefox, MySQL, CentOS)
- Policy op open source en eigen licenties
  - Concluding of obligations of licenses
  - Classification of licenses
  - Complying with license obligations
- Policy on releasing code as open source
  - Contributing back to third party OSS project
  - Publishing a new open source project
  - Contributing in personal time
  - Signing contribution agreements (e.g. CLA or DCOs)
- Policy on making open source business decisions
  - Risk assessment and acceptance  
  - Business alignment

#### Processen

- Creeëren van Open Source
  - Contributing to third-party OSS projects during work time
    - Which copyright statement to use for contributions on behalf of the organization?
    - What to do if there is already a copyright notice in the code?
    - What to do if there is no copyright notice in the code?
    - What to do if the community objects to any changes to the copyright notices?
  - Contributing to third-party OSS projects during personal time
  - Publishing a new open source project
    - Remove from the code any internal references (trade secrets, system names/urls)
    - Check if the new project name is already in use in the community or is trademarked
    - Perform a patent review
      - Freedom to operate: verify project does not infringe third-party's intellectual property
      - Protect organization's intellectual property
        - Does the contribution reveal organization's non-public plans?
        - Does the contribution share the organization's technology advantage with its competitors?
        - Does the contribution prevent the organization from filling new patents for features included in contributed code
        - What is the impact of the contribution on the organization's intellectual property licensing?
    - Perform a legal review
      - Review licenses applicable to contributed code, images or documents
      - Review licenses of dependencies used by contributed code
    - Provide guidance to contributors on open source community ways of working
    - Publishing of project's release artifacts to public repositories such as Maven Central, npm, etc.
  - Sponsoring Open Source
    - Sponsoring third-party projects or individuals
    - Sponsoring open source organizations
    - Sponsoring own organization's open source projects or individual members
    - Sponsoring events
  - Signing contribution related agreements
    - Contributor license agreement (individual / corporate)
    - Developer certificate of origin
  - Shutting down a new open source project
- Using Open Source
  - Using an open source project as a standalone tool
  - Including open source snippets or files
  - Including open source packages
  - Forking an open source project
  - Inventorying open source usage incl. packages, licensing and communities
  - Maintaining a classification and enforcing rules for open source and proprietary licenses
- Deciding on Open Source
  - Drive Open Source Review Board with senior leaders from relevant stakeholder to make decisions on open source
  - Drive Open Source Working Group with representatives / interested stakeholders throughout the organization with the aim of improving open source at the organization
- Marketing and/or communicating Open Source
  - Internal messaging
    - Maintaining internal wiki outlining policy, processes, tooling and best practices
  - External messaging
    - Organization's open-source principles
    - Simplified/redacted version of open source wiki
    - Organization GitHub ReadMe
    - Open Source landing page / portal
    - Obligation fulfillment
    - Organizing community events
- Educating people
  - Open source awareness which includes details on open source policy, processes, tools and the basics of open source licensing, community and contributions
  - Guidelines and best practices for using of, contributing to, complying with open source
  - Training on open source project management
  - New employee orientation
  - Checklist for product teams
  - Checklist for developers
  - Checklist for SW procurement
  - Executing a mentorship for open source leaders and/or organization leaders
  - Organizing events 
    - Present Open Source at the organization's all-hands and similar meetings
    - Organize brown bag seminars on open source topics (with invited speakers)
  - Assist speakers for coding forums / conferences
- Measuring Open Source
  - Develop, execute and improve measuring the impact of your organization's open source activities

### 📈 Prioritize and Drive Open Source Upstream Development

#### Create Educational Programs

- Good OSS hygiene
- Technical programs
  - Basics in OS tech stack
  - How to request features
  - How to file bug reports
  - How to contribute basic code
  - How to do non-code contributions
    - How to contribute code review
    - How to contribute documentation
    - How to contribute testing
    - How to contribute to project management

#### Create Internal Open Source Ambassadors

- Drive event sponsorship
- Train speakers for coding forums

#### Contributes to Third-Party OSS Projects

- Ensure maintainability of OSS projects
- Develop new features upstream
- Fix bugs upstream
- Improve documentation
- Triage or reproduce issues
- Offer project management
- Perform tests such as hardware, usability, etc.
- Improve user experience
- Develop / improve graphics
- Create localizations (translate to another language)

#### Incubate and Launch Open Source Projects

- Develop internal resources for
project incubation and post launch

- Develop processes for project
incubation and post launch

- Develop playbooks, checklists and tooling
  - Vet, organize and operate OS projects
  - Train and coach OS Leaders

#### Optimalizeren Open Outbound Source Contributions


### 🤝 Samenwerken met Open Source Organizaties

##### 📖 Open Standards

- OpenChain
- SPDX

##### 🏠 Foundations

- Apache Foundation
- Free Software Foundation Europe
  - Legal Network
- Eclipse Foundation
  - OSPO Alliance
- InnerSource Commons
- Linux Foundation
  - FINOS
  - OpenSSF
  - OpenChain
  - SPDX
  - TODO Group
- Open Source Initiative
- OpenForum Europe
- OW2
  - Good Governance Initiative


### ⏱️ Bijhouden Performance Metrieken

- Ability to assess health of open source projects
- Measure community engagement / impact upstream
- Development of open source leaders
- Operate a metrics acquisition and dashboard
- Feedback loop to improve metrics and open source activities

### 🤝 Implementeren van InnerSource Practices

- Increase productivity, quality, code re-use, transparency and trust
- Establish communication channels across the organization
- Improve collaboration across the organization
- Remove organizational silos and identify talent across the organization


### 🫶 Groei en Behoud van Open Source Talent In de Organizatie

- Train new and coach existing open source leaders
- Drive an internal open source ambassadors program
- Create programs to incentivize contributions of organization's members
- Recognize contributions of organization's members


### 🧑‍💼 Geef advies over Open Source

- Shaping the organization's software strategy and processes and role of open soure within the organization's software ecosystem
- Advise on which open source technologies to adopt, hold or avoid
- Provide open source guidance to people whether managers, contributors, open source project leaders/project maintainers with their issues
- Evaluate OSS projects whether technical, health or compliance assessment
- Help to understand and navigate project politics
  - Help maintain a neutral posture on the open source technology ecosystem
  - Cultivate personal and working relationship
- Bring the outside inside the organization
  - Provide insights into open source trends
  - Promote import of community best practices
  - Warn in case of major community incident or changes



### 🖥️  Managen van Open Source IT Infrastructure

- Compliance and contribution tooling
  - Build in-house
  - Adopt existing tools
      - Commercial tools
      - [Open Source tools](https://oss-compliance-tooling.org/Tooling-Landscape/OSS-Based-License-Compliance-Tools/)
- Design OSS infrastructure
- Metrics acquisition and dashboard
- Third-party development tool management such as GitHub, GitLab, etc.


### 🧭  Friction from Using and Contributing to Open Source

- Continuously improve processes and tools to reduce learning curve and manual effort required
- Help navigate internal politics or policies
- Maintain relationships with communities of strategic importance to your organization

### 📒 Support Corporate Development Activities

- Help an organization understand the open source technical stack, compliance and opportunities of the target company and related risk as part of the due diligence process
- Ensure contractors (outsourced developement) follow the organization's open source policies and processes
