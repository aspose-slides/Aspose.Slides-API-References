---
title: ReadAttributeValue()
second_title: Aspose.Slides für C++ API-Referenz
description: Parst den Attributwert in ein oder mehrere Text, EntityReference oder EndEntity Knoten.
type: docs
weight: 430
url: /de/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() Methode

Parst den Attributwert in ein oder mehrere **[Text](../../../system.text/)**, **EntityReference** oder **EndEntity** Knoten.

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```

### Rückgabewert

**true** wenn es Knoten zum Zurückgeben gibt. **false** wenn der Reader nicht auf einem Attributknoten positioniert ist, wenn der erste Aufruf erfolgt, oder wenn alle Attributwerte gelesen wurden. Ein leeres Attribut, zum Beispiel **misc=""**, gibt **true** mit einem einzelnen Knoten zurück, dessen Wert [String::Empty](../../../system/string/empty/) ist.

## Siehe auch

* Klasse [XmlNodeReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)