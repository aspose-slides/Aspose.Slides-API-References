---
title: Convert()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert tekens naar bytes.
type: docs
weight: 66
url: /nl/system.text/icuencoder/convert/
---
## ICUEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) methode


Converteert tekens naar bytes.

```cpp
virtual void System::Text::ICUEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tekens om te coderen. |
| charIndex | int | Offset van de invoerbuffer. |
| charCount | int | Grootte van de invoerbuffer. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Doelbytebuffer. |
| byteIndex | int | Offset van de doelarray. |
| byteCount | int | Grootte van de doelarray. |
| flush | **bool** | Indien true, maakt de interne encoderstatus schoon na de berekening. |
| charsUsed | int\& | Referentie naar variabele om het aantal gelezen tekens op te slaan. |
| bytesUsed | int\& | Referentie naar variabele om het aantal geschreven bytes op te slaan. |
| completed | **bool**\& | Referentie naar variabele die true krijgt als de invoerbuffer opgebruikt is en anders false. |

## ICUEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) methode


Converteert tekens naar bytes.

```cpp
virtual void System::Text::ICUEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Tekens om te coderen. |
| charCount | int | Grootte van de invoerbuffer. |
| bytes | **uint8_t** * | Doelbytebuffer. |
| byteCount | int | Grootte van de doelarray. |
| flush | **bool** | Indien true, maakt de interne encoderstatus schoon na de berekening. |
| charsUsed | int\& | Referentie naar variabele om het aantal gelezen tekens op te slaan. |
| bytesUsed | int\& | Referentie naar variabele om het aantal geschreven bytes op te slaan. |
| completed | **bool**\& | Referentie naar variabele die true krijgt als de invoerbuffer opgebruikt is en anders false. |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)