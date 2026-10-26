---
title: GetByteCount()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca liczbę znaków potrzebnych do zakodowania bufora znaków.
type: docs
weight: 157
url: /pl/system.text/utf7encoding/getbytecount/
---
## UTF7Encoding::GetByteCount(const char_t *, int) metoda


Zwraca liczbę znaków potrzebnych do zakodowania bufora znaków.

```cpp
int System::Text::UTF7Encoding::GetByteCount(const char_t *chars, int count) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | const char_t * | Bufor znaków. |
| count | int | [Buffer](../../../system/buffer/) rozmiar. |

### Wartość zwracana

Wymagany rozmiar bufora.

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) metoda


Zwraca liczbę znaków potrzebnych do zakodowania bufora znaków.

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

## UTF7Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) metoda


Zwraca liczbę znaków potrzebnych do zakodowania bufora znaków.

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

## UTF7Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) metoda


Zwraca liczbę znaków potrzebnych do zakodowania bufora znaków.

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

## UTF7Encoding::GetByteCount(const String\&) metoda


Zwraca liczbę znaków potrzebnych do zakodowania łańcucha.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) do zakodowania. |

### Wartość zwracana

Wymagany rozmiar bufora.

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>) metoda


Zwraca liczbę znaków potrzebnych do zakodowania bufora znaków.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Bufor znaków. |

### Wartość zwracana

Wymagany rozmiar bufora.

## UTF7Encoding::GetByteCount(const char_t *, int) metoda


Zwraca liczbę znaków potrzebnych do zakodowania bufora znaków.

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

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [UTF7Encoding](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)