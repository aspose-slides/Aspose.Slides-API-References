---
title: RemoveAttributeNode()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αφαιρεί το καθορισμένο XmlAttribute.
type: docs
weight: 274
url: /el/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) μέθοδος


Αφαιρεί το καθορισμένο [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Ο κόμβος [XmlAttribute](../../xmlattribute/) προς αφαίρεση. Εάν το αφαιρεθέντα χαρακτηριστικό έχει προεπιλεγμένη τιμή, αυτή αντικαθίσταται αμέσως. |

### Τιμή Επιστροφής

Το αφαιρεθέν [XmlAttribute](../../xmlattribute/) ή **nullptr** εάν **oldAttr** δεν είναι κόμβος χαρακτηριστικού του [XmlElement](../).

## XmlElement::RemoveAttributeNode(String, String) μέθοδος


Αφαιρεί το [XmlAttribute](../../xmlattribute/) που καθορίζεται από το τοπικό όνομα και το URI του χώρου ονομάτων. (Εάν το αφαιρεθέντα χαρακτηριστικό έχει προεπιλεγμένη τιμή, αυτή αντικαθίσταται αμέσως).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του χαρακτηριστικού. |
| namespaceURI | [String](../../../system/string/) | Το URI του χώρου ονομάτων του χαρακτηριστικού. |

### Τιμή Επιστροφής

Το αφαιρεθέν [XmlAttribute](../../xmlattribute/) ή **nullptr** εάν το [XmlElement](../) δεν διαθέτει αντίστοιχο κόμβο χαρακτηριστικού.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlAttribute](../../xmlattribute/)
* Κλάση [XmlElement](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)