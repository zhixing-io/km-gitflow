# awesome-gitflow
## 开发之前准备
### 创建迭代分支
> 每次迭代/发版只有一个测试分支，SIT测试和UAT测试都基于该测试分支，提测时将要提测的开发分支合入测试分支
```sh
git checkout -b test/<迭代号>
```
### 基于迭代分支拆分需求分支
> 每个需求卡片拉一个开发分支，修改bug也只能基于开发分支
```sh
git checkout -b feature/<需求号>
```
### 基于需求分支拆分bug分支（可省略）


## 参考资料
- [一个成功的 Git 分支模型](https://zhuanlan.zhihu.com/p/385969268)
- git 的变基(rebase)和合并(merge)具体有什么分别阿？ - 知乎
https://www.zhihu.com/question/26492099
- 在开发过程中使用 git rebase 还是 git merge，优缺点分别是什么？ - 知乎
https://www.zhihu.com/question/36509119
- [最好用的中文速查表](https://github.com/skywind3000/awesome-cheatsheets)
- [阿里AoneFlow分支管理](https://www.jianshu.com/p/5ecb8f5cf5db)