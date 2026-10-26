---
title: ReadAttributeValue()
second_title: Aspose.Slides for C++ API-referentie
description: Parseert de attribuutwaarde in één of meer Text, EntityReference, of EndEntity knooppunten.
type: docs
weight: 508
url: /nl/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue() methode


Parseert de attribuutwaarde in een of meer **[Text](../../../system.text/)**, **EntityReference**, of **EndEntity** knooppunten.

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```


### Retourwaarde

**true** als er knooppunten zijn om te retourneren. **false** als de lezer niet op een attribuutknooppunt staat wanneer de eerste oproep wordt gedaan of als alle attribuutwaarden zijn gelezen. Een leeg attribuut, zoals **misc=\"\"**, retourneert **true** met een enkel knooppunt met een waarde van [String::Empty](../../../system/string/empty/).

## Zie ook

* Klasse [XmlValidatingReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)