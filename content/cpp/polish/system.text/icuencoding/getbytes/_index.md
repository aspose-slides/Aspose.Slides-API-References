---
title: GetBytes()
second_title: Aspose.Slides dla C++ referencja API
description: Pobierz bajty powstałe w wyniku kodowania bufora znaków.
type: docs
weight: 40
url: /pl/system.text/icuencoding/getbytes/
---
## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) metoda


Pobierz bajty powstałe w wyniku kodowania bufora znaków.

```cpp
int System::Text::ICUEncoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | const char_t * | Znaki do zakodowania. |
| char_count | int | Liczba znaków do konwersji. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) do umieszczenia znaków. |
| byte_count | int | Rozmiar bufora wyjściowego. |

### Wartość zwracana

Liczba zapisanych bajtów.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) metoda


Pobierz bajty powstałe w wyniku kodowania bufora znaków.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaki do zakodowania. |
| char_index | int | Początek wycinka znaków. |
| char_count | int | Liczba znaków do konwersji. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do umieszczenia znaków. |
| byte_index | int | Przesunięcie bufora wyjściowego. |

### Wartość zwracana

Liczba zapisanych bajtów.

## ICUEncoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) metoda


Pobierz bajty powstałe w wyniku kodowania bufora znaków.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Znaki do zakodowania. |
| char_index | int | Początek wycinka znaków. |
| char_count | int | Liczba znaków do konwersji. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) do umieszczenia znaków. |
| byte_index | int | Przesunięcie bufora wyjściowego. |

### Wartość zwracana

Liczba zapisanych bajtów.

## ICUEncoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) metoda


Pobierz bajty powstałe w wyniku kodowania bufora znaków.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Znaki do zakodowania. |
| char_index | int | Początek wycinka znaków. |
| char_count | int | Liczba znaków do konwersji. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) do umieszczenia znaków. |
| byte_index | int | Przesunięcie bufora wyjściowego. |

### Wartość zwracana

Liczba zapisanych bajtów.

## ICUEncoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) metoda


Pobierz bajty powstałe w wyniku kodowania bufora znaków.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) do zakodowania. |
| char_index | int | Początek wycinka znaków. |
| char_count | int | Liczba znaków do konwersji. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do umieszczenia znaków. |
| byte_index | int | Przesunięcie bufora wyjściowego. |

### Wartość zwracana

Liczba zapisanych bajtów.

## ICUEncoding::GetBytes(const String\&) metoda


Pobierz bajty powstałe w wyniku kodowania bufora znaków.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) do zakodowania. |

### Wartość zwracana

[Buffer](../../../system/buffer/) zawierający reprezentację kodowanych znaków.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int) metoda


Pobierz bajty powstałe w wyniku kodowania bufora znaków.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaki do zakodowania. |
| index | int | Początek wycinka znaków. |
| count | int | Liczba znaków do konwersji. |

### Wartość zwracana

[Buffer](../../../system/buffer/) zawierający reprezentację kodowanych znaków.

## ICUEncoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) metoda


Pobierz bajty powstałe w wyniku kodowania bufora znaków.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Znaki do zakodowania. |
| index | int | Początek wycinka znaków. |
| count | int | Liczba znaków do konwersji. |

### Wartość zwracana

[Buffer](../../../system/buffer/) zawierający reprezentację kodowanych znaków.

## ICUEncoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) metoda


Pobierz bajty powstałe w wyniku kodowania bufora znaków.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Znaki do zakodowania. |
| index | int | Początek wycinka znaków. |
| count | int | Liczba znaków do konwersji. |

### Wartość zwracana

[Buffer](../../../system/buffer/) zawierający reprezentację kodowanych znaków.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>) metoda


Pobierz bajty powstałe w wyniku kodowania bufora znaków.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaki do zakodowania. |

### Wartość zwracana

[Buffer](../../../system/buffer/) zawierający reprezentację kodowanych znaków.

## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) metoda


Pobierz bajty powstałe w wyniku kodowania bufora znaków.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | const char_t * | Znaki do zakodowania. |
| char_count | int | Liczba znaków do konwersji. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) do umieszczenia znaków. |
| byte_count | int | Rozmiar bufora wyjściowego. |

### Wartość zwracana

Liczba zapisanych bajtów.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [ICUEncoding](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Text](../../)
* Library [Aspose.Slides](../../../)