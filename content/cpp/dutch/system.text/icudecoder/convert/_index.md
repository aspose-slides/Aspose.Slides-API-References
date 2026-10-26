---
title: Convert()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert bytes naar tekens.
type: docs
weight: 66
url: /nl/system.text/icudecoder/convert/
---
## ICUDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) methode

Converteert bytes naar tekens.

```cpp
virtual void System::Text::ICUDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes om te decoderen. |
| byteIndex | int | Offset van de invoerbuffer. |
| byteCount | int | Grootte van de invoerbuffer. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Doelkarakterbuffer. |
| charIndex | int | Offset van doelarray. |
| charCount | int | Grootte van doelarray. |
| flush | **bool** | Indien true, wist de interne decodertoestand na berekening. |
| bytesUsed | int\& | Referentie naar variabele om aantal gelezen bytes op te slaan. |
| charsUsed | int\& | Referentie naar variabele om aantal geschreven tekens op te slaan. |
| completed | **bool**\& | Referentie naar variabele die true wordt ingesteld als de invoerbuffer uitgeput is en anders false. |

## ICUDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) methode

Converteert bytes naar tekens.

```cpp
virtual void System::Text::ICUDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes om te decoderen. |
| byteCount | int | Grootte van de invoerbuffer. |
| chars | char_t * | Doelkarakterbuffer. |
| charCount | int | Grootte van doelarray. |
| flush | **bool** | Indien true, wist de interne decodertoestand na berekening. |
| bytesUsed | int\& | Referentie naar variabele om aantal gelezen bytes op te slaan. |
| charsUsed | int\& | Referentie naar variabele om aantal geschreven tekens op te slaan. |
| completed | **bool**\& | Referentie naar variabele die true wordt ingesteld als de invoerbuffer uitgeput is en anders false. |

## Zie Ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICUDecoder](../)
* Naamruimte [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)