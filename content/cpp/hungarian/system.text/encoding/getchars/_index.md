---
title: GetChars()
second_title: Aspose.Slides C++ API hivatkozás
description: Lekérdezi a bájttömb dekódolásából származó karaktereket.
type: docs
weight: 274
url: /hu/system.text/encoding/getchars/
---
## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method

Lekérdezi a bájttömb dekódolásából származó karaktereket.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) az olvasandó bájtokhoz. |
| byte_index | int | Bemeneti puffer eltolása. |
| byte_count | int | Bemeneti puffer mérete. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) a karakterek elhelyezéséhez. |
| char_index | int | Kimeneti puffer eltolása. |

### Visszatérési érték

A megírt karakterek száma.

## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) method

Lekérdezi a bájttömb dekódolásából származó karaktereket.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) az olvasandó bájtokhoz. |
| index | int | Bemeneti puffer eltolása. |
| count | int | Bemeneti puffer mérete. |

### Visszatérési érték

[Buffer](../../../system/buffer/) a dekódolt karakterek.

## Encoding::GetChars(ArrayPtr\<uint8_t\>) method

Lekérdezi a bájttömb dekódolásából származó karaktereket.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) az olvasandó bájtokhoz. |

### Visszatérési érték

[Buffer](../../../system/buffer/) a dekódolt karakterek.

## Encoding::GetChars(const uint8_t *, int, char_t *, int) method

Lekérdezi a bájttömb dekódolásából származó karaktereket.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) az olvasandó bájtokhoz. |
| byte_count | int | Bemeneti puffer mérete. |
| chars | char_t * | [Buffer](../../../system/buffer/) a karakterek elhelyezéséhez. |
| char_count | int | Kimeneti puffer mérete. |

### Visszatérési érték

A megírt karakterek száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [Encoding](../)
* Névtér [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)