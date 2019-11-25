## 基于 Lerna 管理 packages 的 Monorepo 项目最佳实践

### Monorepo vs Multirepo
Monorepo(monolithic repository)是单体式仓库，与之对应的是 Multirepo(multiple repository)，这里的“单”和“多”是指每个仓库中所管理的模块数量。  
Multirepo 是比较传统的做法，即每一个 package 都单独用一个仓库来进行管理。例如：Rollup, ...   
Monorep 是把所有相关的 package 都放在一个仓库里进行管理， 每个 package 独立发布 。例如：React, Angular, Babel, Jest, Umijs, Vue ...
![一图胜千言](./docs/images/1565339308398714.jpg)