# test this is master
想测试以下几点：
1、在远程仓库创建一个dev分支，因为master和dev分支的git url一样，那么，分别在本地仓库执行 git clone xxx的时候，在本地仓库也有了2个分支（master和dev）。这样和在本地仓库通过 git checkout -b dev origin/dev
检出的分支，提交后push的是同一个库吗？

另外，在本地没有执行git clone 把远程仓库的master下载下来时，会不会不可以直接执行 git checkout -b dev origin/dev 检出远程仓库的分支？
答：当然了，没clone下来时，都不能执行git命令！！！
