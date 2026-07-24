---
title: CloneNode()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Duplikat dieses Knotens. Entitätsknoten können nicht geklont werden. Der Aufruf dieser Methode für ein XmlEntity-Objekt wirft eine Ausnahme.
type: docs
weight: 170
url: /de/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) Methode


Erstellt ein Duplikat dieses Knotens. Entitätsknoten können nicht geklont werden. Der Aufruf dieser Methode für ein [XmlEntity](../)-Objekt wirft eine Ausnahme.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| deep | **bool** | **true** um den Teilbaum unter dem angegebenen Knoten rekursiv zu klonen; **false** um nur den Knoten selbst zu klonen. |

### Rückgabewert

Eine Kopie des [XmlNode](../../xmlnode/), von dem die Methode aufgerufen wird.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlEntity](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)