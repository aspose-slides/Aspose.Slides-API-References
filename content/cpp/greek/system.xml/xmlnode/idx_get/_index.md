---
title: idx_get()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Επιστρέφει το πρώτο παιδικό στοιχείο με το καθορισμένο XmlNode::get_Name."
type: docs
weight: 586
url: /el/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) μέθοδος

Επιστρέφει το πρώτο παιδικό στοιχείο με το καθορισμένο [XmlNode::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το πλήρες όνομα του στοιχείου που θα ανακτηθεί. |

### Τιμή Επιστροφής

Το πρώτο [XmlElement](../../xmlelement/) που ταιριάζει με το καθορισμένο όνομα. Επιστρέφει **nullptr** αν δεν υπάρχει αντιστοιχία.

## XmlNode::idx_get(String, String) μέθοδος

Επιστρέφει το πρώτο παιδικό στοιχείο με τις καθορισμένες τιμές [XmlNode::get_LocalName](../get_localname/) και [XmlNode::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Το τοπικό όνομα του στοιχείου. |
| ns | [String](../../../system/string/) | Το URI του χώρου ονομάτων του στοιχείου. |

### Τιμή Επιστροφής

Το πρώτο [XmlElement](../../xmlelement/) με το αντίστοιχο **localname** και **ns**. Επιστρέφει **nullptr** αν δεν υπάρχει αντιστοιχία.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlElement](../../xmlelement/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlNode](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)