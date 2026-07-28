---
title: Convert()
second_title: Aspose.Slides C++ API referencia
description: Karaktereket bitekké konvertál.
type: docs
weight: 66
url: /hu/system.text/icuencoder/convert/
---
## ICUEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) metódus


Karaktereket bitekké konvertál.

```cpp
virtual void System::Text::ICUEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kódolandó karakterek. |
| charIndex | int | Bemeneti puffer eltolása. |
| charCount | int | Bemeneti puffer mérete. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Cél byte puffer. |
| byteIndex | int | Cél tömb eltolása. |
| byteCount | int | Cél tömb mérete. |
| flush | **bool** | Ha igaz, törli a belső enkóder állapotát a számítás után. |
| charsUsed | int\& | Hivatkozás egy változóra, amely a beolvasott karakterek számát tárolja. |
| bytesUsed | int\& | Hivatkozás egy változóra, amely a kiírt byte-ok számát tárolja. |
| completed | **bool**\& | Hivatkozás egy változóra, amely igazra lesz állítva, ha a bemeneti puffert kimerült, egyébként hamis. |

## ICUEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) metódus


Karaktereket bitekké konvertál.

```cpp
virtual void System::Text::ICUEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | const char_t * | Kódolandó karakterek. |
| charCount | int | Bemeneti puffer mérete. |
| bytes | **uint8_t** * | Cél byte puffer. |
| byteCount | int | Cél tömb mérete. |
| flush | **bool** | Ha igaz, törli a belső enkóder állapotát a számítás után. |
| charsUsed | int\& | Hivatkozás egy változóra, amely a beolvasott karakterek számát tárolja. |
| bytesUsed | int\& | Hivatkozás egy változóra, amely a kiírt byte-ok számát tárolja. |
| completed | **bool**\& | Hivatkozás egy változóra, amely igazra lesz állítva, ha a bemeneti puffert kimerült, egyébként hamis. |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)