I don't have access to the settings and was wondering if there was a role change setting. 
I looked online and there seems to be a functionn to change permisions possibly giving us access to become admins.
The reason I wanted to access settings is to be able to access GitHub Pages which can be useful for creating a webpage.
I did some research and saw it would be easy to push and pull using it this way.
I am open to any other ideas but thought this would at least be a good start.

CHANGING PERMISSIONS INSTRUCTIONS 

On GitHub, navigate to the main page of the repository.
Under your repository name, click  Settings. If you cannot see the "Settings" tab, select the  dropdown menu, then click Settings.
The "Settings" tab is highlighted by a dark orange outline.
In the "Access" section of the sidebar, click  Collaborators & teams.
Under "Manage access", next to the team or person whose role you'd like to change, select the Role dropdown menu, and click a new role.


GITHUB PAGES INSTRUCTIONS

In the upper-right corner of any page, select , then click New repository.

The menu item "New repository" is outlined in dark orange.
Use the Owner dropdown menu to select the account you want to own the repository.

The menu shows two options, octocat and github.
Type a name for your repository and an optional description. If you're creating a user or organization site, your repository must be named <user>.github.io or <organization>.github.io. 
If your user or organization name contains uppercase letters, you must lowercase the letters. For more information, see "About GitHub Pages."

The repository name field contains the text "octocat.github.io" and is outlined in dark orange.
Choose a repository visibility. For more information, see "About repositories."

Select Initialize this repository with a README.

Click Create repository.

Creating your site
Before you can create your site, you must have a repository for your site on GitHub. If you're not creating your site in an existing repository, see "Creating a repository for your site."

Warning: GitHub Pages sites are publicly available on the internet, even if the repository for the site is private (if your plan or organization allows it). 
If you have sensitive data in your site's repository, you may want to remove the data before publishing. For more information, see "About repositories."

On GitHub, navigate to your site's repository.

Decide which publishing source you want to use. For more information, see "Configuring a publishing source for your GitHub Pages site."

Create the entry file for your site. GitHub Pages will look for an index.html, index.md, or README.md file as the entry file for your site.

If your publishing source is a branch and folder, the entry file must be at the top level of the source folder on the source branch. 
For example, if your publishing source is the /docs folder on the main branch, your entry file must be located in the /docs folder on a branch called main.

If your publishing source is a GitHub Actions workflow, the artifact that you deploy must include the entry file at the top level of the artifact. 
Instead of adding the entry file to your repository, you may choose to have your GitHub Actions workflow generate your entry file when the workflow runs.

Configure your publishing source. For more information, see "Configuring a publishing source for your GitHub Pages site."

Under your repository name, click  Settings. If you cannot see the "Settings" tab, select the  dropdown menu, then click Settings.

The "Settings" tab is highlighted by a dark orange outline.
In the "Code and automation" section of the sidebar, click  Pages.

To see your published site, under "GitHub Pages", click  Visit site.
