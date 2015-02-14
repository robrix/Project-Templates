# Project templates

This repository contains Xcode project templates primarily intended to ease the creation of µframeworks in Swift.


# Features

- Framework projects can be created with a `.xcworkspace`.
- Framework projects can be created with a `LICENSE` file. Currently only the MIT license is available.
- Framework projects can be created with a `.gitignore` file.
- Minimal `___COPYRIGHT___`-only source file headers.


# Use

Clone this repository to `~/Library/Developer/Xcode/Templates/Project Templates` (or clone it elsewhere and put a symlink there).


# Caveats

1. Xcode project templates apparently cannot files to the repository without adding them to a group in the project. As a consequence of this, using the `LICENSE`, `.xcworkspace`, or `.gitignore` options will add them to a group in the project.

2. For the same reason, Xcode will open the `.xcodeproj` file even if you’ve enabled the `.xcworkspace` option.

3. The “language choice” option currently only includes Swift.


# Notes

Many of these templates were based directly on Apple’s templates included with Xcode 6. Many thanks to the Xcode team for creating a powerful templating system with interesting default templates!
