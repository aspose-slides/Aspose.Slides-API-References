---
title: get_OldParent()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Zwraca wartość XmlNode::get_ParentNode przed rozpoczęciem operacji."
type: docs
weight: 27
url: /pl/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() metoda

Zwraca wartość [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) przed rozpoczęciem operacji.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```

### Wartość zwracana

Wartość **ParentNode** przed rozpoczęciem operacji. Ta metoda zwraca **nullptr**, jeśli węzeł nie miał rodzica. Dla węzłów atrybutu ta metoda zwraca wartość [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [XmlNodeChangedEventArgs](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)