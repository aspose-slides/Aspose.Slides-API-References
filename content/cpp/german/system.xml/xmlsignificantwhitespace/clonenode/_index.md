---
title: CloneNode()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Kopie dieses Knotens.
type: docs
weight: 79
url: /de/system.xml/xmlsignificantwhitespace/clonenode/
---
## XmlSignificantWhitespace::CloneNode(bool) Methode

Erstellt eine Kopie dieses Knotens.

```cpp
SharedPtr<XmlNode> System::Xml::XmlSignificantWhitespace::CloneNode(bool deep) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| deep | **bool** | **true** um den Unterbaum des angegebenen Knotens rekursiv zu klonen; **false** um nur den Knoten selbst zu klonen. Für signifikante Leerzeichenknoten enthält der geklonte Knoten immer den Datenwert, unabhängig von der Parametereinstellung. |

### Rückgabewert

Der geklonte Knoten.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlSignificantWhitespace](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)