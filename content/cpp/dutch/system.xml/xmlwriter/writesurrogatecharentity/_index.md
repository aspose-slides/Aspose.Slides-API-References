---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer overschreven in een afgeleide klasse, genereert en schrijft de surrogate character entity voor het surrogate character pair.
type: docs
weight: 261
url: /nl/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) methode

Wanneer hij wordt overschreven in een afgeleide klasse, genereert en schrijft hij de surrogate character entity voor het surrogate character pair.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lowChar | char16_t | De low surrogate. Dit moet een waarde zijn tussen 0xDC00 en 0xDFFF. |
| highChar | char16_t | De high surrogate. Dit moet een waarde zijn tussen 0xD800 en 0xDBFF. |

## Zie ook

* Klasse [XmlWriter](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)