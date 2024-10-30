# Deploy multiple Git repositories in an unique folder

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

`modgit` is a shell script for deploying multiple Git repositories in root folder of any project, which is not possible with default `git submodule` command. A common use case would be the easy installation of Magento modules that need to be deployed in root folder.

## Installation

### curl installation

    $ curl https://raw.githubusercontent.com/nholuongut/modgit/master/modgit > modgit
    $ chmod +x modgit
    $ mv modgit /usr/local/bin

### wget installation

    $ wget -O modgit https://raw.githubusercontent.com/nholuongut/modgit/master/modgit
    $ chmod +x modgit
    $ mv modgit /usr/local/bin

### Manual download
* Download shell script [here](https://raw.github.com/nholuongut/modgit/master/modgit)
* Copy modgit file to `/usr/local/bin` (or any folder in your $PATH)
* Run `chmod +x modgit`

## Usage

### Install a module

    $ cd /path/to/project
    $ modgit init
    $ modgit add [-n] [-t tag_name] [-b branch_name] <module> <git_repository>

### Update a module

    $ modgit up [-n] <module>

### Update all modules

    $ modgit up-all [-n]

### Remove a module

    $ modgit rm [-n] <module>

### Remove all modules

    $ modgit rm-all [-n]

### List installed modules

    $ modgit ls

### Show information about an installed module

    $ modgit info <module>

### Show deployed files of an installed module

    $ modgit files <module>

### Show help

    $ modgit help

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
