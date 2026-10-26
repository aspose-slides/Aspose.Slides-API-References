---
title: RemoveNamedItem()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αφαιρεί τον κόμβο από το XmlNamedNodeMap.
type: docs
weight: 40
url: /el/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) μέθοδος

Αφαιρεί τον κόμβο από το [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το πλήρες όνομα του κόμβου για αφαίρεση. Το όνομα ταιριάζει με την τιμή [XmlNode::get_Name](../../xmlnode/get_name/) του αντίστοιχου κόμβου. |

### Τιμή Επιστροφής

Το [XmlNode](../../xmlnode/) αφαιρέθηκε από αυτό το [XmlNamedNodeMap](../) ή **nullptr** εάν δεν βρέθηκε αντίστοιχος κόμβος.

## XmlNamedNodeMap::RemoveNamedItem(String, String) μέθοδος

Αφαιρεί έναν κόμβο με τις αντίστοιχες τιμές [XmlNode::get_LocalName](../../xmlnode/get_localname/) και [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του κόμβου για αφαίρεση. |
| namespaceURI | [String](../../../system/string/) | Το URI του ονοματοχώρου του κόμβου για αφαίρεση. |

### Τιμή Επιστροφής

Το [XmlNode](../../xmlnode/) αφαιρεθεί ή **nullptr** εάν δεν βρέθηκε αντίστοιχος κόμβος.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)