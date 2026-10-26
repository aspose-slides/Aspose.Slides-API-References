---
title: get_OldParent()
second_title: Aspose.Slides för C++ API-referens
description: "Returnerar värdet av XmlNode::get_ParentNode innan operationen påbörjades."
type: docs
weight: 27
url: /sv/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() metod


Returnerar värdet av [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) innan operationen påbörjades.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```


### Returvärde

Värdet av **ParentNode** innan operationen påbörjades. Denna metod returnerar **nullptr** om noden inte hade en förälder. För attributnoder returnerar denna metod [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) värdet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [XmlNodeChangedEventArgs](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)