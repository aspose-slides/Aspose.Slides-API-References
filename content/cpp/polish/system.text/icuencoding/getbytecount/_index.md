---
title: GetByteCount()
second_title: Odniesienie API Aspose.Slides dla C++
description: Zwraca liczbę znaków potrzebnych do zakodowania bufora znaków.
type: docs
weight: 27
url: /pl/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) metoda


Zwraca liczbę znaków potrzebnych do zakodowania bufora znaków.

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | const char_t * | Bufor znaków. |
| count | int | [Buffer](../../../system/buffer/) rozmiar. |

### Wartość zwracana

Wymagany rozmiar bufora.

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

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [ICUEncoding](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)