---
title: GetChars()
second_title: Aspose.Slides voor C++ API-referentie
description: Haal de tekens op die voortkomen uit het decoderen van een buffer.
type: docs
weight: 53
url: /nl/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method

Haal de tekens op die voortkomen uit het decoderen van een buffer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes om te decoderen. |
| byteIndex | int | Offset van de invoerbuffer. |
| byteCount | int | Grootte van de invoerbuffer. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Doelkarakterbuffer. |
| charIndex | int | Offset van de doelarray. |

### Retourwaarde

Aantal tekens geschreven.

## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) method

Haal de tekens op die voortkomen uit het decoderen van een buffer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes om te decoderen. |
| byteIndex | int | Offset van de invoerbuffer. |
| byteCount | int | Grootte van de invoerbuffer. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Doelkarakterbuffer. |
| charIndex | int | Offset van de doelarray. |
| flush | **bool** | Indien true, reinigt de interne decoderstatus na de berekening. |

### Retourwaarde

Aantal tekens geschreven.

## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) method

Haal de tekens op die voortkomen uit het decoderen van een buffer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes om te decoderen. |
| byteCount | int | Grootte van de invoerbuffer. |
| chars | char_t * | Doelkarakterbuffer. |
| charCount | int | Grootte van de doelarray. |
| flush | **bool** | Indien true, reinigt de interne decoderstatus na de berekening. |

### Retourwaarde

Aantal tekens geschreven.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICUDecoder](../)
* Naamruimte [System::Text](../../)
* Library [Aspose.Slides](../../../)