
# 🏥 CarePoint — Hospital Management System

A responsive, browser-based Hospital Management System built using **HTML, CSS, and JavaScript**. CarePoint provides a simple interface for managing patient records, doctor information, appointments, and billing.

---

## 📌 Project Overview

CarePoint is a front-end web application developed to demonstrate the basic workflow of hospital administration. It provides a centralized dashboard where users can register patients, maintain a doctor directory, schedule appointments, and manage invoices.

The project uses browser `localStorage` to retain demo records between page reloads.

### 🎯 Objectives

- Simplify basic hospital administration workflows.
- Provide an easy-to-use and responsive interface.
- Demonstrate front-end development fundamentals.
- Practice Git version control and GitHub collaboration.
- Deploy a static website using GitHub Pages.

---

## ✨ Features

### 📊 Dashboard
- Overview of patients, doctors, and appointments.
- Paid revenue summary.
- Hospital activity overview.

### 👥 Patient Management
- Register new patients.
- Store patient name, age, gender, and contact number.
- Search patient records.
- Delete patient records.

### 🩺 Doctor Management
- Add doctor profiles.
- Maintain specialization and contact details.
- View the doctor directory.

### 📅 Appointment Management
- Book appointments for registered patients.
- Select doctors, dates, and times.
- View appointment records.
- Remove appointments.

### 💳 Billing Management
- Generate patient invoices.
- Record billing amounts.
- Track unpaid and paid invoices.
- Calculate collected revenue.

### 📱 Responsive Design
- Responsive layout for desktop and mobile devices.
- Navigation between application modules.
- Simple dashboard and table layouts.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Styling and responsive design |
| JavaScript | Application logic and interactions |
| localStorage | Browser-based demo data persistence |
| Git | Version control |
| GitHub | Source code hosting and collaboration |
| GitHub Pages | Static website deployment |

---

## 📂 Project Structure

```text
hospital-management-system/
│
├── index.html       # HTML, CSS and JavaScript
├── README.md        # Project documentation
└── LICENSE          # Optional open-source license
```

All application code is contained in a single `index.html` file.

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser.
- Git (optional for local version control).
- A GitHub account for hosting.

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/hospital-management-system.git
```

### 2. Open the Project

```bash
cd hospital-management-system
```

Open `index.html` in your browser.

Alternatively, open the folder in Visual Studio Code and use the Live Server extension.

### 3. Make Changes

Edit `index.html` to customize the interface, features, styling, or functionality.

---

## 🔄 Git & GitHub Workflow

The following workflow explains how to develop, track, and publish changes to the project.

### Step 1: Configure Git

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

### Step 2: Initialize Git

If the project is not already a Git repository:

```bash
git init
git add .
git commit -m "Initial commit: CarePoint HMS"
```

### Step 3: Connect GitHub Repository

Create a repository on GitHub, then connect it:

```bash
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/hospital-management-system.git
git push -u origin main
```

If you cloned the repository from GitHub, you do not need to initialize it or add the remote again.

### Step 4: Create a Feature Branch

Create a separate branch before working on a new feature.

```bash
git switch -c feature/patient-management
```

### Step 5: Develop and Track Changes

After editing the code:

```bash
git status
git diff
git add index.html
git commit -m "Add patient management functionality"
```

### Step 6: Push Your Branch

```bash
git push -u origin feature/patient-management
```

### Step 7: Create a Pull Request

1. Open the repository on GitHub.
2. Select **Compare & pull request**.
3. Set the base branch to `main`.
4. Add a clear title and description.
5. Review and merge the pull request after approval.

For a solo project, you can review your own pull request before merging.

### Step 8: Update the Main Branch

After the pull request is merged:

```bash
git switch main
git pull origin main
```

### Step 9: Deploy with GitHub Pages

1. Open repository **Settings**.
2. Select **Pages**.
3. Choose **Deploy from a branch**.
4. Select `main` and `/(root)`.
5. Save and wait for deployment.

Future commits pushed to the configured branch will trigger a GitHub Pages deployment.

---

## 🌿 Recommended Branching Strategy

| Branch | Purpose |
|---|---|
| `main` | Stable, deployable version |
| `feature/patient-management` | Patient-related features |
| `feature/doctor-management` | Doctor directory |
| `feature/appointments` | Appointment workflows |
| `feature/billing` | Billing functionality |
| `fix/ui-bugs` | Bug fixes and UI corrections |

Create branches only when needed. For a small project, keeping `main` and one feature branch at a time is sufficient.

---

## 👨‍💻 Contributors

### Project Developer

**Phanendra Sana**

- Project design and implementation
- Front-end development
- Patient and doctor management modules
- Appointment and billing functionality
- Git version control and GitHub deployment
- Project documentation

### Contribution Guidelines

Contributions are welcome!

1. Fork the repository.
2. Create a feature branch.
3. Implement your changes.
4. Test the application in a browser.
5. Commit your changes with a descriptive message.
6. Push your branch to GitHub.
7. Open a pull request describing your changes.

Example:

```bash
git switch -c feature/new-dashboard
git add .
git commit -m "Improve dashboard layout"
git push -u origin feature/new-dashboard
```

Only add contributors who have actually contributed to the project.

---

## 🧪 Testing Checklist

- [ ] Register a patient.
- [ ] Search patient records.
- [ ] Add a doctor.
- [ ] Book an appointment.
- [ ] Generate an invoice.
- [ ] Mark an invoice as paid.
- [ ] Verify dashboard statistics.
- [ ] Check the layout on mobile and desktop.
- [ ] Refresh the browser and verify demo data persistence.
- [ ] Verify the deployed GitHub Pages website.

---

## ⚠️ Limitations & Security

This is an educational front-end demonstration, not a production-ready hospital information system.

- Data is stored in the current browser's `localStorage`.
- Records are not synchronized across users or devices.
- There is no authentication, authorization, or server-side database.
- Browser storage is not encrypted by this application.
- Deleting a record may leave related records referring to it.
- No real payment gateway or medical-record system is integrated.

**Do not enter real patient information or sensitive medical data.**

A production version would require a secure backend, database, authentication, access controls, audit logs, backups, and appropriate privacy and security safeguards.

---

## 🔮 Future Enhancements

- Backend integration using Spring Boot or Node.js.
- MySQL or PostgreSQL database.
- Secure login for administrators, doctors, and receptionists.
- Patient medical history and prescriptions.
- Appointment availability and conflict checking.
- PDF invoice generation.
- Email and appointment notifications.
- Automated testing and CI/CD workflows.
- Role-based permissions and audit logs.

---

## 📜 License

This project is available for educational and portfolio purposes.

If you intend to publish it as an open-source project, consider adding an appropriate license file, such as the MIT License, after deciding the terms under which others may use and distribute your code.

---

## 🙌 Acknowledgements

Built as a learning project to practice front-end web development, version control, repository management, and static website deployment using GitHub Pages.

**CarePoint — Simplifying Hospital Administration.**
