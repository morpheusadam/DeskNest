<div align="center">

# 🎫 PHP Tickets — Professional Support & Ticketing System

### A self-hosted PHP help desk and customer support ticketing script — multi-language, RTL-ready, with email & SMS notifications and a secure, robust codebase.

<p>
  <img src="https://img.shields.io/github/stars/morpheusadam/DeskNest?style=for-the-badge&color=ffca28" alt="Stars" />
  <img src="https://img.shields.io/github/forks/morpheusadam/DeskNest?style=for-the-badge&color=42a5f5" alt="Forks" />
  <img src="https://img.shields.io/github/last-commit/morpheusadam/DeskNest?style=for-the-badge&color=8e44ad" alt="Last commit" />
  <img src="https://img.shields.io/github/repo-size/morpheusadam/DeskNest?style=for-the-badge&color=e67e22" alt="Repo size" />
  <img src="https://img.shields.io/badge/version-2.3-0A7BBB?style=for-the-badge" alt="Version 2.3" />
</p>

<p>
  <img src="https://img.shields.io/badge/PHP-7.4%2B-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/MySQL-5.7%2B-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Bootstrap-UI-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
  <img src="https://img.shields.io/badge/jQuery-Ajax-0769AD?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery" />
  <img src="https://img.shields.io/badge/RTL-Ready-2EA44F?style=for-the-badge" alt="RTL ready" />
</p>

</div>

---

## 📖 Overview

**PHP Tickets** is a **professional, self-hosted support and ticketing system** that helps teams manage customer support efficiently from a single web app. Customers open and follow up on tickets from a user panel, while staff handle departments, knowledge-base articles, users, and settings from an admin panel — with **email and SMS notifications** keeping everyone informed of ticket updates.

Built in **PHP** on a clean **MVC structure** (controllers, models, views with a themeable `AH-Tickets` front end) and backed by **MySQL**, the script is **multi-language and RTL-ready** — shipping translation files for English, Persian, Arabic, German, Spanish, French, Italian, Dutch, Russian, Turkish and more. It is designed for **businesses, SaaS products, agencies, and web hosts** who want an installable help desk they fully control on their own server.

> 🔎 **Keywords:** PHP ticketing system, help desk script, customer support software, self-hosted help desk, support ticket system, multi-language help desk, SMS notifications, email notifications, knowledge base, RTL support panel, PHP MVC support script.

---

## ✨ Features

- 🎫 **Comprehensive ticketing** — create, assign, reply to, filter, and track support tickets through their lifecycle.
- 🏢 **Departments & roles** — route tickets to departments; separate admin, staff, and user dashboards.
- 📚 **Knowledge base** — built-in articles so customers can self-serve common questions.
- 🌍 **Multi-language (i18n)** — 12+ bundled language packs (EN, FA, AR, DE, ES, FR, IT, NL, RU, TR, …) with **RTL** support.
- 📧 **Email notifications** — ticket updates via PHPMailer (SMTP) with MailChimp integration.
- 📱 **SMS notifications** — ticket and account alerts via the **MeliPayamak** SMS gateway.
- 🔐 **Accounts & security** — registration, login, account activation, password reset, and social login.
- 📝 **Rich-text editor** — TinyMCE for formatted ticket and knowledge-base content.
- 🎨 **Themeable UI** — Bootstrap-based `AH-Tickets` theme with custom fonts, animations, and a guided web installer.
- ⚙️ **Guided setup & updates** — browser-based installer (`setup.php`) and SQL update scripts.

---

## 🛠️ Tech Stack

| Layer | Technology |
| --- | --- |
| Backend | **PHP 7.4+** (MVC: controllers / models / views) |
| Database | **MySQL 5.7+** |
| Email | **PHPMailer** (SMTP) · MailChimp |
| SMS | **MeliPayamak** gateway |
| Frontend | **Bootstrap**, jQuery (Ajax), TinyMCE, Font Awesome |
| i18n | JSON language packs, RTL-ready (IRANSans web fonts) |

---

## 🚀 Getting Started

### Prerequisites

- **PHP** 7.4 or higher
- **Web server** — Apache or Nginx
- **Database** — MySQL 5.7 or higher

### Installation

1. **Upload** the script files to your web server (under your web root).
2. **Create a database** and import the provided SQL files: `controller/setup/db.sql` and `db-update.sql`.
3. **Configure** `config.php` with your database credentials and settings.
4. **Run the installer** — open `setup.php` in your browser and complete the guided setup.

### Enable SMS notifications

1. Register on [MeliPayamak](https://www.melipayamak.com) and purchase a dedicated SMS line.
2. Enter your MeliPayamak credentials and dedicated line number in the script's SMS settings.
3. Activate SMS notifications in the settings panel.

---

## 🖼️ Screenshots

| | |
| --- | --- |
| ![Screenshot 1](public/1.png) | ![Screenshot 2](public/2.jpg) |
| ![Screenshot 3](public/3.jpg) | ![Screenshot 4](public/4.png) |

---

## 🗂️ Project Structure

```text
php-Tickets/
├── index.php             # Front controller / entry point
├── ajax.php              # Ajax request handler
├── config.php            # Database & app configuration
├── controller/           # Controllers, PHPMailer, MailChimp, setup & installer
│   └── setup/            #   db.sql, db-update.sql, web installer (setup.php)
├── models/               # Data models (tickets, users, knowledge, options) + SQL
├── views/                # Views & the themeable AH-Tickets theme (pages, assets)
├── languages/            # 12+ JSON language packs (EN, FA, AR, DE, …)
└── public/               # Public assets & screenshots
```

---

## 🤝 Contributing

Issues and suggestions are welcome via the [issue tracker](https://github.com/morpheusadam/DeskNest/issues). Please respect the licensing terms below before redistributing or modifying the script.

## 📜 License & Rights

All rights reserved for **Rastchin** and **Mahyar Ansari**. Unauthorized distribution or modification of this script is prohibited. The bundled fonts are legally purchased and licensed (license code **TY3WT**) — please respect the font licensing terms. This project also includes third-party libraries and assets (PHPMailer, Bootstrap, TinyMCE, etc.); refer to their respective licenses for details.

---

<div align="center">

### 👤 Author — Morpheus Adam

Web developer & cheerful hacker · PHP · Laravel · Go

<p>
  <a href="https://github.com/morpheusadam"><img src="https://img.shields.io/badge/GitHub-morpheusadam-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://sam.zeonic.me"><img src="https://img.shields.io/badge/Website-sam.zeonic.me-4c1?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
  <a href="mailto:morpheusadam95@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

⭐ **If this support system helped your team, consider giving it a star!** ⭐

</div>


---

## ⭐ Star History

<a href="https://star-history.com/#morpheusadam/DeskNest&Date">
  <img src="https://api.star-history.com/svg?repos=morpheusadam/DeskNest&type=Date" alt="php-Tickets — Star History Chart" width="70%" />
</a>

<div align="center">

### If this project helps you, please give it a ⭐

A star helps other developers discover **php-Tickets** and supports continued development.

</div>
