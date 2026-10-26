---
title: get_OldParent()
second_title: Aspose.Slides C++ API-referencia
description: "Visszaadja az XmlNode::get_ParentNode értékét a művelet kezdete előtt."
type: docs
weight: 27
url: /hu/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() metódus

Visszaadja a [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) értékét a művelet kezdete előtt.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```

### Visszatérési érték

A **ParentNode** értéke a művelet kezdete előtt. Ez a metódus **nullptr** értéket ad vissza, ha a csomópontnak nem volt szülője. Attribútum csomópontok esetén ez a metódus a [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) értéket adja vissza.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../../xmlnode/)
* Osztály [XmlNodeChangedEventArgs](../)
* Névterület [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)