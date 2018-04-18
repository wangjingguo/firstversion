Git is a version control system.
Git is free software.

第一步，用命令git add告诉Git，把文件添加到仓库

git commit -m "wrote a readme file"


git log命令显示从最近到最远的提交日志--如果嫌输出信息太多，看得眼花缭乱的，可以试试加上--pretty=oneline参数

HEAD指向的版本就是当前版本，因此，Git允许我们在版本的历史之间穿梭，使用命令git reset --hard commit_id。

穿梭前，用git log可以查看提交历史，以便确定要回退到哪个版本。

要重返未来，用git reflog查看命令历史，以便确定要回到未来的哪个版本。