# CodingBat

## Table of Contents
1. [Project Overview](#project-overview)
2. [Solution Index](#solution-index)
3. [Project Structure](#project-structure)
4. [Setup and Run](#setup-and-run)
   - [Java](#java)
   - [Python](#python)
5. [Author](#author)

## Project Overview
This repository contains solutions to CodingBat problems implemented in both Java and Python.  
The purpose of this project is to strengthen problem-solving skills, reinforce programming fundamentals, and compare implementation approaches across languages.

Each language directory includes a `Main` file that serves as the entry point for executing and testing the implemented methods.

## Solution Index
For quick access to all CodingBat solutions, see the full index below:
- [Browse All Solutions](SolutionIndex.md)
  This index organizes solutions by language and category for easier navigation.

## Project Structure

The repository is organized as follows:

```text
src/
  ├── Python/
  └── Java/

starter/
  ├── Python/
  └── Java/
```

- The src/ directory contains completed CodingBat solutions.
- The starter/ directory contains unimplemented versions for practice.

## Setup and Run

### 1. Download the Repository

#### Option A: Using the Command Prompt
1. Clone the repository to your local computer:
```bash
git clone https://github.com/tun67213/CodingBat.git
```

2. Navigate to the project directory:
```bash
cd CodingBat
```

### Option B: Using GitHub Desktop
(Note: if GitHub Desktop is not installed, you can download it [here](https://desktop.github.com/download/).)

1. Open the GitHub repository: [CodingBat Repository](https://github.com/tun67213/CodingBat)
2. Click the <> Code button.
3. Make sure Local is selected.
4. Select Open with GitHub Desktop.
5. GitHub Desktop will open automatically and ask where you would like to save the repository on your computer.
6. Choose a local folder/location, then click Clone.
7. Once cloning is complete, the repository will be available on your local device.
   
You can now proceed to the steps below.

### Compile and Run

#### First step
As a first step, run the following command to get into the repository containing all implementations for both Python and Java:
```bash
cd CodingBat/src
```

#### Java
Compile and run the Java implementations:

```bash
cd Java
javac src/Main.java
java src.Main
```

---

#### Python
Run the Python implementations:

If you were previously running Java code and are currently inside `CodingBat/src/Java`, run the following before moving on:
```bash
cd ..
```

To run all Python-related implementations from CodingBat/src:
```bash
cd Python
python3 Main.py
```

Alternatively, to run a module-specific implementation from `CodingBat/src`, add the file name after `python3`. The following shows how to run Warmup-1 methods:

```bash
cd Python
python3 Warmup_1.py
```

The general rule of thumb for running module-specific code in Python is as follows:
```bash
cd Python
python3 [module_name].py
```
where you would replace [module_name] with the specific module's name.

For Windows users:

If the system does not recognize `python3`, use `python` instead:
If not already in the Python repository:
```bash
cd Python
```
Otherwise:
```bash
python [module_name].py
```

## Author
<p align="center">
  <img src="https://github.com/hiarvindh.png" width="120" />
  <br/>
  <b>Arvindh Velrajan</b>
  <br/>
  <i>CodingBat Practice Repository</i>
  <br/>
  <a href="https://github.com/hiarvindh">@hiarvindh</a>
</p>
