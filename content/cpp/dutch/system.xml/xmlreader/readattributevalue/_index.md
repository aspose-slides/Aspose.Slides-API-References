---
title: ReadAttributeValue()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer overschreven in een afgeleide klasse, parseert de attribuutwaarde in een of meer Text, EntityReference, of EndEntity knooppunten.
type: docs
weight: 677
url: /nl/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() methode


Wanneer overschreven in een afgeleide klasse, parseert de attribuutwaarde in een of meer **[Text](../../../system.text/)**, **EntityReference**, of **EndEntity** knooppunten.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```


### Retourwaarde

**true** als er knooppunten zijn om terug te geven. **false** als de reader niet gepositioneerd is op een attribuutknoop wanneer de eerste oproep wordt gedaan of als alle attribuutwaarden zijn gelezen. Een leeg attribuut, zoals **misc=\"\"**, geeft **true** terug met één knooppunt met een waarde van [String::Empty](../../../system/string/empty/).

## Zie ook

* Klasse [XmlReader](../)
* Naamruimte [System::Xml](../../)
* Library [Aspose.Slides](../../../)