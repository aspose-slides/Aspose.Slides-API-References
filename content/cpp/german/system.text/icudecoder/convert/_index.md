---
title: Convert()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert Bytes zu Zeichen.
type: docs
weight: 66
url: /de/system.text/icudecoder/convert/
---
## ICUDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) Methode

Konvertiert Bytes zu Zeichen.

```cpp
virtual void System::Text::ICUDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes zu dekodieren. |
| byteIndex | int | Offset des Eingabepuffers. |
| byteCount | int | Größe des Eingabepuffers. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zielzeichenpuffer. |
| charIndex | int | Offset des Zielarrays. |
| charCount | int | Größe des Zielarrays. |
| flush | **bool** | Wenn true, wird der interne Decoder-Zustand nach der Berechnung bereinigt. |
| bytesUsed | int\& | Referenz auf Variable, in der die Anzahl gelesener Bytes gespeichert wird. |
| charsUsed | int\& | Referenz auf Variable, in der die Anzahl geschriebener Zeichen gespeichert wird. |
| completed | **bool**\& | Referenz auf Variable, die auf true gesetzt wird, wenn der Eingabepuffer erschöpft ist, andernfalls false. |

## ICUDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) Methode

Konvertiert Bytes zu Zeichen.

```cpp
virtual void System::Text::ICUDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes zu dekodieren. |
| byteCount | int | Größe des Eingabepuffers. |
| chars | char_t * | Zielzeichenpuffer. |
| charCount | int | Größe des Zielarrays. |
| flush | **bool** | Wenn true, wird der interne Decoder-Zustand nach der Berechnung bereinigt. |
| bytesUsed | int\& | Referenz auf Variable, in der die Anzahl gelesener Bytes gespeichert wird. |
| charsUsed | int\& | Referenz auf Variable, in der die Anzahl geschriebener Zeichen gespeichert wird. |
| completed | **bool**\& | Referenz auf Variable, die auf true gesetzt wird, wenn der Eingabepuffer erschöpft ist, andernfalls false. |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICUDecoder](../)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)