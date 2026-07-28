---
title: Convert()
second_title: Aspose.Slides C++ API referenciája
description: Átalakítja a bájtokat karakterekké.
type: docs
weight: 1
url: /hu/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method

Átalakítja a bájtokat karakterekké.

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const **uint8_t** * | A dekódolandó bájtok. |
| byteCount | int | A bemeneti puffer mérete. |
| chars | char_t * | A cél karakterpuffer. |
| charCount | int | A cél tömb mérete. |
| flush | **bool** | Ha igaz, a számítás után megtisztítja a belső dekódoló állapotot. |
| bytesUsed | int\& | Referencia a változóhoz, amely a beolvasott bájtok számát tárolja. |
| charsUsed | int\& | Referencia a változóhoz, amely a kiírt karakterek számát tárolja. |
| completed | **bool**\& | Referencia a változóhoz, amely igazra lesz állítva, ha a bemeneti puffer kimerült, különben hamis. |

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method

Átalakítja a bájtokat karakterekké.

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A dekódolandó bájtok. |
| byteIndex | int | A bemeneti puffer eltolása. |
| byteCount | int | A bemeneti puffer mérete. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | A cél karakterpuffer. |
| charIndex | int | A cél tömb eltolása. |
| charCount | int | A cél tömb mérete. |
| flush | **bool** | Ha igaz, a számítás után megtisztítja a belső dekódoló állapotot. |
| bytesUsed | int\& | Referencia a változóhoz, amely a beolvasott bájtok számát tárolja. |
| charsUsed | int\& | Referencia a változóhoz, amely a kiírt karakterek számát tárolja. |
| completed | **bool**\& | Referencia a változóhoz, amely igazra lesz állítva, ha a bemeneti puffer kimerült, különben hamis. |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [EncodingDecoder](../)
* Névtér [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)