# Getting Started with GitHub and VS Code

This guide explains how to create, publish, and collaborate on a simple documentation project using **VS Code**, **GitHub Desktop**, and **GitHub Pages**.

## 1. Set Up VS Code

If your laptop is provided by the English Department at Iowa State University, install VS Code through the **Self Help** application. If you use a personal device, download [Visual Studio Code](https://code.visualstudio.com/).

After installing VS Code, open **Extensions** and install **Markdown All in One**. Extensions add useful features to VS Code.

See the [VS Code extensions documentation](https://code.visualstudio.com/docs/configure/extensions/extension-marketplace).

## 2. Set Up GitHub and GitHub Desktop

Create a free [GitHub account](https://github.com/signup) and install [GitHub Desktop](https://desktop.github.com/). If you use a department-owned laptop, contact IT if installation help is needed.

Sign in to GitHub Desktop with the same account. GitHub stores repositories online, while GitHub Desktop provides a visual way to manage changes.

See GitHub's [Hello World tutorial](https://docs.github.com/en/get-started/using-github/hello-world).

## 3. Create and Publish a Repository

In GitHub Desktop:

1. Select **File → New Repository**.
2. Name and create the repository.
3. Click **Publish repository**.
4. Make sure it is **public**.

Open the repository in VS Code and create `index.html` at the top level. Add a link to the public repository:

```html
<a href="https://github.com/snehab-hub/solo-doc-documentation">
  Link to repository
</a>
```

Save the file.

## 4. Stage, Commit, and Push Changes

Open GitHub Desktop. Under **Changes**, select `index.html`. Enter a short commit message such as `Add index page`, then click **Commit to main** and **Push origin**.

A **commit** records a version of your work. **Pushing** sends that version to GitHub.

> Remember: commit records the change; push sends it to GitHub.

See the [GitHub Desktop commit guide](https://docs.github.com/en/desktop/making-changes-in-a-branch/committing-and-reviewing-changes-to-your-project-in-github-desktop).

## 5. Publish with GitHub Pages

On GitHub, open **Settings → Pages**. Choose **Deploy from a branch**, select `main` and `/(root)`, and click **Save**.

GitHub Pages turns `index.html` into a public website. Open the website URL and confirm that **Link to repository** appears and returns to your repository.

See the [GitHub Pages documentation](https://pages.github.com/).

## 6. Collaborate with a Pull Request

A pull request lets someone propose changes to a project without changing the main version right away.

Open **Settings → Collaborators** and invite another GitHub user. After they accept, ask them to create a branch, make a small change, commit it, and open a **pull request**.

Review the pull request, **approve** it, and **merge** it into `main`. Then use **Fetch origin** or **Pull origin** in GitHub Desktop to update your local copy.

See GitHub's [pull request documentation](https://docs.github.com/en/pull-requests).

## 7. Document Your Work

Create `readme.md` at the top level of the repository. Write beginner instructions using headings, lists, **bold text**, *italics*, links, block quotes, and code blocks.

See GitHub's [Markdown guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

Save `readme.md`, commit it with a message such as `Add project documentation`, and push it to GitHub.

## Final Check

Confirm that `index.html` and `readme.md` are in the public repository, the GitHub Pages website works, and the collaborator's pull request was merged.

Submit these two links to Canvas:

1. **Public GitHub repository**
2. **Live GitHub Pages website**