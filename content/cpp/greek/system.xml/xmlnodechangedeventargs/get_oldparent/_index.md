---
title: get_OldParent()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Επιστρέφει την τιμή του XmlNode::get_ParentNode πριν ξεκινήσει η λειτουργία."
type: docs
weight: 27
url: /el/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() μέθοδος

Επιστρέφει την τιμή του [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) πριν ξεκινήσει η λειτουργία.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```

### Τιμή Επιστροφής

Η τιμή του **ParentNode** πριν ξεκινήσει η λειτουργία. Αυτή η μέθοδος επιστρέφει **nullptr** αν ο κόμβος δεν είχε γονέα. Για κόμβους χαρακτηριστικών, αυτή η μέθοδος επιστρέφει την τιμή [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlNode](../../xmlnode/)
* Κλάση [XmlNodeChangedEventArgs](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)