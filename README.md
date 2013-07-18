MyOS
====
This is my first OS. 我的第一个操作系统
------------------------------


概述：
--------
本操作系统仿照[川合秀实](http://hrb.osask.jp/)先生的“haribote”系统编写<br />
实现基本的图形界面操作，具备多任务处理、汉字显示、文件压缩等功能

许可证:
--------
[The MIT license.](http://zh.wikipedia.org/wiki/MIT%E8%A8%B1%E5%8F%AF%E8%AD%89)<br /> 

相关知识、技术：
----------------
计算机基本构造、汇编语言、C语言、操作系统原理等

相关文件说明：
----------------
z_tools：     工具软件（部分软件版权归[川合秀实](http://hrb.osask.jp/)先生所有，作者保留版权）文件夹，Makefile自动调用<br />
cmd.bat:      调用系统cmd的批处理文件<br />
Makefile：    自动化编译文件<br />
dogged.img：  img镜像文件，可通过WinISO等软件制作ISO镜像文件<br />
*.c:          系统相关c程序文件<br />
*.nas：       系统相关汇编程序文件<br />
hankaku.txt： 字库文件<br />


系统运行方式：
-----------------
双击cmd.bat打开命令行，输入make run运行。<br />
或者使用相关软件把生成的IMG文件转换为ISO文件直接使用。

目前进度：
--------------
1.完成启动区[100%]<br />
2.导入C语言[100%]<br />
3.绘制基本界面[100%]<br />
4.显示文字[100%]<br />
5.GDT/IDT初始化[100%]<br />
6.分割代码[100%]<br />
7.中断处理制作[100%]<br />
8.获取按键编码[100%]<br />
9.FIFO缓冲区制作[100%]<br />
10.鼠标信息获取[80%]<br />

更多信息
---------
欢迎访问我的博客获得更多相关的信息:<br />
1.[scusjs的专栏](http://blog.csdn.net/scusjs)<br />  
2.[成长的路，点滴记录](http://falcon_s.byethost15.com/)<br />




By SCUSJS



