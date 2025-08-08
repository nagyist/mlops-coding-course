# Agents Instructions

## About the Course

**Welcome to the [MLOps Coding Course](https://mlops-coding-course.fmind.dev/)!**

This course is designed to dive deep into the intersection of software development and data science, focusing on the practical applications of machine learning (ML) and artificial intelligence (AI) projects using Python.

Whether you are a beginner eager to explore or an experienced professional seeking to enhance your skill set, this course offers valuable insights and hands-on experience.

**Related Resources:**

- **[MLOps Python Package (Example)](https://github.com/fmind/mlops-python-package)**: Kickstart your MLOps initiative with a flexible, robust, and productive Python package.
- **[LLMOps Coding Package (Example)](https://github.com/callmesora/llmops-python-package/)**: Example with best practices and tools to support your LLMOps projects.
- **[Cookiecutter MLOps Package (Template)](https://github.com/fmind/cookiecutter-mlops-package)**: Start building and deploying Python packages and Docker images for MLOps tasks.

### Key Features

[](https://github.com/MLOps-Courses/mlops-coding-course#key-features)

- **Hands-on Python Coding**: Learn to code with Python in a way that's directly applicable to real-world AI projects.
- **Project-Driven Learning**: Each chapter includes practical project instructions to help you apply what you've learned.
- **MLOps Techniques**: Gain insights into effective MLOps coding strategies that streamline the development and deployment of AI/ML models.
- **Open Source Tools**: Familiarize yourself with industry-standard tools like [uv](https://docs.astral.sh/uv/), [pytest](https://docs.pytest.org/en/latest/), [pyenv](https://github.com/pyenv/pyenv), [ruff](https://docs.astral.sh/ruff/), [mlflow](https://mlflow.org/), [bandit](https://bandit.readthedocs.io/en/latest/), [pre-commit](https://pre-commit.com/), [GitHub](https://github.com/), and [VS Code](https://code.visualstudio.com/).
- **Mentoring sessions**: Boost your learning experience with personalized feedback and expert insights from the course authors.
    - Book [a one-on-one mentoring session](https://calendar.app.google/9KfEBkpCHQKwarLF8) to receive tailored guidance and support on the course.
    - Contact the [course creators](mailto:mlops-coding-course@fmind.dev) to request a personalized quote for group and organization training.
- **MLOps Coding Assistant**: Get help from the [MLOps Coding Assistant](https://mlops-coding-assistant.fmind.dev/), a premium tool that provides code snippets, explanations, and examples to help you learn and apply MLOps techniques.
    - Contact the [course creators](mailto:mlops-coding-course@fmind.dev) to access the assistant for $10 per month.

### Course Content

[](https://github.com/MLOps-Courses/mlops-coding-course#course-content)

1. **Initializing**: Set up your development environment, manage Python versions, and handle external dependencies.
2. **Prototyping**: Use Jupyter notebooks for ML prototyping, explore dataset manipulation, and perform initial model assessments.
3. **Productionizing**: Transition from notebooks to clean Python packages, learn about modular coding, and understand different programming paradigms.
4. **Validating**: Focus on code quality with typing, linting, testing, and debugging to ensure your ML projects are robust and maintainable.
5. **Refining**: Dive into advanced MLOps techniques including CI/CD workflows, software containers, and model registries to streamline your operations.
6. **Sharing**: Learn how to effectively organize and document your MLOps projects to ensure they are accessible and collaborative.
7. **Observability**: Gain comprehensive insights into the behavior and performance of your deployed models and infrastructure.

## Python Style Guide

This projects uses Python 3.11

## Markdown Style Guide

Respect the following markdownlint rules:

- **[MD001](https://github.com/DavidAnson/markdownlint/blob/main/doc/md001.md)** _heading-increment_ - Heading levels should only increment by one level at a time
- **[MD003](https://github.com/DavidAnson/markdownlint/blob/main/doc/md003.md)** _heading-style_ - Heading style
- **[MD004](https://github.com/DavidAnson/markdownlint/blob/main/doc/md004.md)** _ul-style_ - Unordered list style
- **[MD005](https://github.com/DavidAnson/markdownlint/blob/main/doc/md005.md)** _list-indent_ - Inconsistent indentation for list items at the same level
- **[MD007](https://github.com/DavidAnson/markdownlint/blob/main/doc/md007.md)** _ul-indent_ - Unordered list indentation
- **[MD009](https://github.com/DavidAnson/markdownlint/blob/main/doc/md009.md)** _no-trailing-spaces_ - Trailing spaces
- **[MD010](https://github.com/DavidAnson/markdownlint/blob/main/doc/md010.md)** _no-hard-tabs_ - Hard tabs
- **[MD011](https://github.com/DavidAnson/markdownlint/blob/main/doc/md011.md)** _no-reversed-links_ - Reversed link syntax
- **[MD012](https://github.com/DavidAnson/markdownlint/blob/main/doc/md012.md)** _no-multiple-blanks_ - Multiple consecutive blank lines
- **[MD013](https://github.com/DavidAnson/markdownlint/blob/main/doc/md013.md)** _line-length_ - Line length
- **[MD014](https://github.com/DavidAnson/markdownlint/blob/main/doc/md014.md)** _commands-show-output_ - Dollar signs used before commands without showing output
- **[MD018](https://github.com/DavidAnson/markdownlint/blob/main/doc/md018.md)** _no-missing-space-atx_ - No space after hash on atx style heading
- **[MD019](https://github.com/DavidAnson/markdownlint/blob/main/doc/md019.md)** _no-multiple-space-atx_ - Multiple spaces after hash on atx style heading
- **[MD020](https://github.com/DavidAnson/markdownlint/blob/main/doc/md020.md)** _no-missing-space-closed-atx_ - No space inside hashes on closed atx style heading
- **[MD021](https://github.com/DavidAnson/markdownlint/blob/main/doc/md021.md)** _no-multiple-space-closed-atx_ - Multiple spaces inside hashes on closed atx style heading
- **[MD022](https://github.com/DavidAnson/markdownlint/blob/main/doc/md022.md)** _blanks-around-headings_ - Headings should be surrounded by blank lines
- **[MD023](https://github.com/DavidAnson/markdownlint/blob/main/doc/md023.md)** _heading-start-left_ - Headings must start at the beginning of the line
- **[MD024](https://github.com/DavidAnson/markdownlint/blob/main/doc/md024.md)** _no-duplicate-heading_ - Multiple headings with the same content
- **[MD025](https://github.com/DavidAnson/markdownlint/blob/main/doc/md025.md)** _single-title/single-h1_ - Multiple top-level headings in the same document
- **[MD026](https://github.com/DavidAnson/markdownlint/blob/main/doc/md026.md)** _no-trailing-punctuation_ - Trailing punctuation in heading
- **[MD027](https://github.com/DavidAnson/markdownlint/blob/main/doc/md027.md)** _no-multiple-space-blockquote_ - Multiple spaces after blockquote symbol
- **[MD028](https://github.com/DavidAnson/markdownlint/blob/main/doc/md028.md)** _no-blanks-blockquote_ - Blank line inside blockquote
- **[MD029](https://github.com/DavidAnson/markdownlint/blob/main/doc/md029.md)** _ol-prefix_ - Ordered list item prefix
- **[MD030](https://github.com/DavidAnson/markdownlint/blob/main/doc/md030.md)** _list-marker-space_ - Spaces after list markers
- **[MD031](https://github.com/DavidAnson/markdownlint/blob/main/doc/md031.md)** _blanks-around-fences_ - Fenced code blocks should be surrounded by blank lines
- **[MD032](https://github.com/DavidAnson/markdownlint/blob/main/doc/md032.md)** _blanks-around-lists_ - Lists should be surrounded by blank lines
- **[MD033](https://github.com/DavidAnson/markdownlint/blob/main/doc/md033.md)** _no-inline-html_ - Inline HTML
- **[MD034](https://github.com/DavidAnson/markdownlint/blob/main/doc/md034.md)** _no-bare-urls_ - Bare URL used
- **[MD035](https://github.com/DavidAnson/markdownlint/blob/main/doc/md035.md)** _hr-style_ - Horizontal rule style
- **[MD036](https://github.com/DavidAnson/markdownlint/blob/main/doc/md036.md)** _no-emphasis-as-heading_ - Emphasis used instead of a heading
- **[MD037](https://github.com/DavidAnson/markdownlint/blob/main/doc/md037.md)** _no-space-in-emphasis_ - Spaces inside emphasis markers
- **[MD038](https://github.com/DavidAnson/markdownlint/blob/main/doc/md038.md)** _no-space-in-code_ - Spaces inside code span elements
- **[MD039](https://github.com/DavidAnson/markdownlint/blob/main/doc/md039.md)** _no-space-in-links_ - Spaces inside link text
- **[MD040](https://github.com/DavidAnson/markdownlint/blob/main/doc/md040.md)** _fenced-code-language_ - Fenced code blocks should have a language specified
- **[MD041](https://github.com/DavidAnson/markdownlint/blob/main/doc/md041.md)** _first-line-heading/first-line-h1_ - First line in a file should be a top-level heading
- **[MD042](https://github.com/DavidAnson/markdownlint/blob/main/doc/md042.md)** _no-empty-links_ - No empty links
- **[MD043](https://github.com/DavidAnson/markdownlint/blob/main/doc/md043.md)** _required-headings_ - Required heading structure
- **[MD044](https://github.com/DavidAnson/markdownlint/blob/main/doc/md044.md)** _proper-names_ - Proper names should have the correct capitalization
- **[MD045](https://github.com/DavidAnson/markdownlint/blob/main/doc/md045.md)** _no-alt-text_ - Images should have alternate text (alt text)
- **[MD046](https://github.com/DavidAnson/markdownlint/blob/main/doc/md046.md)** _code-block-style_ - Code block style
- **[MD047](https://github.com/DavidAnson/markdownlint/blob/main/doc/md047.md)** _single-trailing-newline_ - Files should end with a single newline character
- **[MD048](https://github.com/DavidAnson/markdownlint/blob/main/doc/md048.md)** _code-fence-style_ - Code fence style
- **[MD049](https://github.com/DavidAnson/markdownlint/blob/main/doc/md049.md)** _emphasis-style_ - Emphasis style
- **[MD050](https://github.com/DavidAnson/markdownlint/blob/main/doc/md050.md)** _strong-style_ - Strong style
- **[MD051](https://github.com/DavidAnson/markdownlint/blob/main/doc/md051.md)** _link-fragments_ - Link fragments should be valid
- **[MD052](https://github.com/DavidAnson/markdownlint/blob/main/doc/md052.md)** _reference-links-images_ - Reference links and images should use a label that is defined
- **[MD053](https://github.com/DavidAnson/markdownlint/blob/main/doc/md053.md)** _link-image-reference-definitions_ - Link and image reference definitions should be needed
- **[MD054](https://github.com/DavidAnson/markdownlint/blob/main/doc/md054.md)** _link-image-style_ - Link and image style
- **[MD055](https://github.com/DavidAnson/markdownlint/blob/main/doc/md055.md)** _table-pipe-style_ - Table pipe style
- **[MD056](https://github.com/DavidAnson/markdownlint/blob/main/doc/md056.md)** _table-column-count_ - Table column count
- **[MD058](https://github.com/DavidAnson/markdownlint/blob/main/doc/md058.md)** _blanks-around-tables_ - Tables should be surrounded by blank lines
- **[MD059](https://github.com/DavidAnson/markdownlint/blob/main/doc/md059.md)** _descriptive-link-text_ - Link text should be descriptive
