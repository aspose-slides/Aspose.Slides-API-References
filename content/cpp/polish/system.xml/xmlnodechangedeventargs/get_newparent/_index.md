---
title: get_NewParent()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Zwraca wartość XmlNode::get_ParentNode po zakończeniu operacji."
type: docs
weight: 40
url: /pl/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() metoda


Zwraca wartość [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) po zakończeniu operacji.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```


### Wartość zwracana

Wartość **ParentNode** po zakończeniu operacji. Ta metoda zwraca **nullptr**, jeśli węzeł jest usuwany. Dla węzłów atrybutów, ta metoda zwraca wartość [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [XmlNodeChangedEventArgs](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)