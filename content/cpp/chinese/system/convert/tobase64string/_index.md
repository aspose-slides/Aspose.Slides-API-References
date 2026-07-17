---
title: ToBase64String()
second_title: Aspose.Slides for C++ API 参考
description: Base-64 对指定字节数组中的元素进行编码，并将编码后的数据作为字符串返回。
type: docs
weight: 40
url: /zh/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) 方法


Base-64 对指定字节数组中的元素进行编码，并将编码后的数据作为字符串返回。

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 要编码的字节数组 |
| insert_line_breaks | **bool** | 指定是否在每 76 个 base-64 字符后在输出字符串中插入换行字符 |

### 返回值

包含输入数组的 base-64 编码表示的字符串

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) 方法


Base-64 对指定字节数组中一定范围的元素进行编码，并将编码后的数据作为字符串返回。

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 包含要编码元素范围的字节数组 |
| offset_in | int | 输入数组中开始编码范围的元素索引 |
| length | int | 要编码的元素范围的长度 |
| insert_line_breaks | **bool** | 指定是否在每 76 个 base-64 字符后在输出字符串中插入换行字符 |

### 返回值

包含输入数组中元素范围的 base-64 编码表示的字符串

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) 方法


Base-64 对指定字节数组中的元素进行编码，并将编码后的数据作为字符串返回。

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 要编码的字节数组 |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | 指定 base-64 编码数据的格式选项 |

### 返回值

包含输入数组的 base-64 编码表示的字符串

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) 方法


Base-64 对指定字节数组中一定范围的元素进行编码，并将编码后的数据作为字符串返回。

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 包含要编码元素范围的字节数组 |
| offset_in | int | 输入数组中开始编码范围的元素索引 |
| length | int | 要编码的元素范围的长度 |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | 指定 base-64 编码数据的格式选项 |

### 返回值

包含输入数组中元素范围的 base-64 编码表示的字符串

## 另请参见

* 枚举 [Base64FormattingOptions](../../base64formattingoptions/)
* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [String](../../string/)
* 结构体 [Convert](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)