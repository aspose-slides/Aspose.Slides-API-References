---
title: GetChars()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Pobiera znaki powstałe w wyniku dekodowania bufora bajtów.
type: docs
weight: 92
url: /pl/system.text/utf7encoding/getchars/
---
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method

Pobiera znaki powstałe w wyniku dekodowania bufora bajtów.

```cpp
int System::Text::UTF7Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index) override
```

### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do odczytu bajtów. |
| byte_index | int | Offset bufora wejściowego. |
| byte_count | int | Rozmiar bufora wejściowego. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) do zapisu znaków. |
| char_index | int | Offset bufora wyjściowego. |

### Return Value

Liczba zapisanych znaków.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) method

Pobiera znaki powstałe w wyniku dekodowania bufora bajtów.

```cpp
int System::Text::UTF7Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) do odczytu bajtów. |
| byte_count | int | Rozmiar bufora wejściowego. |
| chars | char_t * | [Buffer](../../../system/buffer/) do zapisu znaków. |
| char_count | int | Rozmiar bufora wyjściowego. |

### Return Value

Liczba zapisanych znaków.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method

Pobiera znaki powstałe w wyniku dekodowania bufora bajtów.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do odczytu bajtów. |
| byte_index | int | Offset bufora wejściowego. |
| byte_count | int | Rozmiar bufora wejściowego. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) do zapisu znaków. |
| char_index | int | Offset bufora wyjściowego. |

### Return Value

Liczba zapisanych znaków.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) method

Pobiera znaki powstałe w wyniku dekodowania bufora bajtów.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do odczytu bajtów. |
| index | int | Offset bufora wejściowego. |
| count | int | Rozmiar bufora wejściowego. |

### Return Value

[Buffer](../../../system/buffer/) zdekodowanych znaków.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>) method

Pobiera znaki powstałe w wyniku dekodowania bufora bajtów.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do odczytu bajtów. |

### Return Value

[Buffer](../../../system/buffer/) zdekodowanych znaków.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) method

Pobiera znaki powstałe w wyniku dekodowania bufora bajtów.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) do odczytu bajtów. |
| byte_count | int | Rozmiar bufora wejściowego. |
| chars | char_t * | [Buffer](../../../system/buffer/) do zapisu znaków. |
| char_count | int | Rozmiar bufora wyjściowego. |

### Return Value

Liczba zapisanych znaków.

## See Also

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [UTF7Encoding](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)