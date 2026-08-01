---
title: Fallback()
second_title: Aspose.Slides voor C++ API-referentie
description: Implementeert de daadwerkelijke fallback-procedure.
type: docs
weight: 14
url: /nl/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) methode


Implementeert de daadwerkelijke fallback-procedure.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) van bytes inclusief de byte die de decoder niet kan decoderen. |
| index | int | [Index](../../../system/index/) van byte die de fout veroorzaakte. |

### Retourwaarde

Waar als de buffer onbekende bytes verwerkt, onwaar als deze ze negeert.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [DecoderFallbackBuffer](../)
* Naamruimte [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)