# 🎭 Playwright Automation Lab

A personal test automation project where I practice building reliable end-to-end tests using **Playwright** and **TypeScript**.

This repository is my hands-on playground for improving my automation testing skills, experimenting with Playwright features, and applying QA automation best practices.

## 🛠 Tech Stack

* **Playwright**
* **TypeScript**
* **Node.js**
* **npm**
* **Git & GitHub**

## 📁 Project Structure

```text
playwright-automation-lab/
│
├── tests/                 # Automated test scenarios
├── pages/                 # Page Object Model classes
├── fixtures/              # Test fixtures and reusable setup
├── utils/                 # Helper functions and utilities
├── test-data/             # Test data
│
├── playwright.config.ts   # Playwright configuration
├── package.json
├── tsconfig.json
└── README.md
```

> The project structure may evolve as I add new test scenarios and experiment with different automation patterns.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd playwright-automation-lab
```

### 2. Install dependencies

```bash
npm install
```

### 3. Install Playwright browsers

```bash
npx playwright install
```

### 4. Run the tests

```bash
npx playwright test
```

## 🧪 Useful Commands

Run all tests:

```bash
npx playwright test
```

Run tests in headed mode:

```bash
npx playwright test --headed
```

Run tests using Playwright UI Mode:

```bash
npx playwright test --ui
```

Run a specific test:

```bash
npx playwright test tests/example.spec.ts
```

Run tests in debug mode:

```bash
npx playwright test --debug
```

View the HTML report:

```bash
npx playwright show-report
```

## 🎯 What I'm Practicing

This project is focused on developing practical automation testing skills, including:

* Writing end-to-end test scenarios
* Creating readable and maintainable test suites
* Using Playwright locators and assertions
* Working with multiple browsers
* Page Object Model (POM)
* Test fixtures
* Reusable helper functions
* Test data management
* Handling waits and asynchronous behavior
* API testing with Playwright
* Authentication and session handling
* Screenshots, traces, and debugging
* Test reporting
* CI/CD integration
* Writing clean TypeScript for automation

## 🌐 Cross-Browser Testing

Playwright allows tests to run across multiple browser engines:

```bash
npx playwright test --project=chromium
npx playwright test --project=firefox
npx playwright test --project=webkit
```

## 📊 Test Reports

After running the test suite, the Playwright HTML report can be opened with:

```bash
npx playwright show-report
```

Reports make it easier to inspect passed and failed tests, screenshots, traces, and other debugging information.

## 🔄 Continuous Improvement

This repository is a learning project and will continue to evolve as I explore more advanced automation concepts.

Some areas I plan to practice include:

* Advanced Page Object Model patterns
* API + UI test combinations
* Data-driven testing
* Visual testing
* Network mocking
* CI/CD with GitHub Actions
* Parallel test execution
* Test tagging and test organization
* Advanced Playwright fixtures

## 💡 About This Project

The goal of this repository is not just to write tests that pass.

I'm using it to practice designing automation that is:

**Readable · Maintainable · Reliable · Scalable**

As I continue learning, I'll refactor existing tests, experiment with different approaches, and document useful patterns along the way.

## 👩‍💻 Author Pelin Sophie Gursoy

Created as part of my journey in **QA Automation Engineering** and continuous practice with **Playwright + TypeScript**.

---

⭐ This repository is continuously updated as I learn and experiment with new automation techniques.
