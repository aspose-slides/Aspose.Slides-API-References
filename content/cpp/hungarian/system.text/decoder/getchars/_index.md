---
title: GetChars()
second_title: Aspose.Slides C++ API hivatkozás
description: A puffer dekódolásából származó karakterek lekérése.
type: docs
weight: 53
url: /hu/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metódus


A puffer dekódolásából származó karakterek lekérése.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dekódolandó bájtok. |
| byteIndex | int | Bemeneti puffer eltolása. |
| byteCount | int | Bemeneti puffer mérete. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Célkarakter-puffer. |
| charIndex | int | Cél tömb eltolása. |

### Visszatérési érték

A megírt karakterek száma.

## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) metódus


A puffer dekódolásából származó karakterek lekérése.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dekódolandó bájtok. |
| byteIndex | int | Bemeneti puffer eltolása. |
| byteCount | int | Bemeneti puffer mérete. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Célkarakter-puffer. |
| charIndex | int | Cél tömb eltolása. |
| flush | **bool** | Ha igaz, a számítás után megtisztítja a belső dekóder állapotát. |

### Visszatérési érték

A megírt karakterek száma.

## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) metódus


A puffer dekódolásából származó karakterek lekérése.

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const **uint8_t** * | Dekódolandó bájtok. |
| byteCount | int | Bemeneti puffer mérete. |
| chars | char_t * | Célkarakter-puffer. |
| charCount | int | Cél tömb mérete. |
| flush | **bool** | Ha igaz, a számítás után megtisztítja a belső dekóder állapotát. |

### Visszatérési érték

A megírt karakterek száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [Decoder](../)
* Névtér [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)