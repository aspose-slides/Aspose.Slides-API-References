---
title: GetChars()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Získá znaky, které vzniknou dekódováním bajtového bufferu.
type: docs
weight: 274
url: /cs/system.text/encoding/getchars/
---
## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method

Získá znaky, které vzniknou dekódováním bajtového bufferu.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pro čtení bajtů z. |
| byte_index | int | Posun vstupního bufferu. |
| byte_count | int | Velikost vstupního bufferu. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) pro uložení znaků do. |
| char_index | int | Posun výstupního bufferu. |

### Návratová hodnota

Počet zapsaných znaků.

## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) method

Získá znaky, které vzniknou dekódováním bajtového bufferu.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pro čtení bajtů z. |
| index | int | Posun vstupního bufferu. |
| count | int | Velikost vstupního bufferu. |

### Návratová hodnota

[Buffer](../../../system/buffer/) dekódovaných znaků.

## Encoding::GetChars(ArrayPtr\<uint8_t\>) method

Získá znaky, které vzniknou dekódováním bajtového bufferu.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pro čtení bajtů z. |

### Návratová hodnota

[Buffer](../../../system/buffer/) dekódovaných znaků.

## Encoding::GetChars(const uint8_t *, int, char_t *, int) method

Získá znaky, které vzniknou dekódováním bajtového bufferu.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) pro čtení bajtů z. |
| byte_count | int | Velikost vstupního bufferu. |
| chars | char_t * | [Buffer](../../../system/buffer/) pro uložení znaků do. |
| char_count | int | Velikost výstupního bufferu. |

### Návratová hodnota

Počet zapsaných znaků.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)