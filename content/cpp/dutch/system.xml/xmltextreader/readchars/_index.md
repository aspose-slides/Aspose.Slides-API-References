---
title: ReadChars()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest de tekstinhoud van een element naar een tekenbuffer. Deze methode is ontworpen om grote stromen van ingebedde tekst te lezen door het opeenvolgend aan te roepen.
type: docs
weight: 755
url: /nl/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) methode

Leest de tekstinhoud van een element naar een tekenbuffer. Deze methode is ontworpen om grote stromen van ingebedde tekst te lezen door het opeenvolgend aan te roepen.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | De array van tekens die fungeert als de buffer waarin de tekstinhoud wordt geschreven. |
| index | **int32_t** | De positie binnen **buffer** waar de methode kan beginnen met het schrijven van tekstinhoud. |
| count | **int32_t** | Het aantal tekens dat in **buffer** moet worden geschreven. |

### Retourwaarde

Het aantal gelezen tekens. Dit kan 0 zijn als de lezer niet op een element is gepositioneerd of als er geen verdere tekstinhoud meer te retourneren is in de huidige context.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)