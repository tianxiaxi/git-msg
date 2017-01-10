# git tools

+ git-msg
+ git-user

## git-msg

Update user name and email from git history message

+ Get `git-msg` from github

```bash
wget https://github.com/tianxiaxi/git-msg/raw/master/git-msg -O /usr/bin/git-msg

chmod +x /usr/bin/git-msg
```

+ Usage

```bash
git-msg - Update user name and email from git history message

Usage: git-msg <old email> <user name> <new email>

Required:
    <old email>   - Old email which will be replaced
    <user name>   - User name for git commiter and author
    <new email>   - New email for git commiter and author

Author: wayne@zanran.me
URL:    www.dailyshare.cn
Github: git@github.com:tianxiaxi/git-msg.git
```

## git-user

Auto update git user name and email form ~/.ssh/config

+ Get `git-user` from github

```bash
wget https://github.com/tianxiaxi/git-msg/raw/master/git-user -O /usr/bin/git-user

chmod +x /usr/bin/git-user
```

+ Usage

```bash
git-user - Auto update git user name and email form ~/.ssh/config

Usage: git-user [-h | --help | ?]

Optional:
    -h | --help | ?   - Show usage information for git-user

Author: wayne@zanran.me
URL:    www.dailyshare.cn
Github: git@github.com:tianxiaxi/git-msg.git
```
