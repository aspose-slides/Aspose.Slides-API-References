---
title: GetByteCount()
second_title: Aspose.Slides för C++ API-referens
description: Hämta antalet tecken som behövs för att koda en teckenbuffert.
type: docs
weight: 27
url: /sv/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) metod

Hämta antalet tecken som behövs för att koda en teckenbuffer.

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | const char_t * | Teckenbuffert. |
| count | int | [Buffer](../../../system/buffer/) storlek. |

### Returvärde

Krävd buffertstorlek.

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>, int, int) metod

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) metod

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) metod

RTTI.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

## ICUEncoding::GetByteCount(const String\&) metod

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>) metod

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

## ICUEncoding::GetByteCount(const char_t *, int) metod

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [ICUEncoding](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)