---
title: Convert()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert Zeichen in Bytes.
type: docs
weight: 1
url: /de/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) Methode

Konvertiert Zeichen in Bytes.

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | const char_t * | Zu kodierende Zeichen. |
| charCount | int | Größe des Eingabepuffers. |
| bytes | **uint8_t** * | Ziel-Byte-Puffer. |
| byteCount | int | Größe des Zielarrays. |
| flush | **bool** | Wenn true, wird der interne Encoder-Status nach der Berechnung bereinigt. |
| charsUsed | int\& | Referenz auf Variable, die die Anzahl gelesener Zeichen speichert. |
| bytesUsed | int\& | Referenz auf Variable, die die Anzahl geschriebener Bytes speichert. |
| completed | **bool**\& | Referenz auf Variable, die auf true gesetzt wird, wenn der Eingabepuffer erschöpft ist, andernfalls auf false. |

## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) Methode

Konvertiert Zeichen in Bytes.

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zu kodierende Zeichen. |
| charIndex | int | Versatz des Eingabepuffers. |
| charCount | int | Größe des Eingabepuffers. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ziel-Byte-Puffer. |
| byteIndex | int | Versatz des Zielarrays. |
| byteCount | int | Größe des Zielarrays. |
| flush | **bool** | Wenn true, wird der interne Encoder-Status nach der Berechnung bereinigt. |
| charsUsed | int\& | Referenz auf Variable, die die Anzahl gelesener Zeichen speichert. |
| bytesUsed | int\& | Referenz auf Variable, die die Anzahl geschriebener Bytes speichert. |
| completed | **bool**\& | Referenz auf Variable, die auf true gesetzt wird, wenn der Eingabepuffer erschöpft ist, andernfalls auf false. |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [EncodingEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)