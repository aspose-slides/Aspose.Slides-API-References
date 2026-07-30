---
title: GetChars()
second_title: Aspose.Slides pro referenci API C++
description: Získá znaky, které jsou výsledkem dekódování bajtového bufferu.
type: docs
weight: 92
url: /cs/system.text/utf7encoding/getchars/
---
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metoda

Získá znaky, které jsou výsledkem dekódování bajtového bufferu.

```cpp
int System::Text::UTF7Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) ke čtení bajtů z. |
| byte_index | int | Offset vstupního bufferu. |
| byte_count | int | Velikost vstupního bufferu. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) k vložení znaků do. |
| char_index | int | Offset výstupního bufferu. |

### Návratová hodnota

Počet zapsaných znaků.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) metoda

Získá znaky, které jsou výsledkem dekódování bajtového bufferu.

```cpp
int System::Text::UTF7Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) ke čtení bajtů z. |
| byte_count | int | Velikost vstupního bufferu. |
| chars | char_t * | [Buffer](../../../system/buffer/) k vložení znaků do. |
| char_count | int | Velikost výstupního bufferu. |

### Návratová hodnota

Počet zapsaných znaků.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metoda


Získá znaky, které jsou výsledkem dekódování bajtového bufferu.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) ke čtení bajtů z. |
| byte_index | int | Offset vstupního bufferu. |
| byte_count | int | Velikost vstupního bufferu. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) k vložení znaků do. |
| char_index | int | Offset výstupního bufferu. |

### Návratová hodnota

Počet zapsaných znaků.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) metoda


Získá znaky, které jsou výsledkem dekódování bajtového bufferu.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) ke čtení bajtů z. |
| index | int | Offset vstupního bufferu. |
| count | int | Velikost vstupního bufferu. |

### Návratová hodnota

[Buffer](../../../system/buffer/) dekódovaných znaků.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>) metoda


Získá znaky, které jsou výsledkem dekódování bajtového bufferu.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) ke čtení bajtů z. |

### Návratová hodnota

[Buffer](../../../system/buffer/) dekódovaných znaků.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) metoda


Získá znaky, které jsou výsledkem dekódování bajtového bufferu.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) ke čtení bajtů z. |
| byte_count | int | Velikost vstupního bufferu. |
| chars | char_t * | [Buffer](../../../system/buffer/) k vložení znaků do. |
| char_count | int | Velikost výstupního bufferu. |

### Návratová hodnota

Počet zapsaných znaků.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [UTF7Encoding](../)
* Jmenný prostor [System::Text](../../)
* Knihovna [Aspose.Slides](../../../)