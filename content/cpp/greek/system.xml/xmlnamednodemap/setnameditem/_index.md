---
title: SetNamedItem()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Προσθέτει ένα XmlNode χρησιμοποιώντας την τιμή XmlNode::get_Name του."
type: docs
weight: 27
url: /el/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) μέθοδος

Προσθέτει ένα [XmlNode](../../xmlnode/) χρησιμοποιώντας την τιμή του [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Ένα [XmlNode](../../xmlnode/) για αποθήκευση στο [XmlNamedNodeMap](../). Εάν ένας κόμβος με αυτό το όνομα υπάρχει ήδη στον χάρτη, αντικαθίσταται από το νέο. |

### Τιμή Επιστροφής

Αν το **node** αντικαθιστά έναν υπάρχοντα κόμβο με το ίδιο όνομα, επιστρέφεται ο παλιός κόμβος· διαφορετικά, επιστρέφεται **nullptr**.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlNode](../../xmlnode/)
* Κλάση [XmlNamedNodeMap](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)