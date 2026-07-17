---
title: GetFrame()
second_title: Aspose.Slides C++ API 参考
description: 获取堆栈帧。
type: docs
weight: 40
url: /zh/system.diagnostics/stacktrace/getframe/
---
## StackTrace::GetFrame(uint32_t) 方法

获取堆栈帧。

```cpp
virtual SharedPtr<StackFrame> System::Diagnostics::StackTrace::GetFrame(uint32_t index)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **uint32_t** | 堆栈帧索引，必须在 0 到 FrameCount-1 之间。 |

### 返回值

可用的堆栈帧。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [StackFrame](../../stackframe/)
* 类 [StackTrace](../)
* 命名空间 [System::Diagnostics](../../)
* 库 [Aspose.Slides](../../../)