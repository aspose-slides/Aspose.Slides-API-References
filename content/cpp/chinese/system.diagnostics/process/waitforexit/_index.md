---
title: WaitForExit()
second_title: Aspose.Slides C++ API 参考
description: 等待进程退出。未实现。
type: docs
weight: 27
url: /zh/system.diagnostics/process/waitforexit/
---
## Process::WaitForExit(int) 方法

等待进程退出。未实现。

```cpp
bool System::Diagnostics::Process::WaitForExit(int milliseconds)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| milliseconds | int | 最大等待延迟。 |

### 返回值

如果进程已完成返回 True，超时则返回 false。

## Process::WaitForExit() 方法

等待进程退出，直到完成才返回。

```cpp
void System::Diagnostics::Process::WaitForExit()
```

## 另见

* 类 [Process](../)
* 命名空间 [System::Diagnostics](../../)
* 库 [Aspose.Slides](../../../)