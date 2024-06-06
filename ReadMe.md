# 北京航空航天大学学位论文LaTeX模板

> **本模板仅为个人兴趣之作，非官方模板。**

本项目为北京航空航天大学学位论文模板BUAAThesis，包含Word模板和LaTeX模板(基于[ctexbook](https://ctan.org/pkg/ctex))。模板按照2015年8月版《研究生手册》制定，根据2020年7月修订版调整，适用于理工类博士、硕士学位论文（中文）。

## 2024年6月更新

针对《北京航空航天大学研究生撰写学位论文的规定》（2021 年 11 月修订）的相关规定，以及论文评阅过程中给出的相关意见，对LaTeX版硕士论文的模板格式进行了修改，具体修改如下：

- 修改标题为最多3级标题；
- 修改公式字体为Times New Roman；
- 修改表格行距为1.5倍行距；
- 将图表标题和图表之间的距离改为默认值；
- 新增带题注的表格示例；
- 强制英文摘要两边对齐；
- 修改会议论文的参考文献格式为《北京航空航天大学研究生撰写学位论文的规定》中给出的参考格式；
- 去掉参考文献中``[S.l.]``或``[S.n.]``的提示信息；
- 新增arXiv参考文献示例；
- 修改默认打印格式为单面、非保密、关闭引用编号颜色，取消摘要和正文从右侧页开始，图表目录为单标题等；
- 代码格式化。


## 文件列表

```
BUAAThesis
 |- buaa.cls                  // LaTeX宏模板文件
 |- Template.tex              // LaTeX模板
 |- Template.docx             // Word模板
 |- ref.bib                   // LaTeX模板中的参考文献Bib文件
 |- bst/GBT7714-2005.bst      // 国标参考文献BibTeX样式文件2005版
 |- bst/GBT7714-2015.bst      // 国标参考文献BibTeX样式文件2015版
 |- pic/logo-buaa.eps         // 论文封皮北航字样
 |- pic/head-doctor.eps       // 论文封皮学术博士学位论文标题(华文行楷字体替代解决方案)
 |- pic/head-prodoctor.eps    // 论文封皮专业博士学位论文标题(华文行楷字体替代解决方案)
 |- pic/head-master.eps       // 论文封皮学术硕士学位论文标题(华文行楷字体替代解决方案)
 |- pic/head-professional.eps // 论文封皮专业硕士学位论文标题(华文行楷字体替代解决方案)
 |- tex/*.tex                 // LaTeX模板样例中的独立章节
 |- ReadMe.md                 // 本文件
 |- .gitignore                // Git忽略规则
```

## 模板使用

+ Word: 直接在其上进行修改编写，请记得预先备份；
+ LaTeX: 参看LaTeX模板示例template.tex及相应插入章节tex/*.tex。

## 关于图书馆查重

+ By [Qiao Junfeng](https://github.com/qiaojunfeng), 2018/11/22

    实际经验表明，使用此模板经XeLaTeX编译生成的pdf，图书馆查重时未遇到乱码问题。

    我的环境：Manjaro Linux + TeX Live 2018 + TeXstudio 2.12.10。

+ **已修复Windows系统下从pdf拷贝的西文乱码问题**。

## 建议及问题反馈

+ E-mail: [weiqm@buaa.edu.cn](weiqm@buaa.edu.cn)
+ GitHub: [https://github.com/CheckBoxStudio/BUAAThesis/issues](https://github.com/CheckBoxStudio/BUAAThesis/issues)

## 我的环境

+ Windows 10 64bits
+ TeXStudio 2.12.4
+ MiKTeX 2.9
+ CTeX 2017-07-18

## 致谢

感谢[Haixing Hu](https://github.com/Haixing-Hu)提供的2005版参考文献著录BibTeX样式[GBT7714-2005](https://github.com/Haixing-Hu/GBT7714-2005-BibTeX-Style)及[Zeping Lee](https://github.com/zepinglee)提供的2015版参考文献著录BibTeX样式[GBT7714-2015](https://github.com/zepinglee/gbt7714-bibtex-style)，为本项目LaTeX模板的形成提供了很大的帮助。感谢[BwCai](https://github.com/BwCai)提供的Mac编译环境。

***

By [WeiQM](https://weiquanmao.github.io/).
