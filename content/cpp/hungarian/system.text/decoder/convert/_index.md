---
title: Convert()
second_title: Aspose.Slides for C++ API referencia
description: Átalakítja a bájtokat karakterekké.
type: docs
weight: 79
url: /hu/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method


Átalakítja a bájtokat karakterekké.

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dekódolandó bájtok. |
| byteIndex | int | Bemeneti puffer eltolása. |
| byteCount | int | Bemeneti puffer mérete. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Cél karakter puffer. |
| charIndex | int | Cél tömb eltolása. |
| charCount | int | Cél tömb mérete. |
| flush | **bool** | Ha igaz, a számítás után megtisztítja a belső dekóder állapotát. |
| bytesUsed | int\& | Változóra mutató referencia, amely tárolja a beolvasott bájtok számát. |
| charsUsed | int\& | Változóra mutató referencia, amely tárolja a kiírt karakterek számát. |
| completed | **bool**\& | Változóra mutató referencia, amelyet igazra állítanak, ha a bemeneti puffert kimerítették, egyébként hamis. |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method


Átalakítja a bájtokat karakterekké.

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const **uint8_t** * | Dekódolandó bájtok. |
| byteCount | int | Bemeneti puffer mérete. |
| chars | char_t * | Cél karakter puffer. |
| charCount | int | Cél tömb mérete. |
| flush | **bool** | Ha igaz, a számítás után megtisztítja a belső dekóder állapotát. |
| bytesUsed | int\& | Változóra mutató referencia, amely tárolja a beolvasott bájtok számát. |
| charsUsed | int\& | Változóra mutató referencia, amely tárolja a kiírt karakterek számát. |
| completed | **bool**\& | Változóra mutató referencia, amelyet igazra állítanak, ha a bemeneti puffert kimerítették, egyébként hamis. |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [Decoder](../)
* Névtér [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)