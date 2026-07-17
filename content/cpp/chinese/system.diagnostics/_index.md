---
title: "System::Diagnostics"
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 469
url: /zh/system.diagnostics/
---
## 类

| 类 | 描述 |
| --- | --- |
| [FileVersionInfo](./fileversioninfo/) | 提供文件版本信息。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [PerformanceCounter](./performancecounter/) | 用于编译使用 PerformanceCounter 的翻译代码的虚拟类。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Process](./process/) | 封装进程信息及其操作。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [ProcessStartInfo](./processstartinfo/) | 描述进程启动参数。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [StackFrame](./stackframe/) | 获取单个堆栈帧的信息。仅限 MSVS。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [StackTrace](./stacktrace/) | 堆栈帧集合。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Stopwatch](./stopwatch/) | 允许时间测量。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [TraceListener](./tracelistener/) | 用于响应调试和跟踪信息的接口。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |

## 结构体

| 结构体 | 描述 |
| --- | --- |
| [Debug](./debug/) | 收集调试方法，允许向已注册的监听器发送调试信息。所有输出函数仅在 [Debug](./debug/) 中工作。这是一个静态类型，没有实例服务。决不应以任何方式创建其实例。 |
| [Debugger](./debugger/) | [Debugger](./debugger/) 接口。这是一个静态类型，没有实例服务。决不应以任何方式创建其实例。 |
| [Trace](./trace/) | 提供访问调试器跟踪（如果有）的接口。仅在 [Debug](./debug/) 模式下工作。这是一个静态类型，没有实例服务。决不应以任何方式创建其实例。 |

## 枚举

| 枚举 | 描述 |
| --- | --- |
| [ProcessWindowStyle](./processwindowstyle/) | 进程窗口的样式。 |
| [TraceEventType](./traceeventtype/) | 标识导致跟踪的事件类型。 |
| [TraceLevel](./tracelevel/) | 指定 [System.Diagnostics.Debug](./debug/)、[System.Diagnostics.Trace](./trace/) 和 System.Diagnostics.TraceSwitch 类的输出消息。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [StopwatchPtr](./stopwatchptr/) | 指针类型。