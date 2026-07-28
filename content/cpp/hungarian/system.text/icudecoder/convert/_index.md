---
title: Convert()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a bájtokat karakterekké.
type: docs
weight: 66
url: /hu/system.text/icudecoder/convert/
---
## ICUDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method

Átalakítja a bájtokat karakterekké.

```cpp
virtual void System::Text::ICUDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dekódolandó bájtok. |
| byteIndex | int | Bemeneti puffer eltolás. |
| byteCount | int | Bemeneti puffer mérete. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Célkarakterpuffer. |
| charIndex | int | Cél tömb eltolása. |
| charCount | int | Cél tömb mérete. |
| flush | **bool** | Ha igaz, a számítás után megtisztítja a belső dekóder állapotát. |
| bytesUsed | int\& | Referenciája egy változónak, amely a beolvasott bájtok számát tárolja. |
| charsUsed | int\& | Referenciája egy változónak, amely a kiírt karakterek számát tárolja. |
| completed | **bool**\& | Referenciája egy változónak, amely igazra lesz állítva, ha a bemeneti puffert kimerítették, egyébként hamis. |

## ICUDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method

Átalakítja a bájtokat karakterekké.

```cpp
virtual void System::Text::ICUDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const **uint8_t** * | Dekódolandó bájtok. |
| byteCount | int | Bemeneti puffer mérete. |
| chars | char_t * | Célkarakterpuffer. |
| charCount | int | Cél tömb mérete. |
| flush | **bool** | Ha igaz, a számítás után megtisztítja a belső dekóder állapotát. |
| bytesUsed | int\& | Referenciája egy változónak, amely a beolvasott bájtok számát tárolja. |
| charsUsed | int\& | Referenciája egy változónak, amely a kiírt karakterek számát tárolja. |
| completed | **bool**\& | Referenciája egy változónak, amely igazra lesz állítva, ha a bemeneti puffert kimerítették, egyébként hamis. |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [ICUDecoder](../)
* Névtér [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)