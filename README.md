# Print Structure

## Overview

`print_structure` is a Bash script that generates a clean, tree-like structure of a specified directory and its subdirectories. The output is written to a file, with optional recursion through all subdirectories, while ignoring certain unwanted files like `.DS_Store`, `.git`, and other temporary files.

## Usage

`./print_structure <folder_name>`

This will save the structure in `structure.txt` within the specified folder.

## Include All Subdirectories

The `--all` flag will generate separate structure files for **each** top-level subdirectory in the specified folder:

`./print_structure <folder_name> --all`

## Installation

1. **Add the script to your `$PATH` (optional)**:  

Add the script to your `$PATH` to run it from anywhere:  

`export PATH="$PATH:/path/to/your/script_directory"`

2. Reload your shell configuration:

`source ~/.zshrc` or `source ~/.bashrc`
