---
title: SystemIOStreamWrappingMode
second_title: Aspose.Slides for C++ API 参考
description: "指定包装器将在类似 System::IO::Stream 的流上执行的 I/O 操作模式。"
type: docs
weight: 599
url: /zh/system.io/systemiostreamwrappingmode/
---
## SystemIOStreamWrappingMode 枚举

指定包装器将在 [System::IO::Stream](../stream/) 类流上执行的 I/O 操作模式。

```cpp
enum class SystemIOStreamWrappingMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Binary | 0 | 允许输入操作将流字节编码为 char_type 数据，并在输出操作中将 char_type 数据解码为流字节的模式。 |
| Conversion | 1 | 允许输入操作将流字节从 **uint8_t** 类型转换为 char_type 类型，并在输出操作中进行反向转换的模式。 |

## 参见

* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)