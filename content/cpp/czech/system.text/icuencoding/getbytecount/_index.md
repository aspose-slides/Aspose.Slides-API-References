---
title: GetByteCount()
second_title: Aspose.Slides pro C++ API referenci
description: Získá počet znaků potřebných k zakódování znakového bufferu.
type: docs
weight: 27
url: /cs/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) metoda

Získá počet znaků potřebných k zakódování znakového bufferu.

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | const char_t * | Znakový buffer. |
| count | int | [Buffer](../../../system/buffer/) velikost. |

### Návratová hodnota

Požadovaná velikost bufferu.

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>, int, int) metoda

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) metoda

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) metoda

RTTI.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

## ICUEncoding::GetByteCount(const String\&) metoda

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>) metoda

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

## ICUEncoding::GetByteCount(const char_t *, int) metoda

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

## Viz také

* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Třída [ICUEncoding](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Text](../../)
* Knihovna [Aspose.Slides](../../../)