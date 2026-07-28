---
title: GetBytes()
second_title: Aspose.Slides C++ API referencia
description: Lekéri a puffer kódolásából eredő bájtokat.
type: docs
weight: 53
url: /hu/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) metódus


Lekéri a puffer kódolásából eredő bájtokat.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kódolandó karakterek. |
| charIndex | int | Forrás tömb eltolása. |
| charCount | int | Forrás alttömb hossza. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Cél bájttömb. |
| byteIndex | int | Cél puffer eltolása. |
| flush | **bool** | Ha igaz, a számítás után tisztítja a belső kódoló állapotot. |

### Visszatérési érték

A leírt bájtok száma.

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) metódus


Lekéri a puffer kódolásából eredő bájtokat.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Kódolandó karakterek. |
| charCount | int | Forrás tömb hossza. |
| bytes | **uint8_t** * | Cél bájttömb. |
| byteCount | int | Cél puffer mérete. |
| flush | **bool** | Ha igaz, a számítás után tisztítja a belső kódoló állapotot. |

### Visszatérési érték

A leírt bájtok száma.

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [ICUEncoder](../)
* Névterület [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)