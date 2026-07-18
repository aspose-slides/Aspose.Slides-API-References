---
title: GetAttribute()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει την τιμή του χαρακτηριστικού με το καθορισμένο όνομα.
type: docs
weight: 287
url: /el/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) μέθοδος

Επιστρέφει την τιμή του χαρακτηριστικού με το καθορισμένο όνομα.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το πλήρες όνομα του χαρακτηριστικού. |

### Τιμή Επιστροφής

Η τιμή του καθορισμένου χαρακτηριστικού. Εάν το χαρακτηριστικό δεν βρεθεί, **nullptr** επιστρέφεται.

## XmlNodeReader::GetAttribute(String, String) μέθοδος

Επιστρέφει την τιμή του χαρακτηριστικού με το καθορισμένο τοπικό όνομα και το URI του ονοματοχώρου.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το τοπικό όνομα του χαρακτηριστικού. |
| namespaceURI | [String](../../../system/string/) | Το URI του ονομαχώρου του χαρακτηριστικού. |

### Τιμή Επιστροφής

Η τιμή του καθορισμένου χαρακτηριστικού. Εάν το χαρακτηριστικό δεν βρεθεί, **nullptr** επιστρέφεται.

## XmlNodeReader::GetAttribute(int32_t) μέθοδος

Επιστρέφει την τιμή του χαρακτηριστικού με το καθορισμένο δείκτη.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| attributeIndex | **int32_t** | Ο δείκτης του χαρακτηριστικού. Ο δείκτης αρχίζει από το μηδέν. (Το πρώτο χαρακτηριστικό έχει δείκτη 0.) |

### Τιμή Επιστροφής

Η τιμή του καθορισμένου χαρακτηριστικού.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlNodeReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)