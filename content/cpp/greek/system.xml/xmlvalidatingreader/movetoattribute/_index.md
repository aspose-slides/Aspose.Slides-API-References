---
title: MoveToAttribute()
second_title: Aspose.Slides για την αναφορά API C++
description: Μετακινείται στο χαρακτηριστικό με το καθορισμένο όνομα.
type: docs
weight: 456
url: /el/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) μέθοδος

Μετακινείται στο χαρακτηριστικό με το καθορισμένο όνομα.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το πλήρες όνομα του χαρακτηριστικού. |

### Τιμή Επιστροφής

**true** εάν βρεθεί το χαρακτηριστικό· διαφορετικά, **false**. Αν **false**, η θέση του αναγνώστη δεν αλλάζει.

## XmlValidatingReader::MoveToAttribute(String, String) μέθοδος

Μετακινείται στο χαρακτηριστικό με το καθορισμένο τοπικό όνομα και το URI του χώρου ονομάτων (Uniform Resource Identifier).

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του χαρακτηριστικού. |
| namespaceURI | [String](../../../system/string/) | Το URI του χώρου ονομάτων του χαρακτηριστικού. |

### Τιμή Επιστροφής

**true** εάν βρεθεί το χαρακτηριστικό· διαφορετικά, **false**. Αν **false**, η θέση του αναγνώστη δεν αλλάζει.

## XmlValidatingReader::MoveToAttribute(int32_t) μέθοδος

Μετακινείται στο χαρακτηριστικό με το καθορισμένο δείκτη.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| i | **int32_t** | Το δείκτη του χαρακτηριστικού. |

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlValidatingReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)