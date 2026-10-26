---
title: GetChars()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Pobiera znaki uzyskane w wyniku dekodowania bufora bajtów.
type: docs
weight: 66
url: /pl/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) metoda


Pobiera znaki uzyskane w wyniku dekodowania bufora bajtów.

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) do odczytu bajtów z. |
| byte_count | int | Rozmiar bufora wejściowego. |
| chars | char_t * | [Buffer](../../../system/buffer/) do umieszczenia znaków. |
| char_count | int | Rozmiar bufora wyjściowego. |

### Wartość zwracana

Liczba zapisanych znaków.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metoda


Pobiera znaki uzyskane w wyniku dekodowania bufora bajtów.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do odczytu bajtów z. |
| byte_index | int | Przesunięcie bufora wejściowego. |
| byte_count | int | Rozmiar bufora wejściowego. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) do umieszczenia znaków. |
| char_index | int | Przesunięcie bufora wyjściowego. |

### Wartość zwracana

Liczba zapisanych znaków.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) metoda


Pobiera znaki uzyskane w wyniku dekodowania bufora bajtów.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do odczytu bajtów z. |
| index | int | Przesunięcie bufora wejściowego. |
| count | int | Rozmiar bufora wejściowego. |

### Wartość zwracana

[Buffer](../../../system/buffer/) znaków zdekodowanych.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) metoda


Pobiera znaki uzyskane w wyniku dekodowania bufora bajtów.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do odczytu bajtów z. |

### Wartość zwracana

[Buffer](../../../system/buffer/) znaków zdekodowanych.

## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) metoda


Pobiera znaki uzyskane w wyniku dekodowania bufora bajtów.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) do odczytu bajtów z. |
| byte_count | int | Rozmiar bufora wejściowego. |
| chars | char_t * | [Buffer](../../../system/buffer/) do umieszczenia znaków. |
| char_count | int | Rozmiar bufora wyjściowego. |

### Wartość zwracana

Liczba zapisanych znaków.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [ICUEncoding](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)