---
title: MoveToAttribute()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετακινείται στο χαρακτηριστικό με το καθορισμένο όνομα.
type: docs
weight: 300
url: /el/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) μέθοδος

Μετακινείται στο χαρακτηριστικό με το καθορισμένο όνομα.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το πλήρες όνομα του χαρακτηριστικού. |

### Τιμή Επιστροφής

**true** εάν το χαρακτηριστικό βρεθεί· διαφορετικά, **false**. Εάν **false**, η θέση του αναγνώστη δεν αλλάζει.

## XmlNodeReader::MoveToAttribute(String, String) μέθοδος

Μετακινείται στο χαρακτηριστικό με το καθορισμένο τοπικό όνομα και το URI του namespace.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το τοπικό όνομα του χαρακτηριστικού. |
| namespaceURI | [String](../../../system/string/) | Το URI του namespace του χαρακτηριστικού. |

### Τιμή Επιστροφής

**true** εάν το χαρακτηριστικό βρεθεί· διαφορετικά, **false**. Εάν **false**, η θέση του αναγνώστη δεν αλλάζει.

## XmlNodeReader::MoveToAttribute(int32_t) μέθοδος

Μετακινείται στο χαρακτηριστικό με το καθορισμένο δείκτη.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| attributeIndex | **int32_t** | Ο δείκτης του χαρακτηριστικού. |

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlNodeReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)