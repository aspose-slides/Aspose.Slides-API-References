---
title: GetChars()
second_title: Aspose.Slides C++ API Referencia
description: Visszaadja a dekódolt pufferből származó karaktereket.
type: docs
weight: 53
url: /hu/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metódus

Visszaadja a dekódolt pufferből származó karaktereket.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dekódolandó bájtok. |
| byteIndex | int | Bemeneti puffer eltolás. |
| byteCount | int | Bemeneti puffer mérete. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Cél karakterpuffer. |
| charIndex | int | Cél tömb eltolás. |

### Visszatérési érték

A leírt karakterek száma.

## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) metódus

Visszaadja a dekódolt pufferből származó karaktereket.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dekódolandó bájtok. |
| byteIndex | int | Bemeneti puffer eltolás. |
| byteCount | int | Bemeneti puffer mérete. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Cél karakterpuffer. |
| charIndex | int | Cél tömb eltolás. |
| flush | **bool** | Ha igaz, a számítás után törli a belső dekódoló állapotot. |

### Visszatérési érték

A leírt karakterek száma.

## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) metódus

Visszaadja a dekódolt pufferből származó karaktereket.

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const **uint8_t** * | Dekódolandó bájtok. |
| byteCount | int | Bemeneti puffer mérete. |
| chars | char_t * | Cél karakterpuffer. |
| charCount | int | Cél tömb mérete. |
| flush | **bool** | Ha igaz, a számítás után törli a belső dekódoló állapotot. |

### Visszatérési érték

A leírt karakterek száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [ICUDecoder](../)
* Névtér [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)