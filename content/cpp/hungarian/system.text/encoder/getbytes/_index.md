---
title: GetBytes()
second_title: Aspose.Slides C++ API hivatkozás
description: A kódolás eredményeként egy pufferből származó bájtokat adja vissza.
type: docs
weight: 53
url: /hu/system.text/encoder/getbytes/
---
## Encoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) metódus

A kódolás eredményeként egy pufferből származó bájtokat adja vissza.

```cpp
virtual int System::Text::Encoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | A kódolandó karakterek. |
| charIndex | int | A forrás tömb eltolása. |
| charCount | int | A forrás rész tömb hossza. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A cél bájtpuffer. |
| byteIndex | int | A cél puffer eltolása. |
| flush | **bool** | Ha true, tisztítja a belső kódezó állapotát a számítás után. |

### Visszatérési érték

Az írt bájtok száma.

## Encoder::GetBytes(const char_t *, int, uint8_t *, int, bool) metódus

A kódolás eredményeként egy pufferből származó bájtokat adja vissza.

```cpp
virtual int System::Text::Encoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | const char_t * | A kódolandó karakterek. |
| charCount | int | A forrás tömb hossza. |
| bytes | **uint8_t** * | A cél bájtpuffer. |
| byteCount | int | A cél puffer mérete. |
| flush | **bool** | Ha true, tisztítja a belső kódezó állapotát a számítás után. |

### Visszatérési érték

Az írt bájtok száma.

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [Encoder](../)
* Névtér [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)