# 🤝 Quickstart Guide

1. **Fork or Use Template** – Click **[here](https://github.com/new?template_name=octo-stats&template_owner=nishant-sheoran)** to create a new repository from this template.
2. **Set Up Personal Access Token (PAT)** – Generate a PAT with `repo` and `workflow` permissions and add it as a secret (`GHT`) in your repository.
3. **Enable Workflow Permissions** – Grant "Read and Write" access to GitHub Actions in **Repository Settings > Actions > General**.
4. **Trigger Workflow** – Manually run the workflow from the **Actions** tab or let it execute on schedule.
5. **Embed in README** – Add generated SVGs to your README for a dynamic GitHub profile.

---

# 🔍 Octo-Stats

**Octo-Stats** is a **GitHub template repository** that automates the generation and updating of **GitHub statistics** for your profile using **GitHub Actions**.

This repo includes **pre-tested workflows** from various open-source projects, ensuring **efficiency and minimal errors** in setting up dynamic profile stats.

## ✨ Features  
✅ **Pre-configured GitHub Actions** – Automate fetching and updating GitHub stats effortlessly.  
✅ **Easy Integration** – Copy the template, set up your profile, and enjoy automated updates.  
✅ **Dynamic Display** – Your stats refresh automatically on a scheduled cron job. ⏳  
✅ **Optimized Workflows** – Curated workflows tested for efficiency and reliability. 💡  

---  

## 📌 Example SVG Stats  
Explore the stats that this template can generate:  

🔗 *For themes and customization, visit linked repositories below*  

🖥️ **[GitHub Stats](https://github.com/yogeshwaran01/github-stats-terminal-style)**  

![GitHub Stats](github_stats.svg)  

🕹️ **[3D Contribution Graph](https://github.com/yoshi389111/github-profile-3d-contrib)**  

![3D Contribution Graph](profile-3d-contrib/profile-night-green.svg)  

🐍 **[Snake Contribution Graph](https://github.com/Platane/snk)**  

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="dist/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="dist/github-snake.svg" />
    <img alt="GitHub Snake Animation" src="dist/github-snake.svg" />
  </picture>
</div>

---  

## 🔑 Authentication & Permissions  
To allow GitHub Actions to commit and push changes, follow these steps:

### 📝 Setting Up Personal Access Token (PAT)  
1️⃣ Go to **Settings** → **Developer settings** → **Personal access tokens**.  
2️⃣ Click on **Generate a new token (classic)**.  
3️⃣ Select the required scopes:  
   - ✅ `repo` → Full control of private repositories.  
   - ✅ `workflow` → Allows GitHub Actions to trigger workflows.
 
**⚠️ Important:** Copy the token as it will disappear once you leave the page.  

### 🔒 Adding the Token as a Secret  
1️⃣ Go to **Repository Settings** → **Secrets and Variables** → **Actions**.  
2️⃣ Click **New Repository Secret**.  
3️⃣ Name it **GHT** and paste the copied PAT in the input box.  
4️⃣ Save it.  

**⚠️ Security Tip:** Never expose your PAT publicly. Store it securely as it grants repo modification permissions.  

### ⚙️ Grant Workflow Permissions  
1️⃣ Go to your **GitHub Repository Settings**.  
2️⃣ Navigate to **Actions** under **Code and Automation**.  
3️⃣ Select **General** from the dropdown.  
4️⃣ Scroll down to **Workflow Permissions**.  
5️⃣ Choose **Read and write permissions**.  
6️⃣ Save the settings. ✅  

---  

## ▶️ Running Workflows  
🎯 **Manual Execution**  
1️⃣ Navigate to the **Actions** tab in your repository.  
2️⃣ Under **All Workflows**, select the `.yml` file you want to run.  
3️⃣ Click **Run Workflow** to manually trigger the workflow for testing.  

⏳ **Automated Execution**  
The workflows are scheduled to run **automatically at defined UTC times**.  
After a successful run, your generated files can be embedded into your **README** file. 📄  

---   

## 📩 Contact  
For issues or feature requests, please **[open an issue](https://github.com/nishant-sheoran/octo-stats/issues/new?template=Blank+issue)** on GitHub. 🚀  

---  
_This repository is actively used for personal GitHub profile updates and is now shared with the community to simplify the setup process for others._ 🎉  


