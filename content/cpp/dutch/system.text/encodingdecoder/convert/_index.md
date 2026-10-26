---
title: Convert()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert bytes naar tekens.
type: docs
weight: 1
url: /nl/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method


Converteert bytes naar tekens.

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes om te decoderen. |
| byteCount | int | Grootte van de invoerbuffer. |
| chars | char_t * | Doeltekenbuffer. |
| charCount | int | Grootte van de doelarray. |
| flush | **bool** | Indien true, wordt de interne decoderstatus na de berekening opgeschoond. |
| bytesUsed | int\& | Referentie naar variabele om het aantal gelezen bytes op te slaan. |
| charsUsed | int\& | Referentie naar variabele om het aantal geschreven tekens op te slaan. |
| completed | **bool**\& | Referentie naar variabele die true wordt ingesteld als de invoerbuffer is uitgeput en anders false. |

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method


Converteert bytes naar tekens.

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes om te decoderen. |
| byteIndex | int | Offset van de invoerbuffer. |
| byteCount | int | Grootte van de invoerbuffer. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Doeltekenbuffer. |
| charIndex | int | Offset van de doelarray. |
| charCount | int | Grootte van de doelarray. |
| flush | **bool** | Indien true, wordt de interne decoderstatus na de berekening opgeschoond. |
| bytesUsed | int\& | Referentie naar variabele om het aantal gelezen bytes op te slaan. |
| charsUsed | int\& | Referentie naar variabele om het aantal geschreven tekens op te slaan. |
| completed | **bool**\& | Referentie naar variabele die true wordt ingesteld als de invoerbuffer is uitgeput en anders false. |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [EncodingDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)