# WUIT-LaTeX-Template

Scroll down for the English version of README.

**WUIT-LaTeX-Template** 是 Wuchang Institute of Technology LaTeX Template 的缩写。

此宏包旨在建立一个简单易用的武昌工学院学位论文 LaTeX 模板，包括本科综合论文、课程论文、实验报告以及实训报告。

**由于模板升级频繁，在开始使用和提问前，请确保您已经认真完整地阅读了使用说明文档和示例代码。**

严禁以任何违反 [LaTeX项目公共许可证 v1.3c](https://www.latex-project.org/lppl/lppl-1-3c/) 的方式使用 WUIT-LaTeX-Template 。

## 下载

下载途径：

编写中，暂不提供下载。

**任何在其他途径分发的 WUIT-LaTeX-Template（其他人编写的除外）均不是官方版本，请谨慎使用。**

## 更新日志

每个版本的详细更新日志，请见 [CHANGELOG.md](CHANGELOG.md)。使用文档中也包含了这一内容

#### 开发版

从 GitHub clone 项目源码或者下载源码 zip 包，执行命令（Windows 用户在文件夹空白处按 `Shift + 鼠标右键`，点击“在此处打开命令行窗口”）：

### 目标

* `make WLTemplate`    生成论文 wuit-lateX-template.pdf；
* `make spine`     生成书脊 spine.pdf；
* `make doc`       生成模板使用说明书 WUIT-LaTeX-Template.pdf；
* `make all`       生成论文和书脊，相当于 `make WLTemplate && make spine`；
* `make clean`     删除示例文件的中间文件（不含 wuit-lateX-template.pdf）；
* `make cleanall`  删除示例文件的中间文件和 wuit-lateX-template.pdf；
* `make distclean` 删除示例文件和模板的所有中间文件和 PDF。
