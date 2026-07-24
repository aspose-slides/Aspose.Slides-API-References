---
title: CloneNode()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Duplikat dieses Knotens.
type: docs
weight: 53
url: /de/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) Methode


Erstellt ein Duplikat dieses Knotens.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| deep | **bool** | **true** um den Unterbaum unter dem angegebenen Knoten rekursiv zu klonen; **false** um nur den Knoten selbst zu klonen. Da CDATA-Knoten keine Kinder haben, wird der geklonte Knoten unabhängig von der Parametereinstellung immer den Dateninhalt enthalten. |

### Rückgabewert

Der geklonte Knoten.

## Siehe auch

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlCDataSection](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)