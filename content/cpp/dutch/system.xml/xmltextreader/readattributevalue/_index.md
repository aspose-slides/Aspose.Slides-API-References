---
title: ReadAttributeValue()
second_title: Aspose.Slides voor C++ API-referentie
description: Parseert de attribuutwaarde in één of meer Text, EntityReference of EndEntity knooppunten.
type: docs
weight: 560
url: /nl/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue() methode

Parseert de attribuutwaarde in één of meer **[Text](../../../system.text/)**, **EntityReference**, of **EndEntity** knooppunten.

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```

### Retourwaarde

**true** als er knooppunten zijn om terug te geven. **false** als de lezer niet op een attribuutknooppunt is gepositioneerd wanneer de eerste oproep wordt gedaan of als alle attribuutwaarden zijn gelezen. Een leeg attribuut, zoals **misc=\"\"**, geeft **true** terug met één knooppunt met een waarde van [String::Empty](../../../system/string/empty/).

## Zie ook

* Klasse [XmlTextReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)