---
title: Convert()
second_title: Aspose.Slides for C++ API 参考
description: 将字节转换为字符。
type: docs
weight: 1
url: /zh/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int&, int&, bool&) 方法

将字节转换为字符。

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 要解码的字节。 |
| byteCount | int | 输入缓冲区大小。 |
| chars | char_t * | 目标字符缓冲区。 |
| charCount | int | 目标数组大小。 |
| flush | **bool** | 如果为 true，则在计算后清除内部解码器状态。 |
| bytesUsed | int\& | 引用变量以存储读取的字节计数。 |
| charsUsed | int\& | 引用变量以存储写入的字符计数。 |
| completed | **bool**\& | 引用变量；如果输入缓冲区已耗尽则设为 true，否则设为 false。 |

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int&, int&, bool&) 方法

将字节转换为字符。

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要解码的字节。 |
| byteIndex | int | 输入缓冲区偏移。 |
| byteCount | int | 输入缓冲区大小。 |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 目标字符缓冲区。 |
| charIndex | int | 目标数组偏移。 |
| charCount | int | 目标数组大小。 |
| flush | **bool** | 如果为 true，则在计算后清除内部解码器状态。 |
| bytesUsed | int\& | 引用变量以存储读取的字节计数。 |
| charsUsed | int\& | 引用变量以存储写入的字符计数。 |
| completed | **bool**\& | 引用变量；如果输入缓冲区已耗尽则设为 true，否则设为 false。 |

## 另请参见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [EncodingDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)