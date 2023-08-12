# PGT_Project

## Introduction

Ensuring security and reliability in smart contracts remains a paramount concern in the blockchain domain. While available research projects have utilized machine learning techniques, primarily static analysis, to detect vulnerabilities, these methods often fall short. They present limitations, such as insufficient labeled data, incomplete code analysis due to ineffective execution path navigation, and are computationally demanding.

## About PGT

To address these challenges, we introduce the **Particle Gravitational Translearner (PGT)**. This novel approach is a fusion of a semi-supervised optimization and transductive learning methodology. PGT delves deep into data preprocessing, transforming the textual smart contract source code into dense numerical vectors. This transformation is pivotal as it captures intricate semantic relationships between tokens, enhancing the feature selection process.

### Feature Selection

Our feature selection technique is underpinned by rigorous metaheuristic algorithms. These algorithms traverse the feature space with a balanced focus on exploration and exploitation, ensuring optimized feature extraction.

### Classification Algorithm

The PGT classification algorithm, built on a robust transductive learning approach leveraging labeled and unlabeled data, significantly boosts vulnerability detection accuracy during the classification stage.

## Evaluation

PGT is evaluated comprehensively using a dataset of 47,398 real-world smart contracts. Our evaluations, benchmarked against state-of-the-art methods, revealed that PGT outperformed existing techniques regarding accuracy and computational efficiency.

---

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- R (version 3.6.0 or higher)
- RStudio (optional, but recommended for a better R coding experience)
- Git (for cloning the repository)

### Installation

1. **Clone the Repository**

   Open your terminal or command prompt and run:
   ```bash
   git clone https://github.com/your_username/PGT_Project.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd PGT_Project
   ```

3. **Install Required R Packages**

   Open R or RStudio and run:
   ```R
   install.packages(c("kernlab", "pso", "matrixStats", "tm", "tokenizers"))
   ```

### Running PGT

1. **Load the PGT Script**

   In R or RStudio, set your working directory to the project's location and source the main script:
   ```R
   setwd("/path_to_directory/PGT_Project")
   source("Data Preprocessing.R")
   source("Feature Selection.R")
   source("Classification.R")
   ```

2. **Run the Algorithm**

   Assuming you have datasets `D_train`, `Y_train`, `D_test`, and `X_opt` prepared:
   ```R
   result <- PGT_Classification(X_opt, D_train, Y_train, D_test)
   print(result)
   ```

### Troubleshooting

- If you encounter package installation issues, ensure you have the latest version of R and try installing the packages individually.
- Ensure all datasets are correctly formatted and match the expected input for the PGT functions.

---

## Contributing

We welcome contributions from the community! Whether you're fixing bugs, improving documentation, or proposing new features, your efforts and expertise are appreciated. Here's how you can contribute:

### 1. **Fork the Repository**

Start by forking the [PGT repository](https://github.com/your_username/PGT_Project).

### 2. **Clone Your Fork**

```bash
git clone https://github.com/your_username/PGT_Project.git
cd PGT_Project
```

### 3. **Create a New Branch**

It's best practice to create a new branch for each feature or fix:

```bash
git checkout -b feature/your_feature_name
```
or
```bash
git checkout -b fix/your_fix_name
```

### 4. **Make Your Changes**

- Ensure your code adheres to the project's coding standards.
- If you're adding a feature, make sure to also add relevant tests and documentation.
- If you're fixing a bug, ensure the bug is reproducible with a test before you fix it.

### 5. **Commit Your Changes**

Keep your commit messages clear and descriptive:

```bash
git add .
git commit -m "Add a brief description of your changes"
```

### 6. **Push to Your Fork**

```bash
git push origin feature/your_feature_name
```

### 7. **Submit a Pull Request (PR)**

Go to your fork on GitHub and click the **"New pull request"** button. Fill in the necessary details and submit.

### 8. **Address Review Comments**

Maintainers will review your PR. Address any comments or feedback they provide to ensure timely merging of your contributions.

### Additional Guidelines:

- **Issue First**: For significant changes, it's best to open an issue for discussion before diving into coding.
- **Stay Updated**: Ensure your fork is always updated with the main branch to avoid merge conflicts.
- **Documentation**: Update the README or other documentation if necessary.
- **Testing**: Ensure your code passes all tests and doesn't introduce new bugs.
- **Respect Code Style**: Follow the coding style and conventions used throughout the project.

---

Thank you for contributing to PGT! Your efforts help improve the project for everyone.

---

## License

Certainly! Here's a general overview of the MIT License, which is one of the most common open-source licenses. If you have a different license in mind, please let me know, and I can provide information on that instead.

---

## License

### MIT License

The PGT project is licensed under the MIT License. This means that anyone is free to copy, modify, publish, use, compile, sell, or distribute the software, either in source code form or as a compiled binary, for any purpose, commercial or non-commercial, and by any means.

#### Key Points:

- **Commercial use**: You can use the software for commercial purposes.
- **Modification**: You can make changes to the software.
- **Distribution**: You can distribute the software to others.
- **Sublicense**: You can grant/extend a license to others.
- **Private use**: You can use the software for private purposes.

However, there are some conditions:

- The above copyright notice and this permission notice shall be included in all copies or substantial portions of the software.
- The software is provided "as is", without warranty of any kind.

For the full license text, you can refer to the `LICENSE` file in the repository or visit [MIT License](https://opensource.org/licenses/MIT).

---

This section provides a brief overview of the MIT License for the PGT project. If you decide to use this license, you should include a `LICENSE` file in your repository with the full license text. If you prefer another license, please specify, and I can provide details on that.

---

## Contact

Of course! Here's a template for the contact section of the README:

---

## Contact & Support

For any questions, feedback, or suggestions regarding the PGT project, please reach out to the project maintainers:

- **Rexford Sosu**
  - Email: rexfordsosu@outlook.com
  - GitHub: [@johndoe](https://github.com/niirex1)
  - LinkedIn: [John's LinkedIn](https://www.linkedin.com/in/rexford-sosu-b4593b57/)

We appreciate your interest in the PGT project and look forward to collaborating with you!
---

Please replace "John Doe", "Jane Smith", and the associated links with the actual names and contact details of the project maintainers. This section provides a structured way for users and contributors to reach out to the project team.

---

This README provides a structured overview of the PGT project.
