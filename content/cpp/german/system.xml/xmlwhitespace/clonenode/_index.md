---
title: CloneNode()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Duplikat dieses Knotens.
type: docs
weight: 79
url: /de/system.xml/xmlwhitespace/clonenode/
---
## XmlWhitespace::CloneNode(bool) Methode

Erstellt ein Duplikat dieses Knotens.

```cpp
SharedPtr<XmlNode> System::Xml::XmlWhitespace::CloneNode(bool deep) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| deep | **bool** | **true** zum rekursiven Klonen des Unterbaums unter dem angegebenen Knoten; **false** zum Klonen nur des Knotens selbst. Für Whitespace-Knoten enthält der geklonte Knoten immer den Datenwert, unabhängig von der Parametereinstellung. |

### Rückgabewert

Der geklonte Knoten.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlWhitespace](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)