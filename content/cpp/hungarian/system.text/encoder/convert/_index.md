---
title: Convert()
second_title: Aspose.Slides C++ API referencia
description: Karaktereket bájtokká konvertál.
type: docs
weight: 79
url: /hu/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) metódus


Karaktereket bájtokká konvertál.

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kódolandó karakterek. |
| charIndex | int | Bemeneti puffer eltolás. |
| charCount | int | Bemeneti puffer mérete. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Cél bájt puffer. |
| byteIndex | int | Cél tömb eltolás. |
| byteCount | int | Cél tömb mérete. |
| flush | **bool** | Ha igaz, a számítás után megtisztítja a belső enkóder állapotot. |
| charsUsed | int\& | Referenciaként szolgál a változóhoz, amely a beolvasott karakterek számát tárolja. |
| bytesUsed | int\& | Referenciaként szolgál a változóhoz, amely az írt bájtok számát tárolja. |
| completed | **bool**\& | Referenciaként szolgál a változóhoz, amely igazra (true) lesz állítva, ha a bemeneti puffer kimerült, egyébként hamisra (false). |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) metódus


Karaktereket bájtokká konvertál.

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | const char_t * | Kódolandó karakterek. |
| charCount | int | Bemeneti puffer mérete. |
| bytes | **uint8_t** * | Cél bájt puffer. |
| byteCount | int | Cél tömb mérete. |
| flush | **bool** | Ha igaz, a számítás után megtisztítja a belső enkóder állapotot. |
| charsUsed | int\& | Referenciaként szolgál a változóhoz, amely a beolvasott karakterek számát tárolja. |
| bytesUsed | int\& | Referenciaként szolgál a változóhoz, amely az írt bájtok számát tárolja. |
| completed | **bool**\& | Referenciaként szolgál a változóhoz, amely igazra (true) lesz állítva, ha a bemeneti puffer kimerült, egyébként hamisra (false). |

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [Encoder](../)
* Névtér [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)