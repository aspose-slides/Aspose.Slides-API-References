---
title: GetCharCount()
second_title: Aspose.Slides for C++ API 参考
description: 获取解码缓冲区所需的字符数量。
type: docs
weight: 40
url: /zh/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) 方法

获取解码缓冲区所需的字符数量。

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要解码的字节。 |
| index | int | [Buffer](../../../system/buffer/) 偏移量。 |
| count | int | 要解码的字节数。 |

### 返回值

解码缓冲区所需的字符数量。

## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) 方法

获取解码缓冲区所需的字符数量。

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要解码的字节。 |
| index | int | [Buffer](../../../system/buffer/) 偏移量。 |
| count | int | 要解码的字节数。 |
| flush | **bool** | 如果为 true，则在计算后清除内部解码器状态。 |

### 返回值

解码缓冲区所需的字符数量。

## ICUDecoder::GetCharCount(const uint8_t *, int, bool) 方法

获取解码缓冲区所需的字符数量。

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 要解码的字节。 |
| count | int | 要解码的字节数。 |
| flush | **bool** | 如果为 true，则在计算后清除内部解码器状态。 |

### 返回值

解码缓冲区所需的字符数量。

## 参见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)