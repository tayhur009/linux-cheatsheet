# Linux / Terminal Cheatsheet (Week 1)

## Navigation
pwd        → print working directory
ls         → list directory contents
ls -la     → list with details and hidden files
cd <dir>   → change directory
cd ..      → go up one level
cd ~       → go to home directory

## Files & Directories
mkdir <dir>         → create directory
touch <file>        → create empty file
echo "text" > file  → write (overwrite) to file
echo "text" >> file → append to file
cat <file>          → display file content
rm <file>           → remove file
rm -r <dir>         → remove directory and contents (dangerous)

## Permissions
ls -l               → show permissions and file details
chmod +x <file>     → make file executable
chmod 644 <file>    → set numeric permissions (owner rw, others r)

## Search & Find
grep "text" <file>  → search text in file
grep -n "text" <file> → search with line numbers
find . -name "*.txt" → find files by name

## System & Processes
whoami              → show current user
date                → show current date/time
uname -a            → system information
top                 → show running processes (q to quit)

## Tips
- Use `-i` with rm for interactive delete: rm -i <file>
- Use autocomplete: press TAB to complete file/folder names
- Press Ctrl+C to stop commands that are running

- glance: use 'tab' for autocomplete
