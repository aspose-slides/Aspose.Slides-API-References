---
title: Convert()
second_title: Aspose.Slides for C++ API 参考
description: 将字符转换为字节。
type: docs
weight: 1
url: /zh/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) 方法

将字符转换为字节。

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chars | const char_t * | 待编码的字符。 |
| charCount | int | 输入缓冲区大小。 |
| bytes | **uint8_t** * | 目标字节缓冲区。 |
| byteCount | int | 目标数组大小。 |
| flush | **bool** | 如果为 true，则在计算后清除内部编码器状态。 |
| charsUsed | int\& | 指向存储已读取字符计数的变量的引用。 |
| bytesUsed | int\& | 指向存储已写入字节计数的变量的引用。 |
| completed | **bool**\& | 指向变量的引用，如果输入缓冲区已耗尽则设为 true，否则设为 false。 |

## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) 方法

将字符转换为字节。

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 待编码的字符。 |
| charIndex | int | 输入缓冲区偏移。 |
| charCount | int | 输入缓冲区大小。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 目标字节缓冲区。 |
| byteIndex | int | 目标数组偏移。 |
| byteCount | int | 目标数组大小。 |
| flush | **bool** | 如果为 true，则在计算后清除内部编码器状态。 |
| charsUsed | int\& | 指向存储已读取字符计数的变量的引用。 |
| bytesUsed | int\& | 指向存储已写入字节计数的变量的引用。 |
| completed | **bool**\& | 指向变量的引用，如果输入缓冲区已耗尽则设为 true，否则设为 false。 |

## 参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [EncodingEncoder](../)
* 命名空间 [System::Text](../../)
* 库 [Aspose.Slides](../../../)