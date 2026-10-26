---
title: get_OldParent()
second_title: Aspose.Slides für C++ API Referenz
description: "Gibt den Wert von XmlNode::get_ParentNode zurück, bevor die Operation begann."
type: docs
weight: 27
url: /de/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() Methode

Gibt den Wert von [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) zurück, bevor die Operation begann.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```

### Rückgabewert

Der Wert von **ParentNode** bevor die Operation begann. Diese Methode gibt **nullptr** zurück, wenn der Knoten keinen übergeordneten Knoten hatte. Für Attributknoten gibt diese Methode den [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/)-Wert zurück.

## Siehe auch

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlNodeChangedEventArgs](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)