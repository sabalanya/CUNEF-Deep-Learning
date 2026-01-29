
# CUNEF Deep Learning Course

Welcome to the Deep Learning course repository for CUNEF Students.

## About This Course

This repository contains hands-on exercises and tutorials designed to introduce students to the fundamentals of programming, machine learning, and especially deep learning. The course is structured in three main parts, progressively building from basic Python programming to from-scratch implementation of neural networks, and finally to the use of high-level frameworks like PyTorch to develop more complex architectures such as CNNs and LSTMs.


## Course Objectives

By the end of this course, students will be able to:
- Write Python code for data manipulation and analysis

## Course Structure

The course is divided into three main parts:

### Part 1: Fundamentals
Introduction to Python programming, NumPy for numerical computing, Pandas for data manipulation, and Matplotlib for data visualization.

### Part 2: Deep dive into Deep Learning
Understanding neural networks, backpropagation, and building deep learning models from scratch.

### Part 3: Pytorch and Advanced Architectures
Using PyTorch to implement advanced deep learning architectures such as Convolutional Neural Networks (CNNs) and Long Short-Term Memory networks (LSTMs).

---

## Notebooks

### Part 0: Python Intro

<table>
  <tr>
    <th style="width: 25%">Notebook</th>
    <th style="width: 55%">Description</th>
    <th style="width: 20%">Open in Colab</th>
  </tr>
  <tr>
    <td><strong>01 - Introduction to Python</strong></td>
    <td>Python basics: variables, data types, strings, lists, control flow, and functions</td>
    <td><a href="https://colab.research.google.com/github/sabalanya/CUNEF-Machine-Learning/blob/main/part1_fundamentals/01_intro_python.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a></td>
  </tr>
  <tr>
    <td><strong>02 - NumPy Basics</strong></td>
    <td>Arrays, indexing, operations, matrix multiplication, linspace, and random sampling</td>
    <td><a href="https://colab.research.google.com/github/sabalanya/CUNEF-Machine-Learning/blob/main/part1_fundamentals/02_numpy_basics.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a></td>
  </tr>
  <tr>
    <td><strong>03 - Pandas Basics</strong></td>
    <td>Series, DataFrames, reading/writing CSV files, indexing, merging, and groupby operations</td>
    <td><a href="https://colab.research.google.com/github/sabalanya/CUNEF-Machine-Learning/blob/main/part1_fundamentals/03_pandas_basics.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a></td>
  </tr>
  <tr>
    <td><strong>04 - Matplotlib Basics</strong></td>
    <td>Data visualization: line plots, scatter plots, bar charts, histograms, and subplots</td>
    <td><a href="https://colab.research.google.com/github/sabalanya/CUNEF-Machine-Learning/blob/main/part1_fundamentals/04_matplotlib_basics.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a></td>
  </tr>
</table>

### Part 1: Fundamentals

<table>
  <tr>
    <th style="width: 25%">Notebook</th>
    <th style="width: 55%">Description</th>
    <th style="width: 20%">Open in Colab</th>
  </tr>
  <tr>
    <td><strong>01 - Linear Regression</strong></td>
    <td>Hands-on, from-scratch implementations of Linear Regression: closed-form least squares and iterative gradient descent, with clear code, explanations, and exercises.</td>
    <td><a href="https://colab.research.google.com/github/sabalanya/CUNEF-Deep-Learning/fundamentals/linear_regression_solutions.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a></td>
  </tr>
</table>


### Part 2: Deep dive into Deep Learning

<table>
  <tr>
    <th style="width: 25%">Notebook</th>
    <th style="width: 55%">Description</th>
    <th style="width: 20%">Open in Colab</th>
  </tr>
  <tr>
    <td><em>Coming soon...</em></td>
    <td></td>
    <td></td>
  </tr>
</table>

### Part 3: Pytorch and Advanced Architectures

<table>
  <tr>
    <th style="width: 25%">Notebook</th>
    <th style="width: 55%">Description</th>
    <th style="width: 20%">Open in Colab</th>
  </tr>
  <tr>
    <td><em>Coming soon...</em></td>
    <td></td>
    <td></td>
  </tr>
</table>

---

## Getting Started

### Option 1: Google Colab (Recommended for Beginners)

The easiest way to get started is using Google Colab, which requires no installation:

1. Click on any "Open in Colab" badge above
2. The notebook will open in Google Colab
3. Click "Copy to Drive" to save your own copy
4. Start coding!

**Advantages:**
- No setup required
- Runs in the cloud
- Free GPU access
- Automatic saving to Google Drive

### Option 2: Local Installation

If you prefer to run the notebooks locally:

1. **Clone this repository:**
   ```bash
   git clone https://github.com/sabalanya/CUNEF-Machine-Learning.git
   cd CUNEF-Machine-Learning
   ```

2. **Install Anaconda or Miniconda:**
   - Download from [anaconda.com](https://www.anaconda.com/download)

3. **Create a virtual environment:**
   ```bash
   conda create -n cunef-ml python=3.11
   conda activate cunef-ml
   ```

4. **Install required packages:**
   ```bash
   pip install jupyter numpy pandas matplotlib scikit-learn seaborn
   ```

5. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

6. **Navigate to the desired notebook and start learning!**

---

## Required Libraries

The course uses the following Python libraries:

- **NumPy** - Numerical computing
- **Pandas** - Data manipulation and analysis
- **Matplotlib** - Data visualization
- **Pytorch** - Deep learning framework

All libraries are pre-installed in Google Colab. For local installations, see the setup instructions above.

---

## How to Use This Repository

1. **Start with Part 1** if you're new to Python programming
2. **Follow the notebooks in order** - each builds on concepts from previous ones
3. **Complete the exercises** at the end of each section
4. **Experiment and modify** the code to deepen your understanding
5. **Ask questions** during class or office hours

### Tips for Success

- **Run every code cell** - Don't just read, execute the code!
- **Complete all exercises** - Practice is essential for learning
- **Experiment** - Try changing values and see what happens
- **Take notes** - Add your own markdown cells with observations
- **Don't skip the fundamentals** - They're the foundation for everything else

---

## Contributing

Found a typo or error? Have a suggestion for improvement? Contributions are welcome!

1. Fork the repository
2. Create a new branch (`git checkout -b fix/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add improvement'`)
5. Push to the branch (`git push origin fix/improvement`)
6. Create a Pull Request

---

## Contact

**Course Instructor**: Sergio Álvarez Balanyá\
**Email**: sergio.abalanya@cunef.edu\

**Institution**: CUNEF Universidad\
**Course**: Deep Learning

---

## License

This repository is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.

---

## Additional Resources

### Official Documentation
- [Python Documentation](https://docs.python.org/3/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)
