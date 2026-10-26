---
title: GetChars()
second_title: Aspose.Slides for C++ Referencja API
description: Pobiera znaki, które powstają w wyniku dekodowania bufora bajtów.
type: docs
weight: 274
url: /pl/system.text/encoding/getchars/
---
## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metoda

Pobiera znaki, które powstają w wyniku dekodowania bufora bajtów.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do odczytu bajtów z. |
| byte_index | int | Przesunięcie bufora wejściowego. |
| byte_count | int | Rozmiar bufora wejściowego. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) do umieszczenia znaków w. |
| char_index | int | Przesunięcie bufora wyjściowego. |

### Wartość zwracana

Liczba zapisanych znaków.

## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) metoda

Pobiera znaki, które powstają w wyniku dekodowania bufora bajtów.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do odczytu bajtów z. |
| index | int | Przesunięcie bufora wejściowego. |
| count | int | Rozmiar bufora wejściowego. |

### Wartość zwracana

[Buffer](../../../system/buffer/) zdekodowanych znaków.

## Encoding::GetChars(ArrayPtr\<uint8_t\>) metoda

Pobiera znaki, które powstają w wyniku dekodowania bufora bajtów.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do odczytu bajtów z. |

### Wartość zwracana

[Buffer](../../../system/buffer/) zdekodowanych znaków.

## Encoding::GetChars(const uint8_t *, int, char_t *, int) metoda

Pobiera znaki, które powstają w wyniku dekodowania bufora bajtów.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) do odczytu bajtów z. |
| byte_count | int | Rozmiar bufora wejściowego. |
| chars | char_t * | [Buffer](../../../system/buffer/) do umieszczenia znaków w. |
| char_count | int | Rozmiar bufora wyjściowego. |

### Wartość zwracana

Liczba zapisanych znaków.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [Encoding](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)