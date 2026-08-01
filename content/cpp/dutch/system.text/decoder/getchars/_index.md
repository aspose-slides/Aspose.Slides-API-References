---
title: GetChars()
second_title: Aspose.Slides voor C++ API Referentie
description: Haal de tekens op die voortkomen uit het decoderen van een buffer.
type: docs
weight: 53
url: /nl/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) methode


Haal de tekens op die voortkomen uit het decoderen van een buffer.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes om te decoderen. |
| byteIndex | int | Offset van de invoerbuffer. |
| byteCount | int | Grootte van de invoerbuffer. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Doelcharacterbuffer. |
| charIndex | int | Offset van de doelarray. |

### Retourwaarde

Aantal geschreven tekens.

## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) methode


Haal de tekens op die voortkomen uit het decoderen van een buffer.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes om te decoderen. |
| byteIndex | int | Offset van de invoerbuffer. |
| byteCount | int | Grootte van de invoerbuffer. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Doelcharacterbuffer. |
| charIndex | int | Offset van de doelarray. |
| flush | **bool** | Indien true, wordt de interne decoderstatus na de berekening opgeschoond. |

### Retourwaarde

Aantal geschreven tekens.

## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) methode


Haal de tekens op die voortkomen uit het decoderen van een buffer.

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes om te decoderen. |
| byteCount | int | Grootte van de invoerbuffer. |
| chars | char_t * | Doelcharacterbuffer. |
| charCount | int | Grootte van de doelarray. |
| flush | **bool** | Indien true, wordt de interne decoderstatus na de berekening opgeschoond. |

### Retourwaarde

Aantal geschreven tekens.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Decoder](../)
* Naamruimte [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)