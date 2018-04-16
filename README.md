# requirements-document
(●￣(ｴ)￣●)提供的需求文档

## git开发协作流程

最开始在master分支下：

* git checkout -b dev-baobao(如果有dev-baobao就不需要-b)
* 在这个分支上开发
* git checkout master
* git pull
* git checkout dev-baobao
* git merge master
* 如果有冲突解决冲突（在编辑器里会有提示哪里冲突了的）
* git add .(添加你要提交的文件到暂存区，一般全选就为`.`、或者填写文件名用空格分隔)
* git commit -m "add new commits"
* git push
* 打开github网站，定位到对应远程版本库
* 点击new pull request按钮，按照操作指引请求合并到master分支
