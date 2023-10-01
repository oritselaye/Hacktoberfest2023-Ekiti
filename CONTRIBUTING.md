# Send PR directly on Github

1. Fork the repository: forking a repository creates a copy of the repository on your accoount. This allows you to freely experiment changes without affecting the main repository.

![fork](https://github.com/Elijah699/Hacktoberfest2023-Ekiti/assets/66225920/f6ecaa01-1fa5-4859-b339-7710513197f2)


After clicking the fork button in the image above, you'll complete the forking process by clicking the create fork button

![fork 1](https://github.com/Elijah699/Hacktoberfest2023-Ekiti/assets/66225920/05e31c17-f4d6-4a8b-b362-afb6cb4edece)


2. Create a branch of yours to make your contributions: creating a branch allows you to separate your changes from the main branch which can later be added to the main branch if there is no error or conflict. Else, discarded.

![branch](https://github.com/Elijah699/Hacktoberfest2023-Ekiti/assets/66225920/81897745-9ace-42d9-baf8-05699ce0619b)

Input the name of your branch and then click "Create branch: branch-name" slightly below the branch name input area

3. When you are done creating the branch, you can start making your contributions.

![make-changes](https://github.com/Elijah699/Hacktoberfest2023-Ekiti/assets/66225920/70f30266-2ed3-4027-9964-d509cbad79c4)


4. When you're done making your contribution, compare & pull request

![compare and pull request](https://github.com/Elijah699/Hacktoberfest2023-Ekiti/assets/66225920/dd7c74a5-978f-4491-8201-5239715337f8)

5. Finally, send your pull request.
   You can also leave a comment to explain your contribution.

![pull request](https://github.com/Elijah699/Hacktoberfest2023-Ekiti/assets/66225920/b39bf955-bd41-4912-9044-d1ecb9e61c62)


# Send PR with git

1. Fork the repository as in the first step above

2. Clone the forked repository to your local machine

```markdown
git clone https://github.com/OSCA-Ado-Ekiti/Hacktoberfest2023-Ekiti.git
```

3. Navigate to the cloned directory

```markdown
cd Hacktoberfest2023-Ekiti
```

4. Create a branch

```markdown
git checkout -b branch_name (Creates and switches to the new branch created)
```

5. Make your contributions

6. Add, commit and push changes

```markdown
git add file_name (use . to add every files and folders in the directory)
git commit -m 'commit message'
git push origin branch_name
```

If you are having any dificulty, check this article: [https://codesandbox.io/post/how-to-make-your-first-open-source-contribution](https://codesandbox.io/post/how-to-make-your-first-open-source-contribution)
