---
title: get_NewParent()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt den Wert von XmlNode::get_ParentNode zurück, nachdem die Operation abgeschlossen ist."
type: docs
weight: 40
url: /de/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() Methode


Gibt den Wert von [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) zurück, nachdem die Operation abgeschlossen ist.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```


### Rückgabewert

Der Wert des **ParentNode** nach Abschluss der Operation. Diese Methode gibt **nullptr** zurück, wenn der Knoten entfernt wird. Für Attributknoten gibt diese Methode den [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/)-Wert zurück.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlNodeChangedEventArgs](../)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)