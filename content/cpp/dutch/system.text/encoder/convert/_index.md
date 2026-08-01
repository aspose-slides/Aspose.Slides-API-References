---
title: Convert()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert tekens naar bytes.
type: docs
weight: 79
url: /nl/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method

Converteert tekens naar bytes.

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tekens om te coderen. |
| charIndex | int | Offset van invoerbuffer. |
| charCount | int | Grootte van invoerbuffer. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Doel-bytebuffer. |
| byteIndex | int | Offset van doelarray. |
| byteCount | int | Grootte van doelarray. |
| flush | **bool** | Indien true, maakt de interne encoderstatus schoon na berekening. |
| charsUsed | int\& | Referentie naar variabele om het aantal gelezen tekens op te slaan. |
| bytesUsed | int\& | Referentie naar variabele om het aantal geschreven bytes op te slaan. |
| completed | **bool**\& | Referentie naar variabele die true wordt gezet als de invoerbuffer is uitgeput en anders false. |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) method

Converteert tekens naar bytes.

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Tekens om te coderen. |
| charCount | int | Grootte van invoerbuffer. |
| bytes | **uint8_t** * | Doel-bytebuffer. |
| byteCount | int | Grootte van doelarray. |
| flush | **bool** | Indien true, maakt de interne encoderstatus schoon na berekening. |
| charsUsed | int\& | Referentie naar variabele om het aantal gelezen tekens op te slaan. |
| bytesUsed | int\& | Referentie naar variabele om het aantal geschreven bytes op te slaan. |
| completed | **bool**\& | Referentie naar variabele die true wordt gezet als de invoerbuffer is uitgeput en anders false. |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Encoder](../)
* Naamruimte [System::Text](../../)
* Library [Aspose.Slides](../../../)