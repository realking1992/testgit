[TOC]

# Just Try git Markdown document

## git

- `git config [--global] user.name "[name]"` `git config [--global] user.email "[email address]"`
- `cd`到指定目录
- `git init`建立git仓库
- `git add 文件 `将文件添加到仓库（`git add . `是将所有文件添加到仓库）
- `git commit -m "注释语句"`将add的文件commit到仓库
- `git remote add origin git@github.com:***/***.git`将本地的仓库关联到GitHub上
- `git pull origin master`上传前，要先pull一下
- `git push -u origin master`上传代码到GitHub远程仓库（`git push origin master`）