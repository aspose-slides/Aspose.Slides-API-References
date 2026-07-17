---
title: GetString()
second_title: Aspose.Slides C++ API 参考
description: 将字节缓冲区解码为字符串。
type: docs
weight: 313
url: /zh/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) 方法

将字节缓冲区解码为字符串。

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) 用于读取字节。 |
| byte_count | int | 输入缓冲区大小。 |

### 返回值

[String](../../../system/string/) 已解码字符的数量。

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) 方法

将字节缓冲区解码为字符串。

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) 用于读取字节。 |

### 返回值

[String](../../../system/string/) 已解码字符的数量。

## Encoding::GetString(ArrayPtr\<uint8_t\>) 方法

将字节缓冲区解码为字符串。

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用于读取字节。 |

### 返回值

[String](../../../system/string/) 已解码字符的数量。

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) 方法

将字节缓冲区解码为字符串。

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) 用于读取字节。 |

### 返回值

[String](../../../system/string/) 已解码字符的数量。

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) 方法

将字节缓冲区解码为字符串。

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) 用于读取字节。 |

### 返回值

[String](../../../system/string/) 已解码字符的数量。

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) 方法

将字节缓冲区解码为字符串。

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用于读取字节。 |
| index | int | 输入缓冲区偏移。 |
| count | int | 输入缓冲区大小。 |

### 返回值

[String](../../../system/string/) 已解码字符的数量。

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) 方法

将字节缓冲区解码为字符串。

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) 用于读取字节。 |
| index | int | 输入缓冲区偏移。 |
| count | int | 输入缓冲区大小。 |

### 返回值

[String](../../../system/string/) 已解码字符的数量。

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) 方法

将字节缓冲区解码为字符串。

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) 用于读取字节。 |
| index | int | 输入缓冲区偏移。 |
| count | int | 输入缓冲区大小。 |

### 返回值

[String](../../../system/string/) 已解码字符的数量。

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [Encoding](../)
* 类 [ReadOnlySpan](../../../system/readonlyspan/)
* 命名空间 [System::Text](../../)
* 库 [Aspose.Slides](../../../)