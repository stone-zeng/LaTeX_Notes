# Version list:

## 2016/7/9

1. 增加 `Version_List.md`，开始版本记录

2. 增加问题 2：连字符

3. 问题 1，新的标点符号用法（2011）

4. 脚注不用下标

5. 增加列表环境

6. 增加空行命令

## 2016/7/11

1. 将 `Version_List.md` 重命名为 `README.md`

2. 增加参考文献

## 2016/7/12

1. 使用 `mybst` 参考文献格式，并引入相关文件

2. 改用 `oneside` 格式，减少分页

## 2016/7/15

1. 增加问题 4：微分符号

2. 引入 `physics` 宏包

3. 引入 `siunitx` 宏包

4. 大幅修改 `tcolorbox` 宏包命令，增加 `myExampleH` 和 `myExampleV` 环境（代码 + 效果），
允许 box 分页，修改颜色、边框，修改逃逸字符

5. `\filename` 命令改为等宽字体

6. 改进 `mybst` 文献格式，增加 version 项

7. 修改参考文献数据库中 url 项

8. 参考文献列表改用 small 字号

## 2016/7/16

1. 增加 宏包 一章

2. 增加问题 6：`mathdesign` 宏包找不到 `texnansi.enc`

3. 代码环境允许自动换行

## 2016/7/17

1. 问题 4：微分符号 go on

2. 等宽字体禁用连字

3. 定义对错符号

## 2016/7/24

1. 增加 `Ch_Font.tex`

2. 增加脚本 `MAKE.bat` 和 `DELETE.bat`

3. 增加问题 3：正文上下标

4. 加问题 6： `eu1lmr.fd` 编译很慢

5. 问题 5：微分符号 go on

6. `ctex`：日期格式改用 英文旧式

7. `xeCJK`：正文 方正书宋 `BoldFont` 改用 方正黑体，增加 SmallCapsFont 支持

8. 标题页重新构建，改用繁体，增加图片

9. `\myQA` 环境：增加 `\phantomsection` 命令，以防 `hyperref` 报错

10. `\filename` 命令：重构

11. 参考文献：增加 `mybst.new.bst` 和 `mybst.old.bst` 文件，方便管理；
增加 `gbt-7714-2015-numerical.bst` 文件拷贝（供测试）

12. 参考文献：改用 `mybst.new` 格式

13. 引用：改为 作者名 + 数字

14. `mybst.new`：增加 standard、www 类，网址左对齐（by 陶润恺），人名使用全称、SmallCapital，
改用 author-year 格式（仍用数字引用）

15. `\nocite{*}` 位置移动到 `\bibliography` 之前

## 2016/7/29

1. 添加 PDF 文件至 git

## 2016/8/8

1. 统一全文引用为 作者名 + 数字

## 2016/8/10

1. 增加 `Examples` 文件夹

2. 增加封面（包括 `Cover` 文件夹和 `Cover.ai`、`Cover.pdf`）

3. 增加 `cm`、`cmbright` 等字体示例

4. 增加问题：数学字体

5. 修改标题页，改为内页

6. 引入 `pdfpages` 宏包

## 2016/8/12

1. 更改 URL 超链接配色

## 2016/8/27

1. 增加 `txfonts`、`pxfonts` 字体示例

2. 问题 8：数学字体 go on

## 2016/8/28

1. 增加 `mathptmx` 字体示例，试图增加 `newtxmath` 字体示例（需改进）

2. 问题 8：数学字体 go on

3. TODO list 增加内容