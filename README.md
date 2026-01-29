# Awesome LinkedIn Automation Tools

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)
![GitHub stars](https://img.shields.io/github/stars/sobingt/awesome-linkedin-tools?style=social)
![CI](https://img.shields.io/github/actions/workflow/status/sobingt/awesome-linkedin-tools/ci.yml?label=CI)

> An awesome, community-maintained list of LinkedIn automation tools for sourcing, outreach, and workflow automation. Built for recruiters and sales teams. Use responsibly.

---

## Purpose

This repository is a **single-source Awesome List** you can fork, star, and contribute to. It groups tools by the **LinkedIn activity they automate** — outreach, task automation, automation frameworks, data extraction, enrichment, and multichannel follow-ups — with practical notes for recruiters and sales teams.

Primary use cases:

* **Recruiters**: sourcing, outreach, candidate nurture, ATS/CRM sync
* **Sales teams**: lead generation, follow-up sequences, pipeline enrichment

Contributions are encouraged — see **How to contribute** below.

---

## Table of contents

1. [Outreach](#1-outreach)
2. [Task Automation](#2-task-automation)
3. [Automation frameworks](#3-automation-frameworks)
4. [Data Extraction & Enrichment](#4-data-extraction--enrichment)
5. [Multichannel Outreach & CRM Integrations](#5-multichannel-outreach--crm-integrations)
6. [How to contribute](#6-how-to-contribute)
7. [License](#7-license)

---

> **Tag legend:** `outreach`, `task-automation`, `scraping`, `enrichment`, `cloud`, `extension`, `automation`, `framework`, `integration`, `crm`, `ai`

---

## 1) Outreach

Tools that automate connection requests, personalized messaging sequences, follow-ups, and drip campaigns.

| Tool                                                                                                            |              Type | Short description                                                           | Best for                                 | Tags                             |
| --------------------------------------------------------------------------------------------------------------- | ----------------: | --------------------------------------------------------------------------- | ---------------------------------------- | -------------------------------- |
| [Expandi](https://expandi.io)                                                                                   |        Cloud SaaS | Cloud-based LinkedIn outreach with sequence builder and safety throttling.  | Recruiters, agencies, sales teams        | `outreach`, `cloud`              |
| [Dripify](https://dripify.com)                                                                                  |        Cloud SaaS | Visual sequence builder for LinkedIn and email follow-ups.                  | Sales teams, recruiters                  | `outreach`, `cloud`              |
| [Meet Alfred](https://meetalfred.com)                                                                           |              SaaS | Multi-channel automation: LinkedIn, email, and Twitter.                     | SMB sales, recruiters                    | `outreach`, `cloud`              |
| [HeyReach](https://www.heyreach.io)                                                                             |             Cloud | Scalable LinkedIn outreach across multiple accounts with sequences.         | Agencies, high-volume teams              | `outreach`, `cloud`              |
| [Closely](https://closelyhq.com)                                                                                |             Cloud | AI-assisted personalization for multi-channel outreach including LinkedIn.  | Sales & recruiting teams                 | `outreach`, `cloud`, `ai`        |
| [Salesforge](https://salesforge.io)                                                                             |             Cloud | AI-focused multichannel outbound platform usable with LinkedIn workflows.   | Sales ops, outbound teams                | `outreach`, `cloud`, `ai`        |
| [InTouch](https://chrome.google.com/webstore/detail/intouch-linkedin-auto-con/fngoamlbhhojhodbgoeknadgabgjpgmg) | Browser extension | Lightweight extension for auto-connections and messaging.                   | Individual sourcers                      | `outreach`, `extension`          |
| [Dux-Soup](https://www.dux-soup.com)                                                                            | Browser extension | Profile visiting, tagging, and messaging automation from the browser.       | Individual recruiters, sourcers          | `outreach`, `extension`          |
| [Linked Helper](https://www.linkedhelper.com)                                                                   |    Desktop / SaaS | Feature-rich automation for large-scale outreach and conditional sequences. | High-volume recruiters, agencies         | `outreach`, `task-automation`    |
| [Waalaxy](https://www.waalaxy.com)                                                                              | Extension / Cloud | Campaigns across LinkedIn and email with enrichment and CRM sync.           | Recruiters running multi-step cadences   | `outreach`, `cloud`, `extension` |
| [Octopus CRM](https://octopuscrm.io)                                                                            |         Extension | CRM-style LinkedIn automation for campaigns and pipelines.                  | Small teams, budget-conscious recruiters | `outreach`, `extension`          |
| [Zopto](https://zopto.com)                                                                                      |             Cloud | Automated LinkedIn outreach platform focused on Sales Navigator users.      | Agencies scaling outreach                | `outreach`, `cloud`              |

---

## 2) Task Automation

Tools that automate recurring LinkedIn UI actions such as profile visits, follow/unfollow, auto-accept replies, tagging, or delayed messaging.

| Tool                                          |           Type | Short description                                      | Best for                            | Tags                           |
| --------------------------------------------- | -------------: | ------------------------------------------------------ | ----------------------------------- | ------------------------------ |
| [Dux-Soup](https://www.dux-soup.com)          |      Extension | Auto-visits, auto-messaging, tagging, and notes.       | Sourcers mixing manual + automation | `task-automation`, `extension` |
| [Linked Helper](https://www.linkedhelper.com) | Desktop / SaaS | Advanced task flows with conditional logic and delays. | Teams with complex funnels          | `task-automation`, `cloud`     |
| [Zopto](https://zopto.com)                    |          Cloud | Automation pods for profile visits and outreach.       | Agencies scaling outreach           | `task-automation`, `cloud`     |

---

## 3) Automation frameworks

Scriptable tools and headless browsers used for custom automations, scraping, and repeatable flows. These require engineering skills and carry higher platform risk.

| Tool                                 |              Type | Short description                                                  | Best for                                | Tags                                  |
| ------------------------------------ | ----------------: | ------------------------------------------------------------------ | --------------------------------------- | ------------------------------------- |
| [iMacros](https://imacros.net)       | Browser extension | Macro recorder/playback for repetitive browser tasks.              | Quick scripted automations              | `automation`, `extension`             |
| [Playwright](https://playwright.dev) |         Framework | Cross-browser automation framework for headless or headed scripts. | Engineering teams building custom flows | `automation`, `framework`, `scraping` |
| [Puppeteer](https://pptr.dev)        |         Framework | Headless Chrome/Chromium automation via DevTools protocol.         | Engineering teams and scripts           | `automation`, `framework`, `scraping` |

---

## 4) Data Extraction & Enrichment

Tools used to extract LinkedIn data, enrich profiles, or find emails and contact details for ATS/CRM workflows.

| Tool                                       |             Type | Short description                                                                       | Best for                            | Tags                              |
| ------------------------------------------ | ---------------: | --------------------------------------------------------------------------------------- | ----------------------------------- | --------------------------------- |
| [PhantomBuster](https://phantombuster.com) | Cloud automation | API-style automations and scrapers for LinkedIn Search, Recruiter, and Sales Navigator. | Recruiters and growth teams         | `scraping`, `cloud`               |
| [Wiza](https://wiza.co)                    |             SaaS | Convert Sales Navigator lists into verified emails and enriched contacts.               | Sourcers needing emails at scale    | `enrichment`, `cloud`             |
| [Evaboot](https://evaboot.com)             | Tool + extension | Clean, deduplicated Sales Navigator exports.                                            | Teams heavily using Sales Navigator | `scraping`, `extension`           |
| [Kaspr](https://kaspr.io)                  |             SaaS | Contact enrichment and phone/email discovery for LinkedIn profiles.                     | Recruiters needing contact data     | `enrichment`, `cloud`             |
| [Lusha](https://www.lusha.com)             |             SaaS | B2B contact data enrichment with LinkedIn-friendly integrations.                        | Recruiters needing contact data     | `enrichment`, `cloud`             |
| [Apollo.io](https://www.apollo.io)         |             SaaS | Prospect database with enrichment and outreach workflows.                               | Recruiters and sales teams          | `enrichment`, `outreach`, `cloud` |
| [Snov.io](https://snov.io)                 |             SaaS | Email discovery, enrichment, and outreach automation.                                   | Recruiters needing contact data     | `enrichment`, `outreach`, `cloud` |
| [ContactOut](https://contactout.com)       |             SaaS | Email and phone discovery for LinkedIn profiles.                                        | Targeted outreach workflows         | `enrichment`, `extension`         |
| [SalesQL](https://salesql.com)             |             SaaS | B2B contact discovery via LinkedIn extension.                                           | Targeted outreach workflows         | `enrichment`, `extension`         |
| [Hunter](https://hunter.io)                |             SaaS | Domain- and profile-based email discovery and verification.                             | Targeted outreach workflows         | `enrichment`, `cloud`             |
| [Skrapp](https://skrapp.io)                |             SaaS | Email finder for LinkedIn and Sales Navigator.                                          | Targeted outreach workflows         | `enrichment`, `cloud`             |

---

## 5) Multichannel Outreach & CRM Integrations

Platforms that combine LinkedIn with email or sync data into CRMs and ATS.

| Tool                                     |       Type | Short description                                                   | Best for                        | Tags                        |
| ---------------------------------------- | ---------: | ------------------------------------------------------------------- | ------------------------------- | --------------------------- |
| [Reply.io](https://reply.io)             |       SaaS | Multichannel sequences with LinkedIn tasks and CRM sync.            | Team-based outreach             | `outreach`, `cloud`         |
| [Lemlist](https://lemlist.com)           |       SaaS | Email and LinkedIn sequences with advanced personalization.         | Sales outreach teams            | `outreach`, `cloud`         |
| [HubSpot](https://www.hubspot.com)       |        CRM | CRM with LinkedIn lead capture and integrations.                    | Enterprise recruiting teams     | `crm`, `integration`        |
| [Salesforce](https://www.salesforce.com) |        CRM | Enterprise CRM with LinkedIn and automation integrations.           | Enterprise recruiting teams     | `crm`, `integration`        |
| [Zapier](https://zapier.com)             | Automation | No-code automation connecting LinkedIn tools with CRMs and ATS.     | Lean teams automating pipelines | `automation`, `integration` |
| [Make](https://www.make.com)             | Automation | Visual workflow automation for advanced LinkedIn-related pipelines. | Lean teams automating pipelines | `automation`, `integration` |

---

## 6) How to contribute

1. Fork this repository.
2. Add tools under the appropriate category using the same table format.
3. Include a one-line description, homepage link, and tags from the legend.
4. Open a pull request with clear notes and label the PR (e.g., `automation`, `enrichment`).

**Submission checklist**

* Tool name and canonical homepage
* One-line description (max 20 words)
* Tags from the legend (at least one)
* Category (Outreach / Task Automation / Automation frameworks / Data Extraction / Multichannel)
* Risk level: `low`, `medium`, or `high` (automation/scraping risk)

---

## 7) License

This project is licensed under the MIT License. See `LICENSE.md` for details.

---

*Last updated: 29 January 2026*

*Maintainer: @sobingt*