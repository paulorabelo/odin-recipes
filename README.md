# Odin Recipes Project

This is my first project from The Odin Project, focused on building a basic recipes website using only pure HTML. This project serves as an introductory exercise to practice the fundamental structure of web pages and the initial workflow with Git and GitHub.

## Learning and Technologies Used

In this initial phase of the project, I focused on practicing and understanding the following concepts and tools:

* **GitHub Repository Creation:** Learned how to initialize a new repository (`odin-recipes`) on the GitHub platform to host my project's code in the cloud.
* **Cloning Repository via SSH:** Utilized the SSH protocol to clone the repository to my local machine. This involved:
    * Generating SSH keys (public and private).
    * Adding the public key to my GitHub account.
    * Using the SSH address (`git@github.com:your-username/odin-recipes.git`) to clone the repository securely and authenticated.
* **Basic HTML Structure:** Started creating the first HTML pages, including the main page (`index.html`) and separate pages for a few recipes.
* **Using VS Code:** Used Visual Studio Code as my main code editor. Learned to:
    * Create and edit files (`.html`, `.md`).
    * Use the integrated terminal for Git commands.
    * Perform commits and synchronize (push/pull) changes with the GitHub repository directly through VS Code (using the Source Control interface).
* **Basic Git Workflow:** Practiced the basic cycle of adding files (`git add`), committing changes (`git commit`), and pushing to the remote repository (`git push`).

## Project Structure

The project follows a simple structure:

odin-recipes/
├── README.md
├── index.html
└── recipes/
├── recipe1.html
├── recipe2.html
└── recipe3.html

* `index.html`: The main page with links to the recipes.
* `recipes/`: Directory containing the HTML files for each individual recipe.
* `README.md`: This file, describing the project and the development process.

## How to View

1.  Clone the repository to your local machine (if you haven't already):
    ```bash
    git clone git@github.com:paulorabelo/odin-recipes.git
    ```    
2.  Navigate into the project folder:
    ```bash
    cd odin-recipes
    ```
3.  Open the `index.html` file directly in your web browser.

---

This README will be updated as the project evolves and new technologies (like CSS!) are incorporated.