---
title: get_NewParent()
second_title: Αναφορά API του Aspose.Slides για C++
description: "Επιστρέφει την τιμή του XmlNode::get_ParentNode μετά την ολοκλήρωση της λειτουργίας."
type: docs
weight: 40
url: /el/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() method


Επιστρέφει την τιμή του [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) μετά την ολοκλήρωση της λειτουργίας.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```


### Τιμή Επιστροφής

Η τιμή του **ParentNode** μετά την ολοκλήρωση της λειτουργίας. Αυτή η μέθοδος επιστρέφει **nullptr** εάν ο κόμβος αφαιρείται. Για κόμβους χαρακτηριστικών, αυτή η μέθοδος επιστρέφει την τιμή [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlNode](../../xmlnode/)
* Κλάση [XmlNodeChangedEventArgs](../)
* Χώρος ονομάτων [System::Xml](../../)
* Library [Aspose.Slides](../../../)