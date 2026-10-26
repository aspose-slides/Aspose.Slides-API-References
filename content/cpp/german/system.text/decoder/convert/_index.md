---
title: Convert()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert Bytes in Zeichen.
type: docs
weight: 79
url: /de/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method


Konvertiert Bytes in Zeichen.

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Zu dekodierende Bytes. |
| byteIndex | int | Versatz des Eingabepuffers. |
| byteCount | int | Größe des Eingabepuffers. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zielzeichenpuffer. |
| charIndex | int | Versatz des Zielarrays. |
| charCount | int | Größe des Zielarrays. |
| flush | **bool** | Wenn true, bereinigt den internen Decoder-Zustand nach der Berechnung. |
| bytesUsed | int\& | Referenz auf eine Variable, um die Anzahl gelesener Bytes zu speichern. |
| charsUsed | int\& | Referenz auf eine Variable, um die Anzahl geschriebener Zeichen zu speichern. |
| completed | **bool**\& | Referenz auf eine Variable, die auf true gesetzt wird, wenn der Eingabepuffer erschöpft ist, und sonst auf false. |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method


Konvertiert Bytes in Zeichen.

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const **uint8_t** * | Zu dekodierende Bytes. |
| byteCount | int | Größe des Eingabepuffers. |
| chars | char_t * | Zielzeichenpuffer. |
| charCount | int | Größe des Zielarrays. |
| flush | **bool** | Wenn true, bereinigt den internen Decoder-Zustand nach der Berechnung. |
| bytesUsed | int\& | Referenz auf eine Variable, um die Anzahl gelesener Bytes zu speichern. |
| charsUsed | int\& | Referenz auf eine Variable, um die Anzahl geschriebener Zeichen zu speichern. |
| completed | **bool**\& | Referenz auf eine Variable, die auf true gesetzt wird, wenn der Eingabepuffer erschöpft ist, und sonst auf false. |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Decoder](../)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)