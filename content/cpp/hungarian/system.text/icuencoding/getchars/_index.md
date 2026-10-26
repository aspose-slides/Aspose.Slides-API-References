---
title: GetChars()
second_title: Aspose.Slides C++ API hivatkozás
description: A bájtpuffer dekódolásából származó karakterek lekérése.
type: docs
weight: 66
url: /hu/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) metódus


A bájtpuffer dekódolásából származó karakterek lekérése.

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) a bájtok olvasásához. |
| byte_count | int | A bemeneti puffer mérete. |
| chars | char_t * | [Buffer](../../../system/buffer/) a karakterek elhelyezéséhez. |
| char_count | int | A kimeneti puffer mérete. |

### Visszatérési érték

Az írt karakterek száma.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metódus


A bájtpuffer dekódolásából származó karakterek lekérése.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) a bájtok olvasásához. |
| byte_index | int | A bemeneti puffer eltolása. |
| byte_count | int | A bemeneti puffer mérete. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) a karakterek elhelyezéséhez. |
| char_index | int | A kimeneti puffer eltolása. |

### Visszatérési érték

Az írt karakterek száma.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) metódus


A bájtpuffer dekódolásából származó karakterek lekérése.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) a bájtok olvasásához. |
| index | int | A bemeneti puffer eltolása. |
| count | int | A bemeneti puffer mérete. |

### Visszatérési érték

[Buffer](../../../system/buffer/) dekódolt karakter.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) metódus


A bájtpuffer dekódolásából származó karakterek lekérése.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) a bájtok olvasásához. |

### Visszatérési érték

[Buffer](../../../system/buffer/) dekódolt karakter.

## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) metódus


A bájtpuffer dekódolásából származó karakterek lekérése.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) a bájtok olvasásához. |
| byte_count | int | A bemeneti puffer mérete. |
| chars | char_t * | [Buffer](../../../system/buffer/) a karakterek elhelyezéséhez. |
| char_count | int | A kimeneti puffer mérete. |

### Visszatérési érték

Az írt karakterek száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)