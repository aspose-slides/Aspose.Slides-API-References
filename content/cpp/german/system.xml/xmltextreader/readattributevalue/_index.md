---
title: ReadAttributeValue()
second_title: Aspose.Slides für C++ API-Referenz
description: Parst den Attributwert in ein oder mehrere Text, EntityReference oder EndEntity Knoten.
type: docs
weight: 560
url: /de/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue() Methode

Parst den Attributwert in ein oder mehrere **[Text](../../../system.text/)**, **EntityReference**, oder **EndEntity** Knoten.

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```

### Rückgabewert

**true**, wenn Knoten zurückzugeben sind. **false**, wenn der Reader nicht auf einem Attributknoten positioniert ist, wenn der erste Aufruf erfolgt, oder wenn alle Attributwerte gelesen wurden. Ein leeres Attribut, z. B. **misc=\"\"**, gibt **true** zurück mit einem einzelnen Knoten mit dem Wert [String::Empty](../../../system/string/empty/).

## Siehe auch

* Klasse [XmlTextReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)