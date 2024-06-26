# PLPBasicGitAssignment
Let's walk through the steps to complete this assignment. Here's a detailed guide to help you:

## Task 1: Repository Setup

### 1. GitHub Repository Creation

- **Log in to GitHub**:
  Go to [GitHub](https://github.com) and log in to your account.

- **Create a New Repository**:
  - Click the "+" icon in the top right corner and select "New repository".
  - Name your repository "PLPBasicGitAssignment".
  - Initialize it with a README file.
  - Click "Create repository".

## Task 2: Local Setup

### 2. Local Folder Setup

- **Create a New Folder**:
  - Create a folder on your local machine named "PLPBasicGitAssignment".

- **Open Terminal**:
  - Navigate to the folder in your terminal or command prompt.
  ```sh
  cd path/to/PLPBasicGitAssignment
  ```

### 3. Git Initialization

- **Initialize Git**:
  - Initialize a new Git repository in your local folder.
  ```sh
  git init
  ```

### 4. Connecting to GitHub

- **Link Local Repository to GitHub**:
  - Add the GitHub repository as a remote.
  ```sh
  git remote add origin https://github.com/YourUsername/PLPBasicGitAssignment.git
  ```

Replace `YourUsername` with your actual GitHub username.

## Task 3: Making Changes

### 5. Create a File

- **Create `hello.txt`**:
  - Inside your local folder, create a new text file named `hello.txt`.
  - Add the text "Hello, Git!" to the file.

### 6. Committing Changes

- **Stage the Changes**:
  - Stage the new file for commit.
  ```sh
  git add hello.txt
  ```

- **Commit the Changes**:
  - Commit the changes with a message.
  ```sh
  git commit -m "Add hello.txt with a greeting"
  ```

## Task 4: Pushing to GitHub

### 7. Pushing to GitHub

- **Push the Changes**:
  - Push the committed changes to your GitHub repository.
  ```sh
  git push -u origin main
  ```

## Task 5: Verification

### 8. Verify on GitHub

- **Check GitHub**:
  - Visit your GitHub repository in a web browser.
  - Verify that the `hello.txt` file and commit message are visible.

## Submission

- **Ensure All Changes are Pushed**:
  - Make sure all your changes have been pushed to the GitHub repository.

- **Share the Link**:
  - Provide the link to your GitHub repository to your instructor or submit it as per the class instructions.

## Additional Tips

- **Document Steps**:
  - Document all the steps and commands you used in a text file or the README of your repository.

- **Seek Assistance**:
  - If you encounter issues, refer to the [GitHub documentation](https://docs.github.com/en) or seek assistance from peers or your instructor.

Here's a summary of the commands you'll use:

```sh
# Navigate to your project folder
cd path/to/PLPBasicGitAssignment

# Initialize Git repository
git init

# Link to GitHub repository
git remote add origin https://github.com/YourUsername/PLPBasicGitAssignment.git

# Create and edit hello.txt
echo "Hello, Git!" > hello.txt

# Stage the file
git add hello.txt

# Commit the changes
git commit -m "Add hello.txt with a greeting"

# Push to GitHub
git push -u origin main
```

Replace `path/to/PLPBasicGitAssignment` with the actual path to your folder and `YourUsername` with your GitHub username. This should complete your assignment. 
