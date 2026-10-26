---
title: ReadToFollowing()
second_title: Aspose.Slides για C++ Αναφορά API
description: Διαβάζει μέχρι να βρεθεί ένα στοιχείο με το καθορισμένο πλήρες όνομα.
type: docs
weight: 898
url: /el/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) μέθοδος

Διαβάζει μέχρι να βρεθεί ένα στοιχείο με το καθορισμένο πλήρες όνομα.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το πλήρες όνομα του στοιχείου. |

### Τιμή Επιστροφής

**true** εάν βρεθεί ένα αντιστοιχισμένο στοιχείο· διαφορετικά **false** και το [XmlReader](../) βρίσκεται σε κατάσταση τέλους αρχείου.

## XmlReader::ReadToFollowing(String, String) μέθοδος

Διαβάζει μέχρι να βρεθεί ένα στοιχείο με το καθορισμένο τοπικό όνομα και το URI του χώρου ονομάτων.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του στοιχείου. |
| namespaceURI | [String](../../../system/string/) | Το URI του χώρου ονομάτων του στοιχείου. |

### Τιμή Επιστροφής

**true** εάν βρεθεί ένα αντιστοιχισμένο στοιχείο· διαφορετικά **false** και το [XmlReader](../) βρίσκεται σε κατάσταση τέλους αρχείου.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)