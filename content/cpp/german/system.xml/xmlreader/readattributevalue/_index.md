---
title: ReadAttributeValue()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn in einer abgeleiteten Klasse überschrieben, analysiert es den Attributwert in ein oder mehrere Text-, EntityReference- oder EndEntity-Knoten.
type: docs
weight: 677
url: /de/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() Methode

Wenn in einer abgeleiteten Klasse überschrieben, analysiert es den Attributwert in ein oder mehrere **[Text](../../../system.text/)**, **EntityReference** oder **EndEntity** Knoten.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```

### Rückgabewert

**true**, wenn Knoten zurückgegeben werden können. **false**, wenn der Reader beim ersten Aufruf nicht auf einem Attributknoten positioniert ist oder wenn alle Attributwerte bereits gelesen wurden. Ein leeres Attribut, zum Beispiel **misc=\"\"**, gibt **true** mit einem einzelnen Knoten zurück, dessen Wert [String::Empty](../../../system/string/empty/) ist.

## Siehe auch

* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)