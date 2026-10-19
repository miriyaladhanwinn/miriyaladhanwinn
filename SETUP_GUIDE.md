# 🚀 GitHub Profile Setup Guide

This folder contains your complete, production-ready GitHub profile configured to match the exact aesthetic, gradient banners, typing animations, cards, and contribution snake of [Sampreeth2002](https://github.com/Sampreeth2002), tailored with your credentials, education, and projects from your resume.

---

## 📁 Files Included

- **`README.md`**: Your complete GitHub Profile README with waving header/footer banners, typing SVG, tech stack table, 2x2 experience and project showcases, GitHub analytics, and contribution graph.
- **`.github/workflows/snake.yml`**: GitHub Actions workflow to generate the contribution snake animation SVG every 24 hours.

---

## 🛠️ Step-by-Step Deployment Instructions

### Step 1: Create Your Profile Repository on GitHub
1. Go to [GitHub - New Repository](https://github.com/new).
2. Set the repository name to exactly your GitHub username: **`miriyaladhanwinn`**.
3. Make sure the repository is marked as **Public** and check **"Add a README file"**.
   *(GitHub will show a note: "You've discovered a special repository! Its README.md will appear on your public profile.")*
4. Click **Create repository**.

### Step 2: Push or Paste the Files
#### Option A: Using Git (Recommended)
From this directory:
```bash
git init
git add .
git commit -m "feat: setup animated profile readme and snake action"
git branch -M main
git remote add origin https://github.com/miriyaladhanwinn/miriyaladhanwinn.git
git push -u origin main --force
```

#### Option B: Direct Copy-Paste via Web Interface
1. Open your repository `https://github.com/miriyaladhanwinn/miriyaladhanwinn` in your browser.
2. Edit `README.md` and paste the entire contents of this `README.md`.
3. Commit the changes.
4. To enable the snake animation, create `.github/workflows/snake.yml` using the GitHub web file editor and paste the contents of `snake.yml`.

---

### Step 3: Enable GitHub Actions Workflow Permissions (For Snake Animation)
1. On GitHub, navigate to your repository **`miriyaladhanwinn/miriyaladhanwinn`**.
2. Click **Settings** (top tab) → **Actions** (left sidebar) → **General**.
3. Scroll down to **Workflow permissions**:
   - Select **Read and write permissions**.
   - Check the box **"Allow GitHub Actions to create and approve pull requests"**.
4. Click **Save**.

---

### Step 4: Run the Snake Action for the First Time
1. Click the **Actions** tab in your repository.
2. Under "All workflows" on the left, click **Generate Snake Animation**.
3. Click the **Run workflow** dropdown button on the right, select the `main` branch, and click **Run workflow**.
4. Wait ~30 seconds for the action to finish with a green checkmark.
5. It will automatically create an `output` branch containing `github-contribution-grid-snake.svg` and `github-contribution-grid-snake-dark.svg`.
6. Once completed, the snake animation on your profile page will immediately start moving!

---

### Step 5: Profile Summary Cards
The analytics section includes dynamic theme-responsive cards from `github-profile-summary-cards`.
To initialize your user card cache on their server:
- Simply visit: `https://github-profile-summary-cards.vercel.app/api/cards/stats?username=miriyaladhanwinn&theme=github_dark` once in your browser.

🎉 **All done! Refresh your GitHub profile at `https://github.com/miriyaladhanwinn` to see your new animated profile in action.**
