---
title: GetBytes()
second_title: Aspose.Slides pro C++ – reference API
description: Získá bajty, které jsou výsledkem kódování znakové vyrovnávací paměti.
type: docs
weight: 248
url: /cs/system.text/encoding/getbytes/
---
## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) metoda


Získá bajty, které jsou výsledkem kódování znakové vyrovnávací paměti.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaky k zakódování. |
| char_index | int | Začátek části znaků. |
| char_count | int | Počet znaků k převodu. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pro uložení znaků. |
| byte_index | int | Posun výstupní vyrovnávací paměti. |

### Návratová hodnota

Počet zapsaných bajtů.

## Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) metoda


Získá bajty, které jsou výsledkem kódování znakové vyrovnávací paměti.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Znaky k zakódování. |
| char_index | int | Začátek části znaků. |
| char_count | int | Počet znaků k převodu. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) pro uložení znaků. |
| byte_index | int | Posun výstupní vyrovnávací paměti. |

### Návratová hodnota

Počet zapsaných bajtů.

## Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) metoda


Získá bajty, které jsou výsledkem kódování znakové vyrovnávací paměti.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Znaky k zakódování. |
| char_index | int | Začátek části znaků. |
| char_count | int | Počet znaků k převodu. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) pro uložení znaků. |
| byte_index | int | Posun výstupní vyrovnávací paměti. |

### Návratová hodnota

Počet zapsaných bajtů.

## Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) metoda


Získá bajty, které jsou výsledkem kódování znakové vyrovnávací paměti.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) k zakódování. |
| char_index | int | Začátek části znaků. |
| char_count | int | Počet znaků k převodu. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pro uložení znaků. |
| byte_index | int | Posun výstupní vyrovnávací paměti. |

### Návratová hodnota

Počet zapsaných bajtů.

## Encoding::GetBytes(const String\&) metoda


Získá bajty, které jsou výsledkem kódování znakové vyrovnávací paměti.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) k zakódování. |

### Návratová hodnota

[Buffer](../../../system/buffer/) obsahuje reprezentaci zakódovaných znaků.

## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) metoda


Získá bajty, které jsou výsledkem kódování znakové vyrovnávací paměti.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaky k zakódování. |
| index | int | Začátek části znaků. |
| count | int | Počet znaků k převodu. |

### Návratová hodnota

[Buffer](../../../system/buffer/) obsahuje reprezentaci zakódovaných znaků.

## Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) metoda


Získá bajty, které jsou výsledkem kódování znakové vyrovnávací paměti.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Znaky k zakódování. |
| index | int | Začátek části znaků. |
| count | int | Počet znaků k převodu. |

### Návratová hodnota

[Buffer](../../../system/buffer/) obsahuje reprezentaci zakódovaných znaků.

## Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) metoda


Získá bajty, které jsou výsledkem kódování znakové vyrovnávací paměti.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Znaky k zakódování. |
| index | int | Začátek části znaků. |
| count | int | Počet znaků k převodu. |

### Návratová hodnota

[Buffer](../../../system/buffer/) obsahuje reprezentaci zakódovaných znaků.

## Encoding::GetBytes(ArrayPtr\<char_t\>) metoda


Získá bajty, které jsou výsledkem kódování znakové vyrovnávací paměti.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaky k zakódování. |

### Návratová hodnota

[Buffer](../../../system/buffer/) obsahuje reprezentaci zakódovaných znaků.

## Encoding::GetBytes(const char_t *, int, uint8_t *, int) metoda


Získá bajty, které jsou výsledkem kódování znakové vyrovnávací paměti.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | const char_t * | Znaky k zakódování. |
| char_count | int | Počet znaků k převodu. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) pro uložení znaků. |
| byte_count | int | Velikost výstupní vyrovnávací paměti. |

### Návratová hodnota

Počet zapsaných bajtů.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [Encoding](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Text](../../)
* Knihovna [Aspose.Slides](../../../)