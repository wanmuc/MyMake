# 1.MyMake
一个简易的类似make的命令，它实现以下的功能：

- 解析makefile文件并进行基本语法的校验。
- 支持指定特定的目标执行关联的命令。
- 分析目标之间的依赖关系，并递归地完成目标的编译。
- 根据源文件的变更来决定哪些目标需要重新编译，实现源码变更时的增量编译。

# 2.代码介绍
- mymake.cpp为程序执行的入口文件。
- makefileparser.cpp和makefileparser.h实现了makefile的解析。
- makefiletarget.cpp和makefiletarget.h实现了目标之间依赖关系的分析并实现了目标的构建。

# 3.微信公众号
欢迎关注微信公众号「**Linux后端开发工程实践**」，第一时间获取最新文章！扫码即可订阅。
![img.png](https://github.com/wanmuc/MyMake/blob/main/mp_account.png#pic_center=660*180)