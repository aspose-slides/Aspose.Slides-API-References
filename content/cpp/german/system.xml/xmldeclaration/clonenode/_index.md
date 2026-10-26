---
title: CloneNode()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Duplikat dieses Knotens.
type: docs
weight: 157
url: /de/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) Methode


Erstellt ein Duplikat dieses Knotens.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| deep | **bool** | **true** um den Teilbaum unter dem angegebenen Knoten rekursiv zu klonen; **false** um nur den Knoten selbst zu klonen. Da [XmlDeclaration](../)-Knoten keine Kinder haben, enthält der geklonte Knoten immer den Datenwert, unabhängig von der Parametereinstellung. |

### Rückgabewert

Der geklonte Knoten.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlDeclaration](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)