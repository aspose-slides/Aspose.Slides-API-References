---
title: Convert()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert Bytes in Zeichen.
type: docs
weight: 1
url: /de/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) Methode

Konvertiert Bytes in Zeichen.

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes zum Dekodieren. |
| byteCount | int | Größe des Eingabepuffers. |
| chars | char_t * | Zielzeichenpuffer. |
| charCount | int | Größe des Zielarrays. |
| flush | **bool** | Wenn true, bereinigt den internen Decoder-Zustand nach der Berechnung. |
| bytesUsed | int\& | Referenz auf eine Variable, die die Anzahl gelesener Bytes speichert. |
| charsUsed | int\& | Referenz auf eine Variable, die die Anzahl geschriebener Zeichen speichert. |
| completed | **bool**\& | Referenz auf eine Variable, die auf true gesetzt wird, wenn der Eingabepuffer erschöpft ist, und andernfalls auf false. |

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) Methode

Konvertiert Bytes in Zeichen.

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes zum Dekodieren. |
| byteIndex | int | Offset des Eingabepuffers. |
| byteCount | int | Größe des Eingabepuffers. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zielzeichenpuffer. |
| charIndex | int | Offset des Zielarrays. |
| charCount | int | Größe des Zielarrays. |
| flush | **bool** | Wenn true, bereinigt den internen Decoder-Zustand nach der Berechnung. |
| bytesUsed | int\& | Referenz auf eine Variable, die die Anzahl gelesener Bytes speichert. |
| charsUsed | int\& | Referenz auf eine Variable, die die Anzahl geschriebener Zeichen speichert. |
| completed | **bool**\& | Referenz auf eine Variable, die auf true gesetzt wird, wenn der Eingabepuffer erschöpft ist, und andernfalls auf false. |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [EncodingDecoder](../)
* Namensraum [System::Text](../../)
* Library [Aspose.Slides](../../../)