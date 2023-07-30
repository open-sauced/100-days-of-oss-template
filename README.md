# 100-days-of-oss-template

A journal template to help you keep up with your #100DaysOfOSS work.

## Instructions

We recommend that you use this template to keep track of your work during the challenge. You can use it as a starting point and customize it to your needs.

You will use Markdown to work on your progress. If you are not familiar with working with Markdown, you can read the docs about [Markdown's basic syntax](https://www.markdownguide.org/basic-syntax/).

You might want to create a new repository for your journal, or you can fork this repository and use it as a starting point.

### Set a Goal

Before you start, you might want to set a goal for yourself. What do you want to accomplish in the next 100 days? What do you want to learn? What do you want to build or be a part of? Declaring that in your README will help you stay focused and motivated and will help others understand what you're working on.

#### Getting Started

### Creating a New Repository Using This Template

1. Click the green "Use this template" button on the top of this repository.
2. Click the "Create new repository" from the dropdown menu.
3. Fill in the repository name and description (optional). Leave the "Include all branches" checkbox unchecked — you only want the default branch.
4. Click the green "Create repository" button.
5. Follow steps 3-9 in the [Forking This Repository](#forking-this-repository) section below to work on your OSS progress.

### Forking This Repository

1. Fork this repository by clicking the fork button on the top.
2. Clone _your forked repository_ to your local machine.

   - Go to _your forked repository_ on GitHub.
   - Click the "<> Code" button and copy the HTTPS link.
   - In your terminal on your local machine, open the directory where you want this repo to live. Then run this command:

     ```bash
     git clone <https-link>
     ```

     Paste the HTTPS link that you've copied. For example:

     ```bash
     git clone https://github.com/username/100-days-of-oss-template.git
     ```

3. Create a new file and name this file anything you want, e.g., `my-oss-journal.md`. This file will be where you update your #100DaysofOSS progress.
4. Use the `journal.md` template to record your progress — we also provide an example here. Copy and paste the template into your progress track file, and customize it to your need.
5. Create a new branch for each challenge day if you want to keep your work separate.

   - In your terminal, run this command:

     ```bash
     git checkout -b <new-branch-name>
     ```

     You can name the branch anything, e.g., `day-1`. Then the command will be:

     ```bash
     git checkout -b day-1
     ```

6. Add and commit your work to your branch.

   - In your terminal, run these commands:

     ```bash
     git add .

     git commit -m "Your commit message"
     ```

     Change the "Your commit message" with your own message. For example:

     ```bash
     git commit -m "Add day 1"
     ```

7. Push your changes to _your forked repository_.

   - In your terminal, run this command:

     ```bash
     git push -u origin <your-branch-name>
     ```

     Change the `your-branch-name` to your current branch name. For example:

     ```bash
     git push -u origin day-1
     ```

8. Create a pull request and merge your changes.
   - Go to _your forked repository_ on GitHub.
   - Click the green "Compare & pull request" button.
   - Modify the title if necessary and write the description of your changes.
   - Create a pull request by clicking the green "Create pull request" button.
   - Merge your changes into the `main` branch by clicking the green "Merge pull request" and the "Confirm merge" button.
9. Repeat steps 5-8 for each day of the challenge.

#### Tips for making the most out of #100DaysOfOSS

- Use the `table-of-contents.md` file to keep track of your work. To update the Table of Contents:

  - Go to _your forked repository_ on GitHub.
  - Open your progress track file.
  - Click on the link icon at the day's title and copy the link.
  - Paste the link in the target date in the `table-of-contents.md`.

    ```bash
    [Day 1](link-to-day-1)
    ```

    For example:

    ```bash
    [Day 1](https://github.com/username/100-days-of-oss-journal/blob/main/my-100-days-oss-journal.md#day-1)

    ```

  - Follow steps 6-8 in the [Getting Started](#getting-started) section to add, commit, push, and create a pull request to merge your changes into the `main` branch of your forked repository.

- Commit your work every day, even if you don't have time to work on it for long
- If you don't have time to work on a project, read an article, watch a video, attend an event about an OSS topic that interests you
- If you get stuck, ask for help! You can ask a friend, a mentor, or the community for help.
- If you get bored, try something new! There are so many ways to contribute to OSS. You can write code, write documentation, test software, translate content, and more.
- If you get frustrated, take a break. OSS is supposed to be fun! If you're not having fun, take a break and come back to it later.

#### Additional Resources

- [#100DaysOfOSS](https://docs.opensauced.pizza/community/100-days-of-oss/)
- [OpenSauced](https://opensauced.pizza/)
