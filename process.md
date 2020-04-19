## Brewfile Setup Process

- created a repo called brewfile and a file called Brewfile
- added installs and cask installs
- $ brew install rcmdnk/file/brew-file
- $ brew file init



➜  ~ brew file init
Do you want to set a repository (y)? ((n) for local Brewfile). [y/n]: y

Set repository,
"non" (or empty) for local Brewfile (/Users/sarahproctor/.config/brewfile/Brewfile),
/path/to/repo for local git repository,
https://your/git/repository (or ssh://user@server.project.git) for git repository,
or (<user>/)<repo> for github repository,
or full path for other git repository: sjproctor/brewfile

###############################################
# Set Brewfile repository as sjproctor/brewfile
###############################################

$ git clone git@github.com:sjproctor/brewfile /Users/sarahproctor/.config/brewfile/sjproctor_brewfile
Cloning into '/Users/sarahproctor/.config/brewfile/sjproctor_brewfile'...
The authenticity of host 'github.com (192.30.255.113)' can't be established.
RSA key fingerprint is SHA256:nThbg6kXUpJWGl7E1IGOCspRomTxdCARLviKw6E5SY8.
Are you sure you want to continue connecting (yes/no/[fingerprint])? y
Please type 'yes', 'no' or the fingerprint: yes
Warning: Permanently added 'github.com,192.30.255.113' (RSA) to the list of known hosts.
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.
Please make sure you have the correct access rights
and the repository exists.
GitHub repository: sjproctor/brewfile doesn't exist.
do you want to create the repository? [y/n]:   
