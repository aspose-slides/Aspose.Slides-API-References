---
title: MoveToAttribute()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετακινείται στο χαρακτηριστικό με το καθορισμένο όνομα.
type: docs
weight: 508
url: /el/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) μέθοδος

Μετακινείται στο χαρακτηριστικό με το καθορισμένο όνομα.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το πλήρες όνομα του χαρακτηριστικού. |

### Return Value

**true** αν βρεθεί το χαρακτηριστικό· διαφορετικά, **false**. Αν **false**, η θέση του αναγνώστη δεν αλλάζει.

## XmlTextReader::MoveToAttribute(String, String) μέθοδος

Μετακινείται στο χαρακτηριστικό με το καθορισμένο τοπικό όνομα και URI χώρου ονομάτων.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του χαρακτηριστικού. |
| namespaceURI | [String](../../../system/string/) | Το URI του χώρου ονομάτων του χαρακτηριστικού. |

### Return Value

**true** αν βρεθεί το χαρακτηριστικό· διαφορετικά, **false**. Αν **false**, η θέση του αναγνώστη δεν αλλάζει.

## XmlTextReader::MoveToAttribute(int32_t) μέθοδος

Μετακινείται στο χαρακτηριστικό με τον καθορισμένο δείκτη.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| i | **int32_t** | Ο δείκτης του χαρακτηριστικού. |

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlTextReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)