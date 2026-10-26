---
title: idx_get()
second_title: Aspose.Slides για C++ API Αναφορά
description: Όταν παρακαμφθεί σε παράγωγη κλάση, λαμβάνει την τιμή του χαρακτηριστικού με τον καθορισμένο δείκτη.
type: docs
weight: 612
url: /el/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) μέθοδος

Όταν παρακαμφθεί σε παράγωγη κλάση, λαμβάνει την τιμή του χαρακτηριστικού με το καθορισμένο δείκτη.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| i | **int32_t** | Ο δείκτης του χαρακτηριστικού. |

### Τιμή Επιστροφής

Η τιμή του καθορισμένου χαρακτηριστικού.

## XmlReader::idx_get(String) μέθοδος

Όταν παρακαμφθεί σε παράγωγη κλάση, λαμβάνει την τιμή του χαρακτηριστικού με την καθορισμένη [XmlReader::get_Name](../get_name/) τιμή.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το πλήρες όνομα του χαρακτηριστικού. |

### Τιμή Επιστροφής

Η τιμή του καθορισμένου χαρακτηριστικού. Αν το χαρακτηριστικό δεν βρεθεί, **nullptr** επιστρέφεται.

## XmlReader::idx_get(String, String) μέθοδος

Όταν παρακαμφθεί σε παράγωγη κλάση, λαμβάνει την τιμή του χαρακτηριστικού με τις καθορισμένες [XmlReader::get_LocalName](../get_localname/) και [XmlReader::get_NamespaceURI](../get_namespaceuri/) τιμές.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το τοπικό όνομα του χαρακτηριστικού. |
| namespaceURI | [String](../../../system/string/) | Το URI του χώρου ονομάτων του χαρακτηριστικού. |

### Τιμή Επιστροφής

Η τιμή του καθορισμένου χαρακτηριστικού. Αν το χαρακτηριστικό δεν βρεθεί, **nullptr** επιστρέφεται.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)