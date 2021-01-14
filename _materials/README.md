# Read-only Program Repositories
**Important**: DO NOT make any changes to the code in these repos or you might get a conflict when you `pull` fresh updates. Instead, copy files and code snippets into your own working directory (i.e. `in-class`).

## Terms
Read-only Repo
: A remote repository (on a service such as GitHub) that you do not own or have permission to change.

Repository (aka repo)
: Technically, a collection of commits, and branches and tags to identify commits. You can think of a repo as a directory of code that is tracked using Git.

Local Repository
: A repo that is located on your local machine.

Remote Repository
: A repo that is located on another machine or server. For the purposes of this course, all of your remote repos will be located on GitHub.

Clone a Repository
: A method of copying a remote repo to your local system using the `git clone` command.

## Program Repo List
This program stores course materials in multiple read-only repositories that you can `clone` into this directory. These repos will be updated by your instructor regularly.
- [assessments](https://github.com/sait-wbdv/assessments/): Program assessments, organized by course.
- [sample code](https://github.com/sait-wbdv/sample-code): A collection of starter code and activities. This is a work-in-progress.
- [instructor in-class](https://github.com/sait-wbdv/in-class): Code created during your intructor's live-coding sessions, separated by day. This code will often be messy and borken. Use at your own risk.
- [winter-2021](https://github.com/sait-wbdv/winter-2021): The program website. This may be the least important to `clone`, unless you're interested in learning Jekyll

There are others later on in the program.

## 1. Cloning 3rd-party repositores
Git makes it easy to `clone` (i.e. copy) any public repository to your machine.

1. Using the terminal, navigate to this directory.
2. In a browser, navigate to one of the above repositories you would like to clone. For example, [sample-code](https://github.com/sait-wbdv/sample-code).
3. Copy the clone URL listed under the green `Code` menu. Recommended: use the HTTPS link instead of SSH.
4. Clone the repo to your machine by entering the following terminal command:

    ```
    $ git clone https://github.com/sait-wbdv/sample-code.git
    ```

    Fancy text will fly by the screen...

5. Navigate to the new directory that Git copied to your location:

    ```
    $ cd sample-code
    ```

6. Confirm the status of your new local repo:

    ```
    $ git status
    ```

### Refreshing your local repo
Your instructor will `push` daily updates to the program repos. You can refresh your local copy by pulling new changes:

1. Using the terminal, navigate to the directory you'd like to update.

    ```
    $ cd path/to/repo
    ```

2. `pull` any new changes:

    ```
    $ git pull
    ```

The connection between your local repo and the remote repo was created when you first cloned it.
