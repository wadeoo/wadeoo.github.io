---
description: 笔记
title: 学习笔记
permalink: /notes/
---


HINSTANCE represents a module (a particular running copy of an EXE or a DLL); HWND represents a window. A single application instance would have a single HINSTANCE handle (leaving DLLs aside for a moment), but would often create multiple windows, each with its own HWND.

HINSTANCE handle is passed by the OS to WinMain or DllMain when the module is loaded. HWND handle is returned by CreateWindow or similar, when the window is created.

redirect是由客户端完成的
forward是由服务器端完成的

listen(SOCKET socket,int backlog)The listen backlog is a queue which is used by the operating system to store connections that have been accepted by the TCP stack but not, yet, by your program. Conceptually, 
when a client connects it's placed in this queue until your Accept () code removes it and hands it to your program.

(right-left)/2+left 和(right+left)/2同样是计算中位数的方法,但是当right和left都很大的时候,right+left 更有可能出现整型溢出的问题.

左移右移比乘除法更加高效

strlen() 会截断'\0' length() size() 可以返回真实长度

cpp map insert no-op if key already existed

cpp if(-1) 是可以进入的

cpp sgi stl 栈和队列是容器适配器 栈的底层容器可以由数组或链表或deque实现 
声明的是否可以指定底层容器 默认deque


递归算法三部曲:1.确定参数和返回值2,终止条件3单层递归逻辑

