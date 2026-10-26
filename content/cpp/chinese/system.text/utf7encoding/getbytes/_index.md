---
title: GetBytes()
second_title: Aspose.Slides C++ API 参考
description: 获取对字符缓冲区进行编码后产生的字节。
type: docs
weight: 66
url: /zh/system.text/utf7encoding/getbytes/
---
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) 方法

获取对字符缓冲区进行编码后产生的字节。

```cpp
int System::Text::UTF7Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 要编码的字符。 |
| char_index | int | 字符切片的起始位置。 |
| char_count | int | 要转换的字符数。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用于放置字符。 |
| byte_index | int | 输出缓冲区偏移量。 |

### 返回值

已写入的字节数。

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) 方法

获取对字符缓冲区进行编码后产生的字节。

```cpp
int System::Text::UTF7Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | 要编码的字符。 |
| char_count | int | 要转换的字符数。 |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) 用于放置字符。 |
| byte_count | int | 输出缓冲区大小。 |

### 返回值

已写入的字节数。

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) 方法

获取对字符缓冲区进行编码后产生的字节。

```cpp
int System::Text::UTF7Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) 用于编码。 |
| char_index | int | 字符切片的起始位置。 |
| char_count | int | 要转换的字符数。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用于放置字符。 |
| byte_index | int | 输出缓冲区偏移量。 |

### 返回值

已写入的字节数。

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) 方法

获取对字符缓冲区进行编码后产生的字节。

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 要编码的字符。 |
| char_index | int | 字符切片的起始位置。 |
| char_count | int | 要转换的字符数。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用于放置字符。 |
| byte_index | int | 输出缓冲区偏移量。 |

### 返回值

已写入的字节数。

## UTF7Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) 方法

获取对字符缓冲区进行编码后产生的字节。

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | 要编码的字符。 |
| char_index | int | 字符切片的起始位置。 |
| char_count | int | 要转换的字符数。 |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用于放置字符。 |
| byte_index | int | 输出缓冲区偏移量。 |

### 返回值

已写入的字节数。

## UTF7Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) 方法

获取对字符缓冲区进行编码后产生的字节。

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | 要编码的字符。 |
| char_index | int | 字符切片的起始位置。 |
| char_count | int | 要转换的字符数。 |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) 用于放置字符。 |
| byte_index | int | 输出缓冲区偏移量。 |

### 返回值

已写入的字节数。

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) 方法

获取对字符缓冲区进行编码后产生的字节。

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) 用于编码。 |
| char_index | int | 字符切片的起始位置。 |
| char_count | int | 要转换的字符数。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用于放置字符。 |
| byte_index | int | 输出缓冲区偏移量。 |

### 返回值

已写入的字节数。

## UTF7Encoding::GetBytes(const String\&) 方法

获取对字符缓冲区进行编码后产生的字节。

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) 用于编码。 |

### 返回值

[Buffer](../../../system/buffer/) 保存被编码字符的表示。

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) 方法

获取对字符缓冲区进行编码后产生的字节。

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 要编码的字符。 |
| index | int | 字符切片的起始位置。 |
| count | int | 要转换的字符数。 |

### 返回值

[Buffer](../../../system/buffer/) 保存被编码字符的表示。

## UTF7Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) 方法

获取对字符缓冲区进行编码后产生的字节。

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | 要编码的字符。 |
| index | int | 字符切片的起始位置。 |
| count | int | 要转换的字符数。 |

### 返回值

[Buffer](../../../system/buffer/) 保存被编码字符的表示。

## UTF7Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) 方法

获取对字符缓冲区进行编码后产生的字节。

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | 要编码的字符。 |
| index | int | 字符切片的起始位置。 |
| count | int | 要转换的字符数。 |

### 返回值

[Buffer](../../../system/buffer/) 保存被编码字符的表示。

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>) 方法

获取对字符缓冲区进行编码后产生的字节。

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 要编码的字符。 |

### 返回值

[Buffer](../../../system/buffer/) 保存被编码字符的表示。

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) 方法

获取对字符缓冲区进行编码后产生的字节。

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | 要编码的字符。 |
| char_count | int | 要转换的字符数。 |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) 用于放置字符。 |
| byte_count | int | 输出缓冲区大小。 |

### 返回值

已写入的字节数。

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)