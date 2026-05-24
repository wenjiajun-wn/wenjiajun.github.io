---
title: git的基础语法
date: 2026-05-23
tags:
- git
---
如何使用git
git的基本操作
pwd--打印当前的工作目录
cd--移动到目录
ls--列出目录下的文件
git --version--查看git的版本
git init--初始化一个git仓库
git status--查看当前仓库的状态
git add. 只需一个命令，将两个修改过的文件添加到备用区域。
git commit -m提交一个提交，包括合适的标志，这样你就可以作为命令的一部分提供日志消息
git log--查看提交历史
git log -2 仅查看最近两个提交的信息。
git log --since'--查看自某个日期以来的提交
git diff--查看文件的修改内容
git diff --staged--运行命令将最后提交的版本与预备区的版本进行比较
git diff --report.md--查看report.md文件的修改内容
git diff HEAD~1 HEAD~2--比较最近两次提交之间的差异
git revert--撤销一个提交
git checkout--切换分支或恢复工作树文件
git restore --staged--将文件从暂存区恢复到工作区
git revert HEAD --no-edit-- 撤销最近的提交，并使用默认的提交消息

# 欢迎来到我的博客