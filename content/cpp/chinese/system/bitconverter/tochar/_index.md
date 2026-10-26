---
title: ToChar()
second_title: Aspose.Slides for C++ API 参考
description: 将指定数组中从指定索引开始的两个字节转换为 char_t 值。
type: docs
weight: 40
url: /zh/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) method

将指定数组中从指定索引开始的两个字节转换为 char_t 值。

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Arguments

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要转换的字节 |
| startIndex | int | 数组中开始取字节进行转换的索引 |

### Return Value

char_t value 转换后得到的

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) method

将指定数组中从指定索引开始的两个字节转换为 char_t 值。

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Arguments

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 包含要转换的字节 |
| startIndex | int | 数组中开始取字节进行转换的索引 |

### Return Value

char_t value 转换后得到的

## See Also

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [BitConverter](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)