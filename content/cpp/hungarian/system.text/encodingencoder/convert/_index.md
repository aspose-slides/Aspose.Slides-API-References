---
title: Convert()
second_title: Aspose.Slides C++ API-referencia
description: Átalakítja a karaktereket bájtokká.
type: docs
weight: 1
url: /hu/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) metódus


Átalakítja a karaktereket bájtokká.

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | const char_t * | A kódolandó karakterek. |
| charCount | int | A bemeneti puffertömeg. |
| bytes | **uint8_t** * | A célbájtpuffer. |
| byteCount | int | A cél tömb mérete. |
| flush | **bool** | Ha igaz, a számítás után megtisztítja a belső kódoló állapotot. |
| charsUsed | int\& | Referencia a változóhoz, amely a beolvasott karakterek számát tárolja. |
| bytesUsed | int\& | Referencia a változóhoz, amely a kiírt bájtok számát tárolja. |
| completed | **bool**\& | Referencia a változóhoz, amely igazra lesz állítva, ha a bemeneti puffer kimerült, egyébként hamis. |

## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) metódus


Átalakítja a karaktereket bájtokká.

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | A kódolandó karakterek. |
| charIndex | int | A bemeneti puffer eltolása. |
| charCount | int | A bemeneti puffertömeg. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A célbájtpuffer. |
| byteIndex | int | A cél tömb eltolása. |
| byteCount | int | A cél tömb mérete. |
| flush | **bool** | Ha igaz, a számítás után megtisztítja a belső kódoló állapotot. |
| charsUsed | int\& | Referencia a változóhoz, amely a beolvasott karakterek számát tárolja. |
| bytesUsed | int\& | Referencia a változóhoz, amely a kiírt bájtok számát tárolja. |
| completed | **bool**\& | Referencia a változóhoz, amely igazra lesz állítva, ha a bemeneti puffer kimerült, egyébként hamis. |

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [EncodingEncoder](../)
* Névtér [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)