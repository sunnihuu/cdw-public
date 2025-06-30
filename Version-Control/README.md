# Introduction to Version Control
## Git and GitHub


Welcome to this tutorial on version control. This guide will walk you through the fundamentals of Git.

---

### 1  What is Version Control

**Version Control** (also known as Source Control or Revision Control) is a system that tracks changes to files over time, allowing you to recall specific versions later. Think of it as a "time machine" for your code.

#### Why Do We Need Version Control?

- **Backup & Recovery**: Never lose your work again
- **Collaboration**: Multiple people can work on the same project
- **History Tracking**: See who changed what and when
- **Branching**: Work on features without affecting the main code
- **Rollback**: Easily revert to previous versions if something breaks
- **Code Review**: Track changes and review code before merging

---

### 2  Git Glossary of Terms

#### Core Concepts

- **Repository (Repo)**: A directory containing your project and its version history
- **Commit**: A snapshot of your code at a specific point in time
- **Branch**: A separate line of development
- **Merge**: Combining changes from different branches
- **Clone**: Creating a local copy of a remote repository
- **Push**: Uploading local changes to a remote repository
- **Pull**: Downloading changes from a remote repository

#### Important Terms

- **Working Directory**: Where you edit files
- **Staging Area**: Where you prepare files for commit
- **HEAD**: Pointer to the current commit
- **Master/Main**: Default branch name
- **Origin**: Default name for the remote repository
- **Fork**: A copy of someone else's repository
- **Pull Request**: Request to merge changes into another repository

---

### 3  Your First Repo - Commit and Push "Hello World" file using Github Desktop

While Git can be used entirely from the command line, we'll use **GitHub Desktop** to simplify the learning process. GitHub Desktop provides a user-friendly graphical interface that makes the most common Git operations accessible without memorizing commands.

#### Why GitHub Desktop?

- **Beginner-Friendly**: Visual interface is easier to understand than command line
- **Common Operations**: Covers 90% of what you'll do with Git
- **Error Prevention**: Helps avoid common mistakes
- **Visual Feedback**: See changes, history, and branches clearly
- **Cross-Platform**: Works on Windows, Mac, and Linux
- **Free**: No cost to use

---

#### Step 1: Install GitHub Desktop

![Figma_XWf7GRywY0](https://github.com/user-attachments/assets/e7fbff1d-fc15-4c50-874f-07e06fcca13c)

1. **Download**: Go to [desktop.github.com](https://desktop.github.com/)
2. **Install**: Run the installer and follow the setup wizard
3. **Sign In**: Use your GitHub account credentials
4. **Verify**: GitHub Desktop should open and show your GitHub repositories

#### Step 2: Create Your First Repository

![Figma_htXXlucwQQ](https://github.com/user-attachments/assets/1402b64a-d441-436d-b8e4-5b9616552c6a)

![Figma_Wl1nbWzn73](https://github.com/user-attachments/assets/3a627ee9-fd34-41eb-a0db-63c97b720ebe)

1. **Open GitHub Desktop**
2. **Click**: "File" → "New Repository" (or press Ctrl+N)
3. **Fill in the details**:
   - **Name**: `my-first-repo`
   - **Description**: `My first Git repository using GitHub Desktop`
   - **Local path**: Choose where to save on your computer
   - **Check**: "Initialize this repository with a README"
   - **Git ignore**: Select "None" for now
   - **License**: Choose "MIT License" (common for open source)
4. **Click**: "Create Repository"

#### Step 3: Create Your "Hello World" File

![Figma_wUVmoC17uJ](https://github.com/user-attachments/assets/525d27f1-b7bb-4dba-a2c3-06331a33fe82)

![Figma_7NHo4luSfv](https://github.com/user-attachments/assets/db290596-db12-421f-a3a3-39a404cdc0ea)

1. **In GitHub Desktop**: Click "Show in Explorer" (Windows) or "Show in Finder" (Mac)
2. **Create a new file**: Right-click → New → Text Document
3. **Name it**: `hello-world.txt`
4. **Open the file** in any text editor (Notepad, VS Code, etc.)
5. **Add this simple text**:
```
Hello, World.

```
6. **Save the file**

#### Step 4: Make Your First Commit

![Figma_5taF7eV99B](https://github.com/user-attachments/assets/d834bf60-3943-47c2-8aa6-341e50902151)

1. **Return to GitHub Desktop**
2. **You'll see**: Your new `hello-world.txt` file in the "Changes" tab
3. **Add a commit message**: 
   - **Summary**: `Add Hello World text file`
   - **Description**: `Created a simple text file to demonstrate my first Git repository`
4. **Click**: "Commit to main"

#### Step 5: Push to GitHub

![Figma_NkesT2lGXD](https://github.com/user-attachments/assets/4575b33e-417b-477d-9ec3-cd0c491dcbf0)

1. **In GitHub Desktop**: Click "Push origin" button
2. **Wait**: GitHub Desktop will upload your files
3. **Success**: You'll see "Successfully pushed to GitHub"

#### Step 6: Make your Repo Public

![Figma_0OT6fkv5LZ](https://github.com/user-attachments/assets/a083cc31-296f-4bbb-985a-88ffb6e5c523)

![Figma_8lco2Kc1xF](https://github.com/user-attachments/assets/4c45db97-d862-4453-a4cd-f37f80b7c9a7)

1. **In GitHub**: Click on Settings
2. **In GitHub**: Navigate to the "Danger Zone"
3. **In GitHub**: Change visibility to public


#### Step 7: Verify Your Success

![Figma_WxgMAoxRi2](https://github.com/user-attachments/assets/53a25482-9906-4eaa-abd5-d273e145980e)

1. **Click**: "View on GitHub" button in GitHub Desktop
2. **You should see**: Your repository on GitHub with the `hello-world.txt` file
3. **Click on the file**: To view its contents
4. **Optional**: Enable GitHub Pages to make your site live:
   - Go to "Settings" → "Pages"
   - Select "Deploy from a branch"
   - Choose "main" branch
   - Click "Save"
   - Your site will be available at: `https://YOUR_USERNAME.github.io/my-first-repo/`


#### Step 8: Activate GitHub Pages (Website Hosting)

![Figma_NecU2Khp30](https://github.com/user-attachments/assets/e5790643-c31d-4180-99f0-99193bfa40d8)

1. **In GitHub**: Enable GitHub Pages to make your site live
2. **In GitHub**: Go to "Settings" → "Pages"
3. **In GitHub**: Select "Deploy from a branch"
4. **In GitHub**: Choose "main" branch
5. **In GitHub**: Click "Save"
6. **In GitHub**: Your site will be available at: https://YOUR_USERNAME.github.io/my-first-repo/

#### For user name use: YOUR_USERNAME.github.io
---


