---
title: ReadAttributeValue()
second_title: Aspose.Slides voor C++ API-referentie
description: Parseert de attribuutwaarde naar een of meer Text-, EntityReference- of EndEntity-knooppunten.
type: docs
weight: 430
url: /nl/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() methode

Parseert de attribuutwaarde naar een of meer **[Text](../../../system.text/)**, **EntityReference**, of **EndEntity** knooppunten.

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```

### Retourwaarde

**true** als er knooppunten zijn om terug te geven. **false** als de lezer niet is gepositioneerd op een attribuutknooppunt wanneer de eerste oproep wordt gedaan of als alle attribuutwaarden zijn gelezen. Een leeg attribuut, zoals **misc=\"\"**, geeft **true** terug met één knooppunt met een waarde van [String::Empty](../../../system/string/empty/).

## Zie ook

* Klasse [XmlNodeReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)