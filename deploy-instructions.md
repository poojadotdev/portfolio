# GitHub Deployment Instructions

## After creating your GitHub repository, run these commands:

```bash
# Add your GitHub repository as remote (replace YOUR_USERNAME and REPO_NAME)
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git

# Push your code to GitHub
git branch -M main
git push -u origin main
```

## Enable GitHub Pages:

1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll down to **Pages** section (left sidebar)
4. Under **Source**, select **"Deploy from a branch"**
5. Choose **"main"** branch and **"/ (root)"** folder
6. Click **Save**

Your site will be live at: `https://YOUR_USERNAME.github.io/REPO_NAME`

## Add Your Photos:

Replace these placeholder files with your actual photos:
- `images/profile-photo.jpg` - Your professional headshot
- `images/aws-internship.jpg` - Your AWS office photo (already provided)
- `images/microsoft-office.jpg` - Your Microsoft office photo
- `images/sairs-research-presentation.jpg` - You presenting at SAIRS
- `images/sairs-conference-group.jpg` - SAIRS group photo
- `images/impact-labs-fellows.jpg` - Impact Labs group photo

## Update Portfolio Content:

1. Replace placeholder links in contact section
2. Add your resume as `resume.pdf`
3. Update any remaining `[Your Name]` placeholders

## Future Updates:

When you make changes:
```bash
git add .
git commit -m "Update portfolio content"
git push
```

Changes will automatically deploy to your live site!