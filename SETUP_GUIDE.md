# 🚀 How to Set Up Your GitHub Profile README

To make this README show up on your public GitHub profile (`https://github.com/upasanaX`), follow these simple steps:

### Option 1: Via GitHub Web Interface (Easiest & Fastest ~ 1 Minute)

1. Open [GitHub New Repository](https://github.com/new).
2. Set the **Repository name** to exactly: `upasanaX`
   *(GitHub will show a special banner: "✨ You found a secret! upasanaX/upasanaX is a special repository that you can use to add a README.md to your GitHub profile.")*
3. Make sure the repository is set to **Public**.
4. Check **Add a README file**.
5. Click **Create repository**.
6. Open the newly created `README.md`, click the edit pencil icon, paste the entire content from `github-profile-readme/README.md`, and click **Commit changes**!

---

### Option 2: Via Git Command Line / Terminal

Run these commands in your terminal:

```bash
cd C:\Users\upasa\.gemini\antigravity-ide\scratch\github-profile-readme
git init
git add .
git commit -m "feat: initial profile readme with animations, projects and tech stack"
git branch -M main
git remote add origin https://github.com/upasanaX/upasanaX.git
git push -u origin main
```

*(Note: If you haven't created the repository on GitHub yet, create the empty public repository `upasanaX` on GitHub first, then run the commands above).*

---

### 🐍 Enabling the Animated Contribution Snake

The repository includes `.github/workflows/snake.yml`.
To enable automatic daily updates for your contribution snake:
1. Go to your `upasanaX` repository on GitHub.
2. Click **Settings** → **Actions** → **General**.
3. Under **Workflow permissions**, select **Read and write permissions** and click **Save**.
4. Go to the **Actions** tab, select **Generate Contribution Snake**, and click **Run workflow**.
5. Once it finishes, your snake will automatically eat your real contribution squares!
