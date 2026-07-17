---
title: StackTrace()
second_title: Aspose.Slides for C++ API 参考
description: 创建描述当前堆栈状态的堆栈跟踪。
type: docs
weight: 1
url: /zh/system.diagnostics/stacktrace/stacktrace/
---
## StackTrace::StackTrace() 构造函数


创建描述当前堆栈状态的堆栈跟踪。

```cpp
System::Diagnostics::StackTrace::StackTrace()
```

## StackTrace::StackTrace(bool) 构造函数


创建描述当前堆栈状态的堆栈跟踪。

```cpp
System::Diagnostics::StackTrace::StackTrace(bool isFileInfoNeeded)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isFileInfoNeeded | **bool** | 若为 true，则捕获文件名、行号和列号；否则为 false |

## StackTrace::StackTrace(const StackTrace\&) 构造函数


不复制。

```cpp
System::Diagnostics::StackTrace::StackTrace(const StackTrace &)=delete
```

## 另见

* 类 [StackTrace](../)
* 命名空间 [System::Diagnostics](../../)
* 库 [Aspose.Slides](../../../)