---
title: SetAttributeNode()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει το καθορισμένο XmlAttribute.
type: docs
weight: 261
url: /el/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) μέθοδος

Προσθέτει το καθορισμένο [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Ο κόμβος [XmlAttribute](../../xmlattribute/) που θα προστεθεί στη συλλογή χαρακτηριστικών για αυτό το στοιχείο. |

### Τιμή Επιστροφής

Εάν το χαρακτηριστικό αντικαταστήσει ένα υπάρχον χαρακτηριστικό με το ίδιο όνομα, επιστρέφεται η παλιά [XmlAttribute](../../xmlattribute/)· διαφορετικά, επιστρέφεται **nullptr**.

## XmlElement::SetAttributeNode(String, String) μέθοδος

Προσθέτει το καθορισμένο [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του χαρακτηριστικού. |
| namespaceURI | [String](../../../system/string/) | Το URI του χώρου ονομάτων του χαρακτηριστικού. |

### Τιμή Επιστροφής

Το [XmlAttribute](../../xmlattribute/) που θα προστεθεί.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlAttribute](../../xmlattribute/)
* Κλάση [XmlElement](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Xml](../../)
* Library [Aspose.Slides](../../../)