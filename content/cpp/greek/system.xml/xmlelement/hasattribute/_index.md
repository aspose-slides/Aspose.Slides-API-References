---
title: HasAttribute()
second_title: Aspose.Slides για C++ αναφορά API
description: Καθορίζει εάν ο τρέχων κόμβος διαθέτει ένα χαρακτηριστικό με το καθορισμένο όνομα.
type: docs
weight: 300
url: /el/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) μέθοδος

Καθορίζει εάν ο τρέχων κόμβος διαθέτει ένα χαρακτηριστικό με το καθορισμένο όνομα.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το όνομα του χαρακτηριστικού που θα βρεθεί. Πρόκειται για ένα πλήρες όνομα. Συμφωνεί με την τιμή **get_Name** του αντίστοιχου κόμβου. |

### Τιμή Επιστροφής

**true** εάν ο τρέχων κόμβος διαθέτει το καθορισμένο χαρακτηριστικό· διαφορετικά, **false**.

## XmlElement::HasAttribute(String, String) μέθοδος

Καθορίζει εάν ο τρέχων κόμβος διαθέτει ένα χαρακτηριστικό με το καθορισμένο τοπικό όνομα και το URI του χώρου ονομάτων.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του χαρακτηριστικού που θα βρεθεί. |
| namespaceURI | [String](../../../system/string/) | Το URI του χώρου ονομάτων του χαρακτηριστικού που θα βρεθεί. |

### Τιμή Επιστροφής

**true** εάν ο τρέχων κόμβος διαθέτει το καθορισμένο χαρακτηριστικό· διαφορετικά, **false**.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlElement](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)