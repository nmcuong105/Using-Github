# Using-Github

# 1. About Github pages
- You can use GitHub Pages to host a website about yourself, your organization, or your project directly from a GitHub repository.
- There are three types of GitHub Pages sites: project, user, and organization. Project sites are connected to a specific project hosted on GitHub, such as a JavaScript library or a recipe collection. User and organization sites are connected to a specific GitHub account.
- You can only create one user or organization site for each account on GitHub. Project sites, whether owned by an organization or a user account, are unlimited.
- The publishing source for your GitHub Pages site is the branch and folder where the source files for your site are stored.
- GitHub Pages publishes any static files that you push to your repository. You can create your own static files or use a static site generator to build your site for you.
- Published GitHub Pages sites may be no larger than 1 GB.
- GitHub Pages sites have a soft bandwidth limit of 100GB per month.
- GitHub Pages sites have a soft limit of 10 builds per hour.

# 2. Creating a Github Pages site
- Create a Github account: https://github.com/ 
- Creating a repository for your site: In the upper-right corner of any page, use the + drop-down menu, and select New repository.

# 3. Interacting with your repository
- Download and install Github Desktop : https://desktop.github.com/
- Clone the repository
- Commit & Publish: Enter the repository, commit your changes, and press the publish button. 

# 4. Creating a Branch
- Branching lets you work on different versions of a repository at one time. By default, our branch is main. When we create a branch off of main, we are making a copy of main at that point in time. If someone else made changes to the main branch while you were working on your branch, you could pull in those updates. Here is the diagram that shows:
  - Main branch 
  - A new branch called feature branch is created 
  - The journey that feature goes through before it’s merged into main

 ![Branch](/images/1.png)

- To create a new branch on the GitHub website, 
  1. Go to your repository.
  2. Click the drop-down at the top of the file list that says branch: master.
  3. Type your   branch name to create a new branch
  4. Select the blue Create branch box or hit “Enter” on your keyboard.

# 5. Operations

a. Commit Command:
  - Thiss option saves the changes of file
	- Maintain the history of changes

b. Pull request:
  - Tells the changes done in the file and request other contributors to view it
  - Contributors can review changes and add comments
  
c. Merge pull request:
  - Then, It merges the changes into the main master branch

# 6. Forking
  - Why forking?
    - We may need some code which is present in a public repository, under our repository and GitHub account. For this, we need to fork a repository.
  - Reminder before starting with forking
    - Changes done to the original repository will be reflected back to the forked repository.
    - However, if there is  a change in forked repository, it will not be reflected to the original repository until and unless a pull request has been made.
  - Steps:
    - Go to Explore(on top of the page)  and search for public repositories.
    - Click “fork”. There is an example in the below:
    
     ![Fork](/images/2.png)

Here, this “tangent” repository is already forked 27 times and it is under “google” account. When you click on “Fork”, it will take some time to fork the repository. Once done you will notice that the repository name is under your account.

 ![Forked](/images/3.png)
 
An existing repository under your own account has been forked successfully.

# 7. Project management
  - Visualize all of your work and prioritize it right alongside your code with projects boards. See what tasks are planned or in-progress, either in a repository or across your organization.
  - Organize projects by status: Sort tasks into columns by status. You can label columns with status indicators like “In Progress,” “Up Next,” or “One Light Year from Now”.
  - Add tasks to columns: There are a few ways to add your team’s to-dos to a column. Write notes on your tasks or search existing issues and pull requests, then add them as cards.
  - Share work: Each card has a unique URL, making it easy to share and discuss individual tasks with your team. If a note needs next steps, convert it into an issue from your project board.
  - See project activity: The activity view helps you keep track of everything happening in your team’s project and see exactly what‘s changed since the last time you looked.
  
  ![Example of Project Management](/images/4.PNG)
