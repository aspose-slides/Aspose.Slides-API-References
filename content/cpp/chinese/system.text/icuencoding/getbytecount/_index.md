---
title: GetByteCount()
second_title: Aspose.Slides for C++ API 参考
description: 获取对字符缓冲区进行编码所需的字符数。
type: docs
weight: 27
url: /zh/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) 方法

获取对字符缓冲区进行编码所需的字符数。

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chars | const char_t * | 字符缓冲区。 |
| count | int | [Buffer](../../../system/buffer/) 大小。 |

### 返回值

所需缓冲区大小。

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>, int, int) 方法

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) 方法

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) 方法

RTTI.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

## ICUEncoding::GetByteCount(const String\&) 方法

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>) 方法

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

## ICUEncoding::GetByteCount(const char_t *, int) 方法

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [ICUEncoding](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Text](../../)
* 库 [Aspose.Slides](../../../)