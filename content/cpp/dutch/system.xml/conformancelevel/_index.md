---
title: ConformanceLevel
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de hoeveelheid invoer- of uitvoercontroles die XmlReader- en XmlWriter-objecten uitvoeren.
type: docs
weight: 625
url: /nl/system.xml/conformancelevel/
---
## ConformanceLevel enum

Specificeert de hoeveelheid invoer- of uitvoercontroles die [XmlReader](../xmlreader/) en [XmlWriter](../xmlwriter/) objecten uitvoeren.

```cpp
enum class ConformanceLevel
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | 0 | Het [XmlReader](../xmlreader/) of [XmlWriter](../xmlwriter/) object detecteert automatisch of er document-niveau of fragment-niveau controle moet worden uitgevoerd, en voert de juiste controle uit. Als je een ander [XmlReader](../xmlreader/) of [XmlWriter](../xmlwriter/) object omsluit, voert het buitenste object geen extra conformiteitscontrole uit. Conformiteitscontrole wordt overgelaten aan het onderliggende object. |
| Fragment | 1 | De XML-gegevens zijn een [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities), zoals gedefinieerd door de W3C. Dit conformiteitsniveau vertegenwoordigt een XML-document dat mogelijk geen wortelelement heeft maar anders goed gevormd is. Dit niveau van controle zorgt ervoor dat de stroom die wordt gelezen of geschreven kan worden geconsumeerd door elke processor als een [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities). |
| Document | 2 | De XML-gegevens voldoen aan de regels voor een goed gevormde [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed), zoals gedefinieerd door de W3C. Dit niveau van controle zorgt ervoor dat de stroom die wordt gelezen of geschreven kan worden geconsumeerd door elke processor als een [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed). |

## Zie ook

* Naamruimte [System::Xml](../)
* Bibliotheek [Aspose.Slides](../../)