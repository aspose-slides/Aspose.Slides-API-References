---
title: get_NewParent()
second_title: Aspose.Slides C++ API referencia
description: "Visszaadja az XmlNode::get_ParentNode értékét a művelet befejezése után."
type: docs
weight: 40
url: /hu/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() method


Visszaadja a [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) értékét a művelet befejezése után.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```


### Visszatérési érték

A **ParentNode** értéke a művelet befejezése után. Ez a metódus **nullptr**-t ad vissza, ha a csomópont el van távolítva. Attribútum csomópontok esetén ez a metódus a [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) értéket adja vissza.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../../xmlnode/)
* Osztály [XmlNodeChangedEventArgs](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)