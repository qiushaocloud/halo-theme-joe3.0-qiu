<h1 align="center"> Halo Theme Joe3 Qiu </h1>

<p class="badge-row" align="center">
  <a href="https://halo.run" target="_blank">
    <img src="https://img.shields.io/badge/dynamic/yaml?label=Halo&query=%24.spec.require&url=https://raw.githubusercontent.com/qiushaocloud/halo-theme-joe3.0-qiu/master/theme.yaml&color=113,195,71" alt="Halo"/>
  </a>
  <a href="https://github.com/qiushaocloud/halo-theme-joe3.0-qiu/releases" target="_blank">
    <img src="https://img.shields.io/github/v/release/qiushaocloud/halo-theme-joe3.0-qiu" alt="Release"/>
  </a>
  <a href="https://halo.run" target="_blank">
    <img src="https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-orange" alt="License"/>
  </a>
</p>

<p align="center">Joe3.0 Halo 主题 邱少修改版</p>

---
<p align="center">
<img width="100%" src="https://wmimg.com/i/70/2023/08/64d3c41d5bde2.webp">
</p>

预览：[邱少羽梦 Blog](https://www.qiushaocloud.top)

#### 👀 [有疑问或者功能需求，请点击此处前往](https://www.qiushaocloud.top/2024/05/05/halo2x-joe30-zhu-ti-qiu-shao-xiu-gai-ban)


### 邱少羽梦修改内容
1. 支持不蒜子统计、邱少羽梦实现的[极简网页计数器](https://www.qiushaocloud.top/2022/01/10/site-counter)
2. 支持导航条三级菜单
3. 友链支持默认头像，优化友链样式，支持渐变色背景
4. 头像支持根据所属博主名称生成图片
5. 修复若干 bug
6. 导航条站点图标后支持显示博客名称
7. 留言板 Markdown 内容展示
8. 部分样式修改及优化
9. 首页文章支持排除指定的分类【暂未实现】
10. 支持 iframe 模板展示其它网页【暂未实现】
11. 支持 pdf 模板展示 pdf 文件【暂未实现】
12. 支持 Markdown 模板展示 Md 文件【暂未实现】
13. 支持朋友圈模板【暂未实现】
14. 支持 Docsme、豆瓣模板【暂未实现】
15. 实现登陆评论后文章可见的功能
16. 支持推送到各大搜索引擎【暂未实现】
17. 友链支持按照分类的seq排序，同一分类内也按照seq排序
18. 友链支持配置分类是否显示，也支持配置某个友链是否显示
19. 友链支持友链申请表单【暂未实现】
20. 友链支持评论区是否显示
21. 支持 comment-widget 进行图片上传，不需要修改 comment-widget 源代码，在主题中控制 comment-widget 的样式和逻辑【暂未实现】
22. 图库逻辑和样式优化，添加动画效果及图片信息展示，参考 Joe2.0 主题【暂未实现】
23. 支持博主等级是否显示，并支持等级计算公式模版进行计算等级
24. 评论区只显示一个回复输入框，且回复后自动关闭输入框【暂未实现】
25. 移动端的菜单支持图标，可配置【暂未实现】

### 等待修复的bug
* [mac command + C 复制文章内容时，会直接选中其它内容](https://github.com/jiewenhuang/halo-theme-joe3.0/issues/269)
* [设置了”自定义-外部CSS链接“没有效果，页面中没有引入css文件](https://github.com/jiewenhuang/halo-theme-joe3.0/issues/252)
* [设置了 “后台-设置-代码注入-页脚”，但是在主题页面中并没有注入到页脚](https://github.com/jiewenhuang/halo-theme-joe3.0/issues/251)
* pad上横屏时文章目录没显示内容
* 留言簿获取的评论墙并不止是该页面的评论，其它页面的评论也显示在其中了

<hr />

文档：部分配置请参考 [Joe3不完全使用指导指南](https://www.jiewen.run/archives/joe3use)
> halo-theme-Joe3-qiu 是一款 [Halo2.0](https://halo.run/) 的博客主题  
> 由[halo-theme-joe2.0](https://github.com/qinhua/halo-theme-joe2.0)适配而来，感谢原作者的无私奉献

**类似主题效果图** 👇
![类似主题效果图](https://githubcdn.qiushaocloud.top/gh/qiushaocloud/halo-theme-joe3.0-qiu@master/templates/assets/img/dp/mockup.jpg)
![类似主题效果图](https://githubcdn.qiushaocloud.top/gh/qiushaocloud/halo-theme-joe3.0-qiu@master/templates/assets/img/dp/screenshot.png)


## 安裝

### 下载安装
* 下载[releases](https://github.com/qiushaocloud/halo-theme-joe3.0-qiu/releases)或者直接[下载代码](https://github.com/qiushaocloud/halo-theme-joe3.0-qiu)，通过 Halo Console 后台主题安装处上传即可。
* 【推荐这种方式】到 `themes` 目录下克隆主题：`git clone https://github.com/qiushaocloud/halo-theme-joe3.0-qiu.git theme-Joe3-qiu`，然后通过 Halo Console 后台主题本地未安装处安装即可。【注意：如果克隆不了，换成 gitee 地址克隆即可，如：`git clone https://gitee.com/qiushaocloud/halo-theme-joe3.0-qiu.git theme-Joe3-qiu`】

## 使用说明
> 1、首次使用请先把主题所有配置保存一遍  
> 2、部分功能使用插件进行实现  
> 3、请配合Halo2.8.0及以上版本使用  
> 4、菜单栏的图标请使用[iconfont](https://www.iconfont.cn/)的图标，需要填入Font Family 和图标代码例如：`jiewen joe-icon-tupian`  
> 5、使用自定义标签样式请安装[Tool-Bench](https://github.com/DioxideCN/Tool-Bench)插件，标签请参考[Joe3部分样式](https://www.jiewen.run/archives/joe3style)或者直接使用插件标签

- [x] 卡片化设计
- [x] 响应式主题
- [x] 深色模式
- [X] 文章目录
- [X] 代码高亮/语言/复制）
- [x] [文章搜索](https://github.com/halo-sigs/plugin-search-widget)
- [x] 显示字数统计
- [x] 显示相关文章
- [X] [评论系统](https://github.com/halo-sigs/plugin-comment-widget)
- [x] [友情链接](https://github.com/halo-sigs/plugin-links)  
- [x] [瞬时](https://github.com/halo-sigs/plugin-moments)  
- [x] [图库](https://github.com/halo-sigs/plugin-photos)  
- [x] 其他功能


## 预览
WIP
## TODO
- [ ] 优化图库
- [ ] ......


### 🏭 贡献

> 如果你想帮助完善 `Joe3.0-qiu` 主题，请：

- 点 `star`
- 提 `issue`
- 修 `bugs`
- 推 `pr`

<br>  

### 奉献提示
此仓库分为master和develop分支，如何您想奉献代码，请fork develop分支，开发完成后提交pr到develop分支，develop分支会定期合并到master分支，master分支为稳定版本且develop分支才是最新代码，不接受pr。


### 🙆‍♂️ 感谢

在此感谢以下项目提供的支持：

- [Halo](https://halo.run)
- [theme-starter](https://github.com/halo-dev/theme-starter)
- [Typecho Themes Joe](https://github.com/HaoOuBa/Joe)
- [Halo-theme-Joe2.0](https://github.com/qinhua/halo-theme-joe2.0)
- [Halo-theme-hao](https://github.com/liuzhihang/halo-theme-hao)
- [Halo-theme-sakura](https://github.com/LIlGG/halo-theme-sakura/tree/next)
- [plugin-links](https://github.com/halo-sigs/plugin-links)
- [plugin-comment-widget](https://github.com/halo-sigs/plugin-comment-widget)
- [plugin-search-widget](https://github.com/halo-sigs/plugin-search-widget)
- [plugin-moments](https://github.com/halo-sigs/plugin-moments)
- [plugin-photos](https://github.com/halo-sigs/plugin-photos)
- ......

<br>


#### 开源不易，如果对您有帮助，请您动一动您的小手，给作者点 Star，也请您多多关注分享者「[邱少羽梦](https://www.qiushaocloud.top)」

* 分享者邮箱: [qiushaocloud@126.com](mailto:qiushaocloud@126.com)
* [分享者博客](https://www.qiushaocloud.top)
* [分享者自己搭建的 gitlab](https://gitlab.qiushaocloud.top/qiushaocloud) 
* [分享者 gitee](https://gitee.com/qiushaocloud/dashboard/projects) 
* [分享者 github](https://github.com/qiushaocloud?tab=repositories) 


### 版权信息公告:
* 此主题是基于 [jiewenhuang/halo-theme-joe3.0](https://github.com/jiewenhuang/halo-theme-joe3.0) 修改
* 以上内容大部分为原作者原创内容
* 如果大家喜欢，请支持 [邱少羽梦(修改者)](https://www.qiushaocloud.top)，也请支持下原作者哦
* 版权归原作者所有，修改者只是进行部分修改，以满足修改者需求
