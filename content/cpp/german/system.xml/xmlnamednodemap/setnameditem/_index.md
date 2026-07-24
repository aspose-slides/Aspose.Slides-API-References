---
title: SetNamedItem()
second_title: Aspose.Slides für C++ API Referenz
description: "Fügt einen XmlNode mithilfe seines XmlNode::get_Name-Werts hinzu."
type: docs
weight: 27
url: /de/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) Methode

Fügt ein [XmlNode](../../xmlnode/) mithilfe seines [XmlNode::get_Name](../../xmlnode/get_name/) Werts hinzu.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Ein [XmlNode](../../xmlnode/) zum Speichern im [XmlNamedNodeMap](../). Wenn bereits ein Knoten mit diesem Namen in der Karte vorhanden ist, wird er durch den neuen ersetzt. |

### Rückgabewert

Wenn **node** einen vorhandenen Knoten mit demselben Namen ersetzt, wird der alte Knoten zurückgegeben; andernfalls wird **nullptr** zurückgegeben.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlNamedNodeMap](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)