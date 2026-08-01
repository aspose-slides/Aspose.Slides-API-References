---
title: Convert()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert bytes naar tekens.
type: docs
weight: 79
url: /nl/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method

Converteert bytes naar tekens.

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes om te decoderen. |
| byteIndex | int | Offset van invoerbuffer. |
| byteCount | int | Grootte van invoerbuffer. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Doelkarakterbuffer. |
| charIndex | int | Offset van doelarray. |
| charCount | int | Grootte van doelarray. |
| flush | **bool** | Indien true, maakt de interne decodertoestand schoon na de berekening. |
| bytesUsed | int\& | Referentie naar variabele om het aantal gelezen bytes op te slaan. |
| charsUsed | int\& | Referentie naar variabele om het aantal geschreven karakters op te slaan. |
| completed | **bool**\& | Referentie naar variabele die op true wordt gezet als de invoerbuffer uitgeput is en anders op false. |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method

Converteert bytes naar tekens.

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes om te decoderen. |
| byteCount | int | Grootte van invoerbuffer. |
| chars | char_t * | Doelkarakterbuffer. |
| charCount | int | Grootte van doelarray. |
| flush | **bool** | Indien true, maakt de interne decodertoestand schoon na de berekening. |
| bytesUsed | int\& | Referentie naar variabele om het aantal gelezen bytes op te slaan. |
| charsUsed | int\& | Referentie naar variabele om het aantal geschreven karakters op te slaan. |
| completed | **bool**\& | Referentie naar variabele die op true wordt gezet als de invoerbuffer uitgeput is en anders op false. |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Decoder](../)
* Naamruimte [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)