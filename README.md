# pwd.sh
GnuPG wrapper for password management.

This script uses GPG to manage an encrypted text file containing passwords.

# Requirements
Requires `gpg`. Install with `brew install gpg` or `apt-get install gnupg` or build and install it from [source](https://www.gnupg.org/download/index.html).

# Installation

    git clone https://github.com/drduh/pwd.sh && cd pwd.sh
    
# Use

Run the script with `./pwd.sh`
    
Type `w` to create a password. Will update existing password with same Username/ID.

Type `r` to print stored passwords. Can be piped to `grep` and `pbcopy` or `xsel`, for example.

To reset/erase keys and passwords, `rm pwd.sh.*`.
