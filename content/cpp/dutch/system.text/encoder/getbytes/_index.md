---
title: GetBytes()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de bytes op die voortkomen uit het coderen van een buffer.
type: docs
weight: 53
url: /nl/system.text/encoder/getbytes/
---
## Encoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) methode


Haalt de bytes op die voortkomen uit het coderen van een buffer.

```cpp
virtual int System::Text::Encoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Lettertekens om te coderen. |
| charIndex | int | Bronarray-offset. |
| charCount | int | Lengte van de subarray van de bron. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Doel-bytebuffer. |
| byteIndex | int | Doelbuffer-offset. |
| flush | **bool** | Indien true, wordt de interne encoderstatus gewist na de berekening. |

### Retourwaarde

Aantal geschreven bytes.

## Encoder::GetBytes(const char_t *, int, uint8_t *, int, bool) methode


Haalt de bytes op die voortkomen uit het coderen van een buffer.

```cpp
virtual int System::Text::Encoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | const char_t * | Lettertekens om te coderen. |
| charCount | int | Bronarray-lengte. |
| bytes | **uint8_t** * | Doel-bytebuffer. |
| byteCount | int | Grootte van de doelbuffer. |
| flush | **bool** | Indien true, wordt de interne encoderstatus gewist na de berekening. |

### Retourwaarde

Aantal geschreven bytes.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Encoder](../)
* Naamruimte [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)