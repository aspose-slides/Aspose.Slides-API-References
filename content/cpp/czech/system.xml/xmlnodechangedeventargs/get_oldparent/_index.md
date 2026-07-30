---
title: get_OldParent()
second_title: Aspose.Slides pro C++ API Reference
description: "Vrací hodnotu XmlNode::get_ParentNode před zahájením operace."
type: docs
weight: 27
url: /cs/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() metoda


Vrací hodnotu [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) před zahájením operace.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```


### Návratová hodnota

Hodnota **ParentNode** před zahájením operace. Tato metoda vrací **nullptr**, pokud uzel neměl nadřazený uzel. Pro uzly atributů tato metoda vrací hodnotu [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../../xmlnode/)
* Třída [XmlNodeChangedEventArgs](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)