---
title: GetByteCount()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Pobiera liczbę znaków potrzebnych do zakodowania bufora znaków.
type: docs
weight: 235
url: /pl/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) metoda

Pobiera liczbę znaków potrzebnych do zakodowania bufora znaków.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Bufor znaków. |
| index | int | Początek fragmentu. |
| count | int | Rozmiar fragmentu. |

### Wartość zwracana

Wymagany rozmiar bufora.

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) metoda

Pobiera liczbę znaków potrzebnych do zakodowania bufora znaków.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Bufor znaków. |
| index | int | Początek fragmentu. |
| count | int | Rozmiar fragmentu. |

### Wartość zwracana

Wymagany rozmiar bufora.

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) metoda

Pobiera liczbę znaków potrzebnych do zakodowania bufora znaków.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Bufor znaków. |
| index | int | Początek fragmentu. |
| count | int | Rozmiar fragmentu. |

### Wartość zwracana

Wymagany rozmiar bufora.

## Encoding::GetByteCount(const String\&) metoda

Pobiera liczbę znaków potrzebnych do zakodowania ciągu znaków.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) do zakodowania. |

### Wartość zwracana

Wymagany rozmiar bufora.

## Encoding::GetByteCount(ArrayPtr\<char_t\>) metoda

Pobiera liczbę znaków potrzebnych do zakodowania bufora znaków.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Bufor znaków. |

### Wartość zwracana

Wymagany rozmiar bufora.

## Encoding::GetByteCount(const char_t *, int) metoda

Pobiera liczbę znaków potrzebnych do zakodowania bufora znaków.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | const char_t * | Bufor znaków. |
| count | int | [Buffer](../../../system/buffer/) rozmiar. |

### Wartość zwracana

Wymagany rozmiar bufora.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [Encoding](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Text](../../)
* Library [Aspose.Slides](../../../)