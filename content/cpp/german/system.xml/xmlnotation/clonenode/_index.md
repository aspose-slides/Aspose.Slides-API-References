---
title: CloneNode()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Kopie dieses Knotens. Notationsknoten können nicht dupliziert werden. Das Aufrufen dieser Methode an einem XmlNotation-Objekt wirft eine Ausnahme.
type: docs
weight: 118
url: /de/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) method


Erstellt eine Kopie dieses Knotens. Notationsknoten können nicht dupliziert werden. Das Aufrufen dieser Methode an einem [XmlNotation](../)-Objekt wirft eine Ausnahme.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| deep | **bool** | **true** um den Unterbaum unter dem angegebenen Knoten rekursiv zu klonen; **false** um nur den Knoten selbst zu klonen. |

### Rückgabewert

Eine [XmlNode](../../xmlnode/) Kopie des Knotens, von dem die Methode aufgerufen wird.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNotation](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)