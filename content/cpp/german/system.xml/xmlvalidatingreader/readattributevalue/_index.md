---
title: ReadAttributeValue()
second_title: Aspose.Slides für C++ API-Referenz
description: Parst den Attributwert in einen oder mehrere Text, EntityReference oder EndEntity Knoten.
type: docs
weight: 508
url: /de/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue() Methode

Parst den Attributwert in ein oder mehrere **[Text](../../../system.text/)**, **EntityReference**, oder **EndEntity** Knoten.

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```

### Rückgabewert

**true** wenn es Knoten zum Zurückgeben gibt. **false** wenn der Reader nicht auf einem Attributknoten positioniert ist, wenn der initiale Aufruf gemacht wird oder wenn alle Attributwerte gelesen wurden. Ein leeres Attribut, zum Beispiel **misc=\"\"**, gibt **true** zurück mit einem einzelnen Knoten mit dem Wert [String::Empty](../../../system/string/empty/).

## Siehe auch

* Klasse [XmlValidatingReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)