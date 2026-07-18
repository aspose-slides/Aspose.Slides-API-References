---
title: MoveToAttribute()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Όταν παρακαμφθεί σε μια παράγωγη κλάση, μετακινείται στο γνωριστικό με την καθορισμένη τιμή XmlReader::get_Name."
type: docs
weight: 625
url: /el/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) μέθοδος


Όταν παρακαμφθεί σε μια παράγωγη κλάση, μετακινείται στο γνωριστικό με την καθορισμένη τιμή [XmlReader::get_Name](../get_name/).

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το πλήρες όνομα του γνωριστικού. |

### Τιμή Επιστροφής

**true** εάν το γνωριστικό βρεθεί· διαφορετικά, **false**. Εάν **false**, η θέση του αναγνώστη δεν αλλάζει.

## XmlReader::MoveToAttribute(String, String) μέθοδος


Όταν παρακαμφθεί σε μια παράγωγη κλάση, μετακινείται στο γνωριστικό με τις καθορισμένες τιμές [XmlReader::get_LocalName](../get_localname/) και [XmlReader::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το τοπικό όνομα του γνωριστικού. |
| ns | [String](../../../system/string/) | Το URI του χώρου ονομάτων του γνωριστικού. |

### Τιμή Επιστροφής

**true** εάν το γνωριστικό βρεθεί· διαφορετικά, **false**. Εάν **false**, η θέση του αναγνώστη δεν αλλάζει.

## XmlReader::MoveToAttribute(int32_t) μέθοδος


Όταν παρακαμφθεί σε μια παράγωγη κλάση, μετακινείται στο γνωριστικό με τον καθορισμένο δείκτη.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| i | **int32_t** | Ο δείκτης του γνωριστικού. |

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)