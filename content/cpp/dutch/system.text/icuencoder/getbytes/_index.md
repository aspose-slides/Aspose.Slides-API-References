---
title: GetBytes()
second_title: Aspose.Slides voor C++ API-referentie
description: Haal de bytes op die voortvloeien uit het coderen van een buffer.
type: docs
weight: 53
url: /nl/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) method

Haal de bytes op die voortvloeien uit het coderen van een buffer.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Te coderen tekens. |
| charIndex | int | Offset in bronarray. |
| charCount | int | Lengte van subarray van bron. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Doel-bytebuffer. |
| byteIndex | int | Offset in doelbuffer. |
| flush | **bool** | Indien true, wordt de interne encoder-status na de berekening opgeschoond. |

### Retourwaarde

Aantal bytes geschreven.

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) method

Haal de bytes op die voortvloeien uit het coderen van een buffer.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | const char_t * | Te coderen tekens. |
| charCount | int | Lengte van bronarray. |
| bytes | **uint8_t** * | Doel-bytebuffer. |
| byteCount | int | Grootte van doelbuffer. |
| flush | **bool** | Indien true, wordt de interne encoder-status na de berekening opgeschoond. |

### Retourwaarde

Aantal bytes geschreven.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICUEncoder](../)
* Namespace [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)