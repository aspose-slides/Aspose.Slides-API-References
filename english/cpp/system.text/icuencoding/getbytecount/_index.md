---
title: GetByteCount()
second_title: Aspose.Slides for C++ API Reference
description: Get the number of characters needed to encode a character buffer.
type: docs
weight: 27
url: /cpp/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) method


Get the number of characters needed to encode a character buffer.

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Characters buffer. |
| count | int | [Buffer](../../../system/buffer/) size. |

### Return Value

Required buffer size.

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>, int, int) method


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) method


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) method


RTTI.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

## ICUEncoding::GetByteCount(const String\&) method


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>) method


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

## ICUEncoding::GetByteCount(const char_t *, int) method


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)