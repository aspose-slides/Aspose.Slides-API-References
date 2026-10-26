---
title: STDIOStreamWrappingMode
second_title: Aspose.Slides C++ API 参考
description: "指定包装器将在类似 std::iostream 的流上执行的 I/O 操作模式。"
type: docs
weight: 573
url: /zh/system.io/stdiostreamwrappingmode/
---
## STDIOStreamWrappingMode 枚举

指定包装器将在类似 std::iostream 的流上执行的 I/O 操作模式。

```cpp
enum class STDIOStreamWrappingMode
```

### 值

| Name | Value | Description |
| --- | --- | --- |
| Binary | 0 | 一种模式，允许输入操作将 char_type 类型的流数据解码为字节，并将字节编码为 char_type 数据用于输出操作。 |
| Conversion | 1 | 一种模式，允许输入操作将流数据从 char_type 类型转换为 **uint8_t** 类型，并在输出操作中反向转换。 |

## 另见

* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)