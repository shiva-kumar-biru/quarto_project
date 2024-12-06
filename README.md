# Powfacpy Documentation using Quarto Doc

Welcome to the **Powfacpy Documentation** project! This repository hosts the official documentation for the Powfacpy Python package, created using **Quarto Doc** and published on **GitHub Pages**. The documentation provides detailed information about the functionalities, installation, and usage of Powfacpy.

Explore the hosted documentation here:  
**[Powfacpy Documentation](https://shiva-kumar-biru.github.io/quarto_project/)**

---

## Project Overview

This project demonstrates how to create professional, user-friendly documentation for a Python library using Quarto, a modern publishing system. The documentation includes:  
- A comprehensive introduction to Powfacpy.  
- Installation instructions.  
- Code examples to help users understand the usage.  
- API reference for all major functionalities.  

The documentation is styled and structured for clarity, ensuring users can easily find and understand the information they need.

---

## Features

- **Dynamic and Responsive Design:** The Quarto framework ensures the documentation looks great across all devices.  
- **Markdown and Code Integration:** Combines Markdown for text with Python code snippets for examples.  
- **Easy Hosting:** Documentation is seamlessly deployed via **GitHub Pages**.  

---


## Continuous Integration and Deployment (CI/CD)

This project uses **CI/CD** practices to automate the build and deployment of the documentation. With the help of **GitHub Actions**, any updates to the repository are automatically rendered and deployed to **GitHub Pages**.

### Workflow Overview
The CI/CD pipeline performs the following steps:
1. **Checkout Repository:** Clones the latest code from the `main` branch.
2. **Install Dependencies:** Installs Quarto CLI and Python requirements.
3. **Build Documentation:** Runs the `quarto render` command to build the documentation.
4. **Deploy to GitHub Pages:** Publishes the built documentation to the `_site` directory.

You can view the workflow file here:  
**[GitHub Actions Workflow File](https://github.com/shiva-kumar-biru/quarto_project/blob/main/.github/workflows/publish.yml)**

### Benefits of CI/CD in This Project
- **Automated Updates:** Reduces manual intervention by automating the build and deployment process.  
- **Reliable Deployment:** Ensures the hosted documentation is always up-to-date.  
- **Streamlined Workflow:** Simplifies collaboration and scaling for larger projects.  

---

## How to View the Documentation

To access the live documentation:  
[**Powfacpy Documentation on GitHub Pages**](https://shiva-kumar-biru.github.io/quarto_project/)

---

## How to Set Up Locally

If you'd like to view or modify the documentation locally, follow these steps:

### Prerequisites
Ensure you have the following installed on your system:
1. **Python 3.x**  
2. **Quarto CLI** – [Install Quarto](https://quarto.org/docs/get-started/)

### Clone the Repository
```bash
git clone https://github.com/shiva-kumar-biru/quarto_project.git
cd quarto_project
```
### Install the requirements for the project 

```
pip install -r requirements.txt
```

Serve Locally
```
quarto preview

```

### Deployment to GitHub Pages
The documentation is automatically deployed to GitHub Pages. If you make updates to the documentation, follow these steps to redeploy:

1. Build the Documentation

```bash
quarto render
```
2. Commit and Push Changes

```bash

git add .
git commit -m "Updated documentation"
git push origin main
```
3. GitHub Pages will automatically update the hosted site.
