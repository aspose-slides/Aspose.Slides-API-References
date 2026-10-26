---
title: get_NewParent()
second_title: Aspose.Slides för C++ API-referens
description: "Returnerar värdet av XmlNode::get_ParentNode efter att operationen slutförs."
type: docs
weight: 40
url: /sv/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() metod

Returnerar värdet av [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) efter att operationen slutförts.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```

### Returvärde

Värdet av **ParentNode** efter att operationen slutförts. Denna metod returnerar **nullptr** om noden tas bort. För attributnoder returnerar denna metod värdet [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [XmlNodeChangedEventArgs](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)