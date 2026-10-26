---
title: Convert()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert Zeichen in Bytes.
type: docs
weight: 79
url: /de/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) Methode


Konvertiert Zeichen in Bytes.

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zeichen zum Kodieren. |
| charIndex | int | Eingabepuffer-Offset. |
| charCount | int | Größe des Eingabepuffers. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ziel-Byte-Puffer. |
| byteIndex | int | Zielarray-Offset. |
| byteCount | int | Größe des Zielarrays. |
| flush | **bool** | Falls true, löscht den internen Encoder-Zustand nach der Berechnung. |
| charsUsed | int\& | Referenz auf die Variable, die die Anzahl gelesener Zeichen speichert. |
| bytesUsed | int\& | Referenz auf die Variable, die die Anzahl geschriebener Bytes speichert. |
| completed | **bool**\& | Referenz auf die Variable, die auf true gesetzt wird, wenn der Eingabepuffer erschöpft ist, und andernfalls auf false. |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) Methode


Konvertiert Zeichen in Bytes.

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | const char_t * | Zeichen zum Kodieren. |
| charCount | int | Größe des Eingabepuffers. |
| bytes | **uint8_t** * | Ziel-Byte-Puffer. |
| byteCount | int | Größe des Zielarrays. |
| flush | **bool** | Falls true, löscht den internen Encoder-Zustand nach der Berechnung. |
| charsUsed | int\& | Referenz auf die Variable, die die Anzahl gelesener Zeichen speichert. |
| bytesUsed | int\& | Referenz auf die Variable, die die Anzahl geschriebener Bytes speichert. |
| completed | **bool**\& | Referenz auf die Variable, die auf true gesetzt wird, wenn der Eingabepuffer erschöpft ist, und andernfalls auf false. |

## Siehe Auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Encoder](../)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)