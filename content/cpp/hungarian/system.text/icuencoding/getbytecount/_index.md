---
title: GetByteCount()
second_title: Aspose.Slides C++ API-referencia
description: Visszaadja a karakterpuffer kódolásához szükséges karakterek számát.
type: docs
weight: 27
url: /hu/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) method

A karakterpuffer kódolásához szükséges karakterek számát adja vissza.

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | const char_t * | Karakterpuffer. |
| count | int | [Buffer](../../../system/buffer/) méret. |

### Visszatérési érték

Szükséges pufferméret.

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

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [ICUEncoding](../)
* Osztály [String](../../../system/string/)
* Névtere [System::Text](../../)
* Library [Aspose.Slides](../../../)