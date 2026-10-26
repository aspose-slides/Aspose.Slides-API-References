---
title: SetNamedItem()
second_title: Aspose.Slides für C++ API-Referenz
description: "Fügt einen XmlNode mithilfe seines XmlNode::get_Name-Ergebnisses hinzu."
type: docs
weight: 14
url: /de/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) Methode

Fügt ein [XmlNode](../../xmlnode/) mit dessen [XmlNode::get_Name](../../xmlnode/get_name/) Ergebnis hinzu.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Ein Attributknoten, der in dieser Sammlung gespeichert wird. Der Knoten ist später über den Namen des Knotens zugänglich. Wenn bereits ein Knoten mit diesem Namen in der Sammlung vorhanden ist, wird er durch den neuen ersetzt; andernfalls wird der Knoten am Ende der Sammlung angehängt. |

### Rückgabewert

Wenn **node** einen bestehenden Knoten mit demselben Namen ersetzt, wird der alte Knoten zurückgegeben; andernfalls wird der hinzugefügte Knoten zurückgegeben.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlAttributeCollection](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)