
# COSC2759 Assignment 1
## Notes App - CI Pipeline
- Full Name/Names: Kien Dat Ly
- Student ID/IDs: s3886334

- Full Name/Names: An Ninh Pho
- Student ID/IDs: s3978162

### Guidance (remove this section before final submission)

1. Refer for assignment specification `Marking Guide` for details of what should appear in this README.

2. If you do not see an `Actions` tab in your GitHub, email matthew.cullen@rmit.edu.au with URL to your repository, so that it can be enabled.

3. Implement your CI pipeline in the directory `.github/workflows`.

4. Refer to [src/README.md](/src/README.md) for important details on building and testing the application.

5. Commit images to the `img` directory and add them like
    ```html
    <img src="/img/md.png" style="height: 70px;"/>
    ```
    <img src="/img/md.png" style="height: 70px;"/>

6. Only edit THIS README.md - not the src/README.md

# Project Pipeline

## How to Run the Pipeline

To run the pipeline, use the following commands:

1. **Clone the repository:**
   ```sh
   git clone <repository-url>
   cd <repository-directory>

2. **Install dependencies:**
    npm install
3. **Run the pipeline:**
    npm run ci

## Expected Output

Static Code Analysis / Lint: The linter will check the code for any programming and stylisticerrors.

Unit Testing: All unit tests will be executed and the results will be displayed.

Code Coverage: A report will be generated to show the percentage of code covered by tests.

Artifact Generation: If all tests pass, a deployable artifact will be created.
