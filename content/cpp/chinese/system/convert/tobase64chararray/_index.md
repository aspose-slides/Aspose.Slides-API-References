---
title: ToBase64CharArray()
second_title: Aspose.Slides C++ API 参考
description: Base-64 对指定字节数组中的一定范围元素进行编码，并将编码后的数据存储为 Unicode 字符数组。
type: docs
weight: 27
url: /zh/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) method

Base-64 对指定字节数组中的一定范围元素进行编码，并将编码后的数据存储为 Unicode 字符数组。

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```

### Arguments

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 包含待编码元素范围的字节数组 |
| offset_in | int | 输入数组中元素的索引，表示编码范围的起始位置 |
| length | int | 待编码元素范围的长度 |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | 指向输出数组的常量引用，用于存放生成的数据 |
| offset_out | int | 输出数组中开始写入生成数据的索引 |
| insert_line_breaks | **bool** | 指定是否在每 76 个 base-64 字符后向输出数组中插入换行符 |

### Return Value

写入输出数组的字符数量

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) method

Base-64 对指定字节数组中的一定范围元素进行编码，并将编码后的数据存储为 Unicode 字符数组。

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```

### Arguments

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 包含待编码元素范围的字节数组 |
| offset_in | int | 输入数组中元素的索引，表示编码范围的起始位置 |
| length | int | 待编码元素范围的长度 |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 指向输出数组的常量引用，用于存放生成的数据 |
| offset_out | int | 输出数组中开始写入生成数据的索引 |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | 指定 base-64 编码数据的格式化选项 |

### Return Value

写入输出数组的字符数量

## 参见

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)