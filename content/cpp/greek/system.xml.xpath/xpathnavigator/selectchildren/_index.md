---
title: SelectChildren()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιλέγει όλους τους κόμβους-παιδιά του τρέχοντος κόμβου που έχουν το αντίστοιχο XPathNodeType.
type: docs
weight: 833
url: /el/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) μέθοδος

Επιλέγει όλους τους κόμβους-παιδιά του τρέχοντος κόμβου που έχουν τον αντίστοιχο XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Ο XPathNodeType των κόμβων-παιδιών. |

### Τιμή Επιστροφής

Ένα [XPathNodeIterator](../../xpathnodeiterator/) που περιέχει τους επιλεγμένους κόμβους.

## XPathNavigator::SelectChildren(String, String) μέθοδος

Επιλέγει όλους τους κόμβους-παιδιά του τρέχοντος κόμβου που έχουν το τοπικό όνομα και το URI του ονόματος χώρου που καθορίζονται.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το τοπικό όνομα των κόμβων-παιδιών. |
| namespaceURI | [String](../../../system/string/) | Το URI του ονόματος χώρου των κόμβων-παιδιών. |

### Τιμή Επιστροφής

Ένα [XPathNodeIterator](../../xpathnodeiterator/) που περιέχει τους επιλεγμένους κόμβους.

## Δείτε επίσης

* Απαρίθμηση [XPathNodeType](../../xpathnodetype/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [XPathNodeIterator](../../xpathnodeiterator/)
* Κλάση [XPathNavigator](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)