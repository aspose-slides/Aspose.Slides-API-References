---
title: GetChars()
second_title: Aspose.Slides for C++ API 参考
description: 获取解码缓冲区后得到的字符。
type: docs
weight: 53
url: /zh/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) 方法


获取解码缓冲区后得到的字符。

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 待解码的字节。 |
| byteIndex | int | 输入缓冲区偏移量。 |
| byteCount | int | 输入缓冲区大小。 |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 目标字符缓冲区。 |
| charIndex | int | 目标数组偏移量。 |

### 返回值

写入的字符数。

## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) 方法


获取解码缓冲区后得到的字符。

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 待解码的字节。 |
| byteIndex | int | 输入缓冲区偏移量。 |
| byteCount | int | 输入缓冲区大小。 |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 目标字符缓冲区。 |
| charIndex | int | 目标数组偏移量。 |
| flush | **bool** | 如果为 true，则在计算后清除内部解码器状态。 |

### 返回值

写入的字符数。

## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) 方法


获取解码缓冲区后得到的字符。

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | 待解码的字节。 |
| byteCount | int | 输入缓冲区大小。 |
| chars | char_t * | 目标字符缓冲区。 |
| charCount | int | 目标数组大小。 |
| flush | **bool** | 如果为 true，则在计算后清除内部解码器状态。 |

### 返回值

写入的字符数。

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [Decoder](../)
* 命名空间 [System::Text](../../)
* 库 [Aspose.Slides](../../../)