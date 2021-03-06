# 《Advanced Bash-Scripting Guide》 in Chinese

《高级Bash脚本编程指南》Revision 10中文版

## 原著及早期翻译作品
### 原著
- 原著链接：http://tldp.org/LDP/abs/html/
- 原作：Mendel Cooper
- 原著版本：Revision 10, 10 Mar 2014

### 译著
- 译著连接：http://www.linuxsir.org/bbs/thread256887.html
- 译者：杨春敏 黄毅
- 译著版本：Revision 3.7, 23 Oct 2005

## 翻译作品
翻译的部分都放置在[GitBook](https://www.gitbook.com/book/imcmy/advanced-bash-scripting-guide-in-chinese/details)上，欢迎阅读！

## 翻译进度
- Part 1. Introduction[@imcmy]
	- 1\. Shell Programming![@imcmy]
	- 2\. Starting Off With a Sha-Bang
- Part 2. Basics
	- 3\. Special Characters
	- 4\. Introduction to Variables and Parameters
	- 5\. Quoting
	- 6\. Exit and Exit Status
	- 7\. Tests
	- 8\. Operations and Related Topics
- Part 3. Beyond the Basics
	- 9\. Another Look at Variables
	- 10\. Manipulating Variables
	- 11\. Loops and Branches
	- 12\. Command Substitution
	- 13\. Arithmetic Expansion
	- 14\. Recess Time
- Part 4. Commands
	- 15\. Internal Commands and Builtins
	- 16\. External Filters, Programs and Commands
	- 17\. System and Administrative Commands
- Part 5. Advanced Topics
	- 18\. Regular Expressions
	- 19\. Here Documents
	- 20\. I/O Redirection
	- 21\. Subshells
	- 22\. Restricted Shells
	- 23\. Process Substitution
	- 24\. Functions
	- 25\. Aliases
	- 26\. List Constructs
	- 27\. Arrays
	- 28\. Indirect References
	- 29\. /dev and /proc
	- 30\. Network Programming
	- 31\. Of Zeros and Nulls
	- 32\. Debugging
	- 33\. Options
	- 34\. Gotchas
	- 35\. Scripting With Style
	- 36\. Miscellany
	- 37\. Bash, versions 2, 3, and 4
	- 38\. Endnotes
		- 38.1 Author's Note
		- 38.2 About the Author
		- 38.3 Where to Go For Help
		- 38.4 Tools Used to Produce This Book
		- 38.5 Credits
		- 38.6 Disclaimer
- Bibliography
- Appendix
	- A\. Contributed Scripts
	- B\. Reference Cards
	- C\. A Sed and Awk Micro-Primer
		- C.1 Sed
		- C.2 Awk
	- D\. Parsing and Managing Pathnames
	- E\. Exit Codes With Special Meanings
	- F\. A Detailed Introduction to I/O and I/O Redirection
	- G\. Command-Line Options
		- G.1 Standard Command-Line Options
		- G.2 Bash Command-Line Options
	- H\. Important Files
	- I\. Important System Directories
	- J\. An Introduction to Programmable Completion
	- K\. Localization
	- L\. History Commands
	- M\. Sample .bashrc and .bash_profile Files
	- N\. Converting DOS Batch Files to Shell Scripts
	- O\. Exercises
		- O.1 Analyzing Scripts
		- O.2 Writing Scripts
	- P\. Revision History
	- Q\. Download and Mirror Sites
	- R\. To Do List
	- S\. Copyright
	- T\. ASCII Table
- Index
- List of Tables
- List of Examples

## 翻译流程
### 初始化
1. 首先fork项目
2. 把fork过去的项目clone到本地
3. 命令行下运行 `git checkout -b dev` 创建一个新分支
4. 运行 `git remote add upstream https://github.com/LinuxStory/Advanced-Bash-Scripting-Guide-in-Chinese.git` 添加远端库
5. 运行 `git remote update`更新
6. 运行 `git fetch upstream master` 拉取更新到本地
7. 运行 `git rebase upstream/master` 将更新合并到你的分支

初始化只需要做一遍，之后请在dev分支进行修改。

如果修改过程中项目有更新，请重复5、6、7步。

### 翻译流程
1. 保证在在dev分支中
2. 打开README.md，在翻译进度后加上你自己的github名
	> 1\. Shell Programming! [@imcmy]
3. 本地提交修改，写明提交信息
4. push到你fork的项目中，然后登录GitHub
5. 在你fork的项目的首页可以看到一个 `pull request` 按钮，点击它，填写说明信息，然后提交即可
	> 为了不重复工作，请等待我们确认了你的pull request(即你的名字出现在项目中时)，再进行翻译工作
6. 进行翻译，重复3-5步提交翻译的作品

## 翻译建议
1. 使用markdown进行翻译，文件名必须使用英文
2. 翻译后的文档请放到source文件夹下的对应章节中，然后pull request即可
3. 有任何问题随时欢迎发issue
4. 术语尽量保证和已翻译的一致，也可以查询[微软术语搜索](http://www.microsoft.com/Language/zh-cn/Search.aspx)
5. 你可以将你认为是术语的词汇加入术语表`term.md`中

## 关于版权
根据原著作者的要求，翻译成果属于公有领域(CC0)。翻译参与人员及原著作者Mendel Cooper享有署名权