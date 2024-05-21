# ustcthss-typst 中国科学技术大学本科生毕业论文typst模版

中国科学技术大学本科生毕业论文的typst模版, 能够一键生成论文pdf文件。

按照[2024年中国科学技术大学教务处毕业论文格式要求](https://www.teach.ustc.edu.cn/notice/notice-teaching/17071.html) 编写。

**欢迎提出任何 Issue 和 PR 帮助完善这个模板。**

![ustcthss-typst](./images/cover_ustc.png)

## 使用方式

### 方式一: 本地编译

- 下载安装最新版本的[Typst](https://github.com/typst/typst)
- 克隆本仓库。
- 修改`thesis.typ`完成你的论文写作，`thesis.typ`是论文模版，其中包含了标题、段落、图片、公式、表格、引用、参考文献等的几乎所有毕业论文可能用到的特性。
- 在命令行中，执行`typst compile thesis.typ --font-path fonts`进行编译，生成同名的`thesis.pdf`文件。

### 方式二: 在线编译

进入 [Typst](https://typst.app/) 官网 ，并将本模板的文件导入进去，包括`typ`文件、`fonts/`下的字体、图片文件。然后修改`thesis.typ`完成你的论文写作。



## 致谢

本仓库基于[PKUTHSS-Typst](https://github.com/pku-typst/pkuthss-typst)修改得到，感谢开发者的贡献。