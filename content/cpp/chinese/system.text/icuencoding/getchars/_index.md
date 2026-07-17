---
title: GetChars()
second_title: Aspose.Slides for C++ API 参考
description: 获取从解码字节缓冲区得到的字符。
type: docs
weight: 66
url: /zh/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) method


获取从解码字节缓冲区得到的字符。

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) 用于读取字节。 |
| byte_count | int | 输入缓冲区大小。 |
| chars | char_t * | [Buffer](../../../system/buffer/) 用于放置字符。 |
| char_count | int | 输出缓冲区大小。 |

### 返回值

已写入字符的数量。

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method


获取从解码字节缓冲区得到的字符。

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用于读取字节。 |
| byte_index | int | 输入缓冲区偏移。 |
| byte_count | int | 输入缓冲区大小。 |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) 用于放置字符。 |
| char_index | int | 输出缓冲区偏移。 |

### 返回值

已写入字符的数量。

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) method


获取从解码字节缓冲区得到的字符。

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用于读取字节。 |
| index | int | 输入缓冲区偏移。 |
| count | int | 输入缓冲区大小。 |

### 返回值

[Buffer](../../../system/buffer/) 已解码字符的数量。

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) method


获取从解码字节缓冲区得到的字符。

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用于读取字节。 |

### 返回值

[Buffer](../../../system/buffer/) 已解码字符的数量。

## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) method


获取从解码字节缓冲区得到的字符。

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) 用于读取字节。 |
| byte_count | int | 输入缓冲区大小。 |
| chars | char_t * | [Buffer](../../../system/buffer/) 用于放置字符。 |
| char_count | int | 输出缓冲区大小。 |

### 返回值

已写入字符的数量。

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [ICUEncoding](../)
* 命名空间 [System::Text](../../)
* 库 [Aspose.Slides](../../../)