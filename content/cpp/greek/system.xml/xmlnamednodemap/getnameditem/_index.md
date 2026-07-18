---
title: GetNamedItem()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ανακτά ένα XmlNode που καθορίζεται με το όνομα.
type: docs
weight: 14
url: /el/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) method

Ανακτά ένα [XmlNode](../../xmlnode/) που καθορίζεται με το όνομα.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το πλήρες όνομα του κόμβου που θα ανακτηθεί. Συμφωνεί με την τιμή [XmlNode::get_Name](../../xmlnode/get_name/) του αντίστοιχου κόμβου. |

### Τιμή Επιστροφής

Ένα [XmlNode](../../xmlnode/) με το καθορισμένο όνομα ή **nullptr** εάν δεν βρεθεί αντίστοιχος κόμβος.

## XmlNamedNodeMap::GetNamedItem(String, String) method

Ανακτά έναν κόμβο με τις αντίστοιχες τιμές [XmlNode::get_LocalName](../../xmlnode/get_localname/) και [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του κόμβου που θα ανακτηθεί. |
| namespaceURI | [String](../../../system/string/) | Το Uniform Resource Identifier (URI) του χώρου ονομάτων του κόμβου που θα ανακτηθεί. |

### Τιμή Επιστροφής

Ένα [XmlNode](../../xmlnode/) με το αντίστοιχο τοπικό όνομα και το URI του χώρου ονομάτων ή **nullptr** εάν δεν βρεθεί αντίστοιχος κόμβος.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlNode](../../xmlnode/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlNamedNodeMap](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)