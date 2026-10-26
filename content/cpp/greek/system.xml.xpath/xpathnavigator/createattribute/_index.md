---
title: CreateAttribute()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Δημιουργεί έναν κόμβο χαρακτηριστικού στον τρέχοντα κόμβο στοιχείου χρησιμοποιώντας το πρόθεμα του χώρου ονομάτων, το τοπικό όνομα και το URI του χώρου ονομάτων που καθορίζονται, μαζί με την καθορισμένη τιμή."
type: docs
weight: 1041
url: /el/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) μέθοδος


Δημιουργεί έναν κόμβο χαρακτηριστικού στον τρέχοντα κόμβο στοιχείου χρησιμοποιώντας το πρόθεμα χώρου ονομάτων, το τοπικό όνομα και το URI του χώρου ονομάτων που καθορίζονται, μαζί με την καθορισμένη τιμή.

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Το πρόθεμα χώρου ονομάτων του νέου κόμβου χαρακτηριστικού (εάν υπάρχει). |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του νέου κόμβου χαρακτηριστικού που δεν μπορεί να [String::Empty](../../../system/string/empty/) ή **nullptr**. |
| namespaceURI | [String](../../../system/string/) | Το URI του χώρου ονομάτων για τον νέο κόμβο χαρακτηριστικού (εάν υπάρχει). |
| value | [String](../../../system/string/) | Η τιμή του νέου κόμβου χαρακτηριστικού. Εάν [String::Empty](../../../system/string/empty/) ή **nullptr** περαστούν, δημιουργείται ένας κενός κόμβος χαρακτηριστικού. |

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XPathNavigator](../)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)