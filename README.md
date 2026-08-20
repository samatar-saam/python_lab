### Why Developers Use Branches and Pull Requests

Developers use branches and pull requests to keep the `main` branch stable and protected while new features, fixes, and experiments are being developed. Instead of committing changes directly to `main`, a developer creates a separate branch, such as `feature/add-greeting`, and makes the changes there. This allows the developer to work independently without affecting the production-ready code in `main`.

After the work is completed, the developer pushes the feature branch to GitHub and opens a pull request into `main`. During code review, other developers examine the changes, check the code for errors or potential problems, and provide comments or suggestions. Automated tests and other checks may also run to verify that the changes work correctly. The developer can make additional commits to address review comments, and those changes automatically appear in the pull request. Once the reviewers are satisfied and all required checks pass, the pull request can be approved and merged into `main`.

Branches and pull requests therefore improve collaboration, code quality, testing, and project safety while reducing the risk of introducing broken code directly into the main branch.
