# Project File Structure Activity

![an image of a calculator](calculator.jpg)

For this activity, the objective is to re-organize the files in this repo so they are organized in accordance with best practices.

After re-organizing the files, it will also be necessary to update the imports in the program (.py) files so the tests may run successfully.

To check if the tests are running as expected, run the following command:

```
python3 -m pytest test_X.py
```

Replace X with addition, subtraction, multiplication, or division. If the file you are testing is nested in a sub-directory, please remember to cd into the directory before running the command.

Once the tests are running correctly, please also create the following for the project:
* A README file explaining the project and how the modules can be used
* A .gitignore file
* Choose a license for the project

You can find hints to get you started in the [hints.md](hints.md) file.

# Hints

Here are some common sub-directories found in projects:

Directory Type | Description | Common Names
---    | ---  | ---
Assets | This directory may contain items such as images for a project, favicons, type fonts, etc | assets, resources, static
Source Code | The code for a project typically live in this directory | src, project name (i.e. calculator)
Tests | The tests for a project typically live in this directory | test(s)
Elaborate Documentation | Some projects may require multiple files to document the in-and-outs of how to utilize or contribute to the project. They would be housed under this type of directory. This file (hints.md) is the type of file you may find in this type of directory. | docs, project-docs

Please keep in mind that not *all* files will need to be placed into sub-directories.