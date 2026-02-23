# Problem Solving with Python — Chapter 2: Grab the Dialogue

This repository contains the chapter and active-learning exercise code associated with this chapter in the book *Problem Solving with Python: Using Computational Thinking in Everyday Life* by Michael D. Smith (2026), which is available from [MIT Press](https://mitpress.mit.edu/9780262383677/problem-solving-with-python/) and [Amazon](https://www.amazon.com/Problem-Solving-Python-Computational-Thinking/dp/0262552841/).

## Getting started

You will need:

- an integrated development environment (IDE)
- Python 3.10 or newer
- `pip` (usually included with Python)

If you need help getting started with an IDE, please read [my short introduction to "Understanding and Selecting an IDE"](https://ctps.io/select_ide.html).

## Cloning this repository

If you're using GitHub Codespaces, click the green "Code" button on this repo's page, select the tab "Codespaces," and click the "Create codespace on main."

Otherwise, in your IDE's terminal window, type the following commands:

```bash
git clone https://github.com/pswp-book/chap02.git
cd chap02
```

## (Optional) Create and activate a virtual environment

```bash
python -m venv .venv
# Windows
.\.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate
```

## Install dependencies

```bash
pip install -r requirements.txt
```

If there is no file `requirements.txt`, the code in this repository uses only the Python standard library.

## Reporting issues

If you find a problem in this chapter’s code (typo, bug, or mismatch with the book):

1.  Check the issues for this repo to see if it’s already reported.

2.  Open a new issue and include:
    *   The chapter number and section title (e.g., “Chapter 5, The game loop”)
    *   The filename, line number(s), and a short description of the problem.
    *   If something's wrong with the code's execution, please describe how you ran the program and the exeuction result.

## Short description of the repo's files

`read32.py`: our complete solution to the problem in Chapter 1 (i.e.,
it reads a children's story).  This script is a renamed copy of
`chap01/ale03c.py`.

`script1.py`: the parts of `read32.py` that we can use as a start
to solving the new problem in Chapter 2 (i.e., turn a story into
a theatrical script).

`script2.py` - `script7.py`: incomplete scripts that track the major
steps we follow in Chapter 2.

`script8.py`: a script that we hope will work for dialogue spread
over two or more file lines. We're not sure it will work for other
patterns of dialogue.

`script9.py`: a script that fixes a problem with `script8.py`, which
didn't work for dialogue contained completely within one file line.

`txts`: Directory containing plaintext stories (i.e., `[title].txt`).
The chapter and its exercises make reference to a number of these
files as test inputs.

`count32.py`: starting point for ALEs 2.1-2.5.

`script32.py`: a cleaned-up version of `script9.py` that serves
as the starting point for ALE 2.7.

`ale08.py`: starting point for ALE 2.8.
