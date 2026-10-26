---
title: GetChars()
second_title: Aspose.Slides C++ API Referenciája
description: Visszaadja a bájtpuffer dekódolása után kapott karaktereket.
type: docs
weight: 92
url: /hu/system.text/utf7encoding/getchars/
---
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metódus

Visszaadja a bájtpuffer dekódolása után kapott karaktereket.

```cpp
int System::Text::UTF7Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) a beolvasandó bájtokhoz. |
| byte_index | int | Bemeneti puffer eltolás. |
| byte_count | int | Bemeneti puffer mérete. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) a karakterek elhelyezéséhez. |
| char_index | int | Kimeneti puffer eltolás. |

### Visszatérési érték

A leírt karakterek száma.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) metódus

Visszaadja a bájtpuffer dekódolása után kapott karaktereket.

```cpp
int System::Text::UTF7Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) a beolvasandó bájtokhoz. |
| byte_count | int | Bemeneti puffer mérete. |
| chars | char_t * | [Buffer](../../../system/buffer/) a karakterek elhelyezéséhez. |
| char_count | int | Kimeneti puffer mérete. |

### Visszatérési érték

A leírt karakterek száma.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metódus

Visszaadja a bájtpuffer dekódolása után kapott karaktereket.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) a beolvasandó bájtokhoz. |
| byte_index | int | Bemeneti puffer eltolás. |
| byte_count | int | Bemeneti puffer mérete. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) a karakterek elhelyezéséhez. |
| char_index | int | Kimeneti puffer eltolás. |

### Visszatérési érték

A leírt karakterek száma.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) metódus

Visszaadja a bájtpuffer dekódolása után kapott karaktereket.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) a beolvasandó bájtokhoz. |
| index | int | Bemeneti puffer eltolás. |
| count | int | Bemeneti puffer mérete. |

### Visszatérési érték

[Buffer](../../../system/buffer/) a dekódolt karakterek.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>) metódus

Visszaadja a bájtpuffer dekódolása után kapott karaktereket.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) a beolvasandó bájtokhoz. |

### Visszatérési érték

[Buffer](../../../system/buffer/) a dekódolt karakterek.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) metódus

Visszaadja a bájtpuffer dekódolása után kapott karaktereket.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) a beolvasandó bájtokhoz. |
| byte_count | int | Bemeneti puffer mérete. |
| chars | char_t * | [Buffer](../../../system/buffer/) a karakterek elhelyezéséhez. |
| char_count | int | Kimeneti puffer mérete. |

### Visszatérési érték

A leírt karakterek száma.

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [UTF7Encoding](../)
* Névtér [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)