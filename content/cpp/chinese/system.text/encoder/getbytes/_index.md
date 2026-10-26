---
title: GetBytes()
second_title: Aspose.Slides for C++ API 参考
description: 获取对缓冲区进行编码后产生的字节。
type: docs
weight: 53
url: /zh/system.text/encoder/getbytes/
---
## Encoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) method

获取对缓冲区进行编码后产生的字节。

```cpp
virtual int System::Text::Encoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 要编码的字符。 |
| charIndex | int | 源数组偏移量。 |
| charCount | int | 源子数组长度。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 目标字节缓冲区。 |
| byteIndex | int | 目标缓冲区偏移量。 |
| flush | **bool** | 如果为 true，则在计算后清除内部编码器状态。 |

### 返回值

写入的字节数。

## Encoder::GetBytes(const char_t *, int, uint8_t *, int, bool) method

获取对缓冲区进行编码后产生的字节。

```cpp
virtual int System::Text::Encoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | 要编码的字符。 |
| charCount | int | 源数组长度。 |
| bytes | **uint8_t** * | 目标字节缓冲区。 |
| byteCount | int | 目标缓冲区大小。 |
| flush | **bool** | 如果为 true，则在计算后清除内部编码器状态。 |

### 返回值

写入的字节数。

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [Encoder](../)
* 命名空间 [System::Text](../../)
* 库 [Aspose.Slides](../../../)