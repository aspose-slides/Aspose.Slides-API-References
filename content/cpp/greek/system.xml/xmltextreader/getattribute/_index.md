---
title: GetAttribute()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει την τιμή του χαρακτηριστικού με το συγκεκριμένο όνομα.
type: docs
weight: 495
url: /el/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) μέθοδος

Επιστρέφει την τιμή του χαρακτηριστικού με το συγκεκριμένο όνομα.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το πλήρες όνομα του χαρακτηριστικού. |

### Τιμή Επιστροφής

Η τιμή του συγκεκριμένου χαρακτηριστικού. Εάν το χαρακτηριστικό δεν βρεθεί, **nullptr** επιστρέφεται.

## XmlTextReader::GetAttribute(String, String) μέθοδος

Επιστρέφει την τιμή του χαρακτηριστικού με το συγκεκριμένο τοπικό όνομα και το URI του ονοματοχώρου.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του χαρακτηριστικού. |
| namespaceURI | [String](../../../system/string/) | Το URI του ονοματοχώρου του χαρακτηριστικού. |

### Τιμή Επιστροφής

Η τιμή του συγκεκριμένου χαρακτηριστικού. Εάν το χαρακτηριστικό δεν βρεθεί, **nullptr** επιστρέφεται. Αυτή η μέθοδος δεν μετακινεί τον αναγνώστη.

## XmlTextReader::GetAttribute(int32_t) μέθοδος

Επιστρέφει την τιμή του χαρακτηριστικού με το συγκεκριμένο δείκτη.

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| i | **int32_t** | Ο δείκτης του χαρακτηριστικού. Ο δείκτης είναι μηδενικής βάσης. (Το πρώτο χαρακτηριστικό έχει δείκτη 0.) |

### Τιμή Επιστροφής

Η τιμή του συγκεκριμένου χαρακτηριστικού.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlTextReader](../)
* Ονοματοχώρος [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)