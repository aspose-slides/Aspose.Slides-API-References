---
title: Start()
second_title: Aspose.Slides C++ API 参考
description: 使用预定义参数启动进程。
type: docs
weight: 14
url: /zh/system.diagnostics/process/start/
---
## Process::Start() 方法

使用预定义参数启动进程。

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) 方法

使用指定的路径和参数启动进程。

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) 路径。 |
| arguments | const [String](../../../system/string/)\& | [Process](../) 参数。 |

### 返回值

[Object](../../../system/object/) 附加到新启动的进程。

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) 方法

使用指定的路径和参数启动进程。

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | 关于要启动的进程的信息。 |

### 返回值

[Object](../../../system/object/) 附加到新启动的进程。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Process](../)
* 类 [String](../../../system/string/)
* 类 [ProcessStartInfo](../../processstartinfo/)
* 命名空间 [System::Diagnostics](../../)
* 库 [Aspose.Slides](../../../)