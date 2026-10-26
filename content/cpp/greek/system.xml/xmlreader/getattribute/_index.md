---
title: GetAttribute()
second_title: Aspose.Slides για το C++ API Αναφορά
description: "Όταν αντικαθίσταται σε παράγωγη κλάση, λαμβάνει την τιμή του χαρακτηριστικού με την καθορισμένη τιμή XmlReader::get_Name."
type: docs
weight: 599
url: /el/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) μέθοδος

Όταν αντικαθίσταται σε παράγωγη κλάση, λαμβάνει την τιμή του χαρακτηριστικού με την καθορισμένη τιμή [XmlReader::get_Name](../get_name/).

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το πλήρες όνομα του χαρακτηριστικού. |

### Τιμή Επιστροφής

Η τιμή του καθορισμένου χαρακτηριστικού. Αν το χαρακτηριστικό δεν βρεθεί ή η τιμή είναι [String::Empty](../../../system/string/empty/), **nullptr** επιστρέφεται.

## XmlReader::GetAttribute(String, String) μέθοδος

Όταν αντικαθίσταται σε παράγωγη κλάση, λαμβάνει την τιμή του χαρακτηριστικού με τις καθορισμένες τιμές [XmlReader::get_LocalName](../get_localname/) και [XmlReader::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το τοπικό όνομα του χαρακτηριστικού. |
| namespaceURI | [String](../../../system/string/) | Το URI του χώρου ονομάτων του χαρακτηριστικού. |

### Τιμή Επιστροφής

Η τιμή του καθορισμένου χαρακτηριστικού. Αν το χαρακτηριστικό δεν βρεθεί ή η τιμή είναι [String::Empty](../../../system/string/empty/), **nullptr** επιστρέφεται. Αυτή η μέθοδος δεν μετακινεί τον αναγνώστη.

## XmlReader::GetAttribute(int32_t) μέθοδος

Όταν αντικαθίσταται σε παράγωγη κλάση, λαμβάνει την τιμή του χαρακτηριστικού με τον καθορισμένο δείκτη.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| i | **int32_t** | Ο δείκτης του χαρακτηριστικού. Ο δείκτης μετράται από το μηδέν. (Το πρώτο χαρακτηριστικό έχει δείκτη 0.) |

### Τιμή Επιστροφής

Η τιμή του καθορισμένου χαρακτηριστικού. Αυτή η μέθοδος δεν μετακινεί τον αναγνώστη.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)