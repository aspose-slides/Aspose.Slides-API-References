---
title: ToString()
second_title: Aspose.Slides for C++ API 参考
description: 将指定字节数组的所有值转换为其十六进制字符串表示形式。十六进制表示中使用的字母大小写以及在每对相邻字节之间插入的分隔符通过相应的参数指定。
type: docs
weight: 157
url: /zh/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) 方法

将指定字节数组的所有值转换为它们的十六进制字符串表示形式。十六进制表示中使用的字母大小写以及在每对相邻字节之间插入的分隔符通过相应的参数指定。

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要转换的字节 |
| uppercase | **bool** | 指定在结果十六进制表示中使用的字母大小写 |
| separator | const [String](../../string/)\& | 用于在结果字符串中每对相邻字节之间插入的分隔符字符串 |

### 返回值

[String](../../string/) 包含指定字节数组的十六进制表示

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) 方法

将指定字节数组的值从指定索引开始转换为其十六进制字符串表示形式。

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要转换的字节 |
| startIndex | int | 在指定数组中开始转换的索引 |

### 返回值

[String](../../string/) 包含指定数组中指定范围元素的十六进制表示

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) 方法

将指定字节数组的一段值转换为其十六进制字符串表示形式。

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要转换的字节 |
| startIndex | int | 在指定数组中转换的字节数组元素范围的起始索引 |
| length | int | 要转换的字节数组元素范围的长度 |

### 返回值

[String](../../string/) 包含指定数组中指定范围元素的十六进制表示

## 另见

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)