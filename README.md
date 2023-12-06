# Python Pre-commit Checks

This repository contains a simple Python script to add two numbers, along with pre-commit checks to ensure code quality.

## Project Structure

- `source`: Contains the Python script.
- `.github`: Holds GitHub workflows.
  - `workflows`: GitHub Actions workflow files.
- `.pre-commit-config.yaml`: Configuration file for pre-commit hooks.
- `CODEOWNERS`: Specifies my own account for code review.

## Usage

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/shibam-max/python-precommit-checks.git
    cd python-precommit-checks
    ```

2. **Run the Python Script:**

    Open the `source/add_numbers.py` file to view and modify the numbers. Then, run the script:

    ```bash
    python source/add_numbers.py
    ```

3. **Update Python Script (Optional):**

    If you want to modify the Python script, open `source/add_numbers.py`, make your changes, and save the file.

4. **Pre-commit Checks:**

    Before committing your changes, make sure to run the pre-commit checks. Ensure you have `pre-commit` installed:

    ```bash
    pip install pre-commit
    ```

    Run the pre-commit checks:

    ```bash
    pre-commit run --all-files
    ```

    This will automatically check and format the code according to the defined standards.

5. **Add, Commit, and Push:**

    After verifying that the pre-commit checks passed, add, commit, and push your changes to the repository:

    ```bash
    git add source/add_numbers.py
    git commit -m "Update add_numbers script"
    git push origin main
    ```

6. **GitHub Actions Workflow:**

    Check the GitHub Actions workflow to ensure that the format check is also passing in the CI/CD pipeline.
