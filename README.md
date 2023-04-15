# Perl Find-in-Folder
A simple Perl script to search all files in a folder for string matches.

 - First argument is the path to search files inside of
 - Second argument is the string to match
 - Output is a hash dump listing the file name and line number of each match

There probably already exists a better tool/chain of Unix commands for this purpose, but I thought it would be fun to make my own.

# TODO
- Add column of matched string to output hash for easier location
- Use Parallel::ForkManager to search files in parallel if overhead is worth it
- Tidy up output