# TASK-6: Basic HTML Website

This is a static website hosted using github pages. It includes only an `index.html` file with a simple layout. The main purpose of this project is to understand:

- How to use Git and GitHub for version control
- How to manage repositories using GitHub CLI
- How to deploy static content for free
- How to host static website using github pages

## 🌐 Website Features

- Clean HTML, CSS structure
- Simple navigation using links
- Fully static and browser-friendly

---

## 💡 How This Project Was Built

### ✅ Step-by-Step Workflow

#### 1. Create a new folder for the project

```cmd
mkdir <DIR NAME>
cd <DIR NAME>
```
2. Create index.html manually using any code editor
3. Initialize a Git repository
```cmd
git init
```
4. Add and commit the file
```cmd
git add index.html
git commit -m "Add index.html file"
```
5. Create a GitHub repo using GitHub CLI
```cmd
gh repo create <DIR NAME --public --source=. --remote=origin --push
```
Make sure you’ve already run gh auth login to authenticate your GitHub account.

7. OR manually add the remote if needed
```cmd
git remote add origin https://github.com/ravisharma79/TASK-6.git
git push -u origin main
```

HOSTED WEBSITE LINK
https://ravisharma79.github.io/TASK-6/
