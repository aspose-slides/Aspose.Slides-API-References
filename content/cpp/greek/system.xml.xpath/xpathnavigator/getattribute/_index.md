---
title: GetAttribute()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιστρέφει την τιμή του χαρακτηριστικού με το συγκεκριμένο τοπικό όνομα και URI ονόματος χώρου.
type: docs
weight: 482
url: /el/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) μέθοδος

Επιστρέφει την τιμή του χαρακτηριστικού με το συγκεκριμένο τοπικό όνομα και URI ονόματος χώρου.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του χαρακτηριστικού. **localName** είναι ευαίσθητο σε πεζά/κεφαλαία. |
| namespaceURI | [String](../../../system/string/) | Το URI ονόματος χώρου του χαρακτηριστικού. |

### Τιμή επιστροφής

Ένα [String](../../../system/string/) που περιέχει την τιμή του συγκεκριμένου χαρακτηριστικού· [String::Empty](../../../system/string/empty/) εάν δεν βρεθεί αντιστοιχικό χαρακτηριστικό ή εάν το [XPathNavigator](../) δεν βρίσκεται σε κόμβο στοιχείου.

## Δείτε επίσης

* Τάξη [String](../../../system/string/)
* Τάξη [XPathNavigator](../)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)