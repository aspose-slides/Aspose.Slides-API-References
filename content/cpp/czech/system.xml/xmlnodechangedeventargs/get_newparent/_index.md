---
title: get_NewParent()
second_title: Aspose.Slides pro C++ API Reference
description: "Vrací hodnotu XmlNode::get_ParentNode po dokončení operace."
type: docs
weight: 40
url: /cs/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() metoda

Vrací hodnotu [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) po dokončení operace.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```

### Návratová hodnota

Hodnota **ParentNode** po dokončení operace. Tato metoda vrací **nullptr**, pokud je uzel odstraňován. U atributových uzlů tato metoda vrací hodnotu [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../../xmlnode/)
* Třída [XmlNodeChangedEventArgs](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)