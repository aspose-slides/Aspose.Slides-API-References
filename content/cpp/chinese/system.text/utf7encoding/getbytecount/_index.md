---
title: GetByteCount()
second_title: Aspose.Slides for C++ API 参考
description: 获取对字符缓冲区进行编码所需的字符数。
type: docs
weight: 157
url: /zh/system.text/utf7encoding/getbytecount/
---
## UTF7Encoding::GetByteCount(const char_t *, int) 方法

获取对字符缓冲区进行编码所需的字符数。

```cpp
int System::Text::UTF7Encoding::GetByteCount(const char_t *chars, int count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chars | const char_t * | 字符缓冲区。 |
| count | int | [Buffer](../../../system/buffer/) 大小。 |

### 返回值

所需缓冲区大小。

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) 方法

获取对字符缓冲区进行编码所需的字符数。

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 字符缓冲区。 |
| index | int | 切片起始位置。 |
| count | int | 切片大小。 |

### 返回值

所需缓冲区大小。

## UTF7Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) 方法

获取对字符缓冲区进行编码所需的字符数。

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | 字符缓冲区。 |
| index | int | 切片起始位置。 |
| count | int | 切片大小。 |

### 返回值

所需缓冲区大小。

## UTF7Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) 方法

获取对字符缓冲区进行编码所需的字符数。

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | 字符缓冲区。 |
| index | int | 切片起始位置。 |
| count | int | 切片大小。 |

### 返回值

所需缓冲区大小。

## UTF7Encoding::GetByteCount(const String\&) 方法

获取对字符串进行编码所需的字符数。

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) 要编码的。 |

### 返回值

所需缓冲区大小。

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>) 方法

获取对字符缓冲区进行编码所需的字符数。

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 字符缓冲区。 |

### 返回值

所需缓冲区大小。

## UTF7Encoding::GetByteCount(const char_t *, int) 方法

获取对字符缓冲区进行编码所需的字符数。

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chars | const char_t * | 字符缓冲区。 |
| count | int | [Buffer](../../../system/buffer/) 大小。 |

### 返回值

所需缓冲区大小。

## 另请参阅

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)