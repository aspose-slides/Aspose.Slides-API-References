---
title: Trace
second_title: Aspose.Slides for C++ API 参考
description: 提供访问调试器跟踪（如果有）的接口。仅在 Debug 模式下工作。这是一个没有实例服务的静态类型。绝不应以任何方式创建其实例。
type: docs
weight: 131
url: /zh/system.diagnostics/trace/
---
## Trace struct

提供访问调试器跟踪的接口（如果有）。仅在 [Debug](../debug/) 模式下工作。这是一个没有实例服务的静态类型。绝不应以任何方式创建其实例。

```cpp
class Trace
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static void [Flush](./flush/)() | 刷新输出缓冲区，并导致缓冲的数据写入监听器。 |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | 将行写入调试器跟踪。 |
## 另见

* 命名空间 [System::Diagnostics](../)
* 库 [Aspose.Slides](../../)