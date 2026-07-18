---
title: idx_get()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει το χαρακτηριστικό με το καθορισμένο δείκτη.
type: docs
weight: 1
url: /el/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) μέθοδος


Επιστρέφει το χαρακτηριστικό με το καθορισμένο δείκτη.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| i | **int32_t** | Ο δείκτης του χαρακτηριστικού. |

### Τιμή Επιστροφής

Το χαρακτηριστικό στον καθορισμένο δείκτη.

## XmlAttributeCollection::idx_get(const String\&) μέθοδος


Επιστρέφει το χαρακτηριστικό με το καθορισμένο όνομα.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Το πλήρες όνομα του χαρακτηριστικού. |

### Τιμή Επιστροφής

Το χαρακτηριστικό με το καθορισμένο όνομα. Εάν το χαρακτηριστικό δεν υπάρχει, αυτή η μέθοδος επιστρέφει **nullptr**.

## XmlAttributeCollection::idx_get(const String\&, const String\&) μέθοδος


Επιστρέφει το χαρακτηριστικό με το καθορισμένο τοπικό όνομα και το URI (Uniform Resource Identifier) του ονοματοχώρου.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Το τοπικό όνομα του χαρακτηριστικού. |
| namespaceURI | const [String](../../../system/string/)\& | Το URI του ονοματοχώρου του χαρακτηριστικού. |

### Τιμή Επιστροφής

Το χαρακτηριστικό με το καθορισμένο τοπικό όνομα και το URI του ονοματοχώρου. Εάν το χαρακτηριστικό δεν υπάρχει, αυτή η μέθοδος επιστρέφει **nullptr**.

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlAttribute](../../xmlattribute/)
* Κλάση [XmlAttributeCollection](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)