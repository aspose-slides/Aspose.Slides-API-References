---
title: SelectDescendants()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιλέγει όλους τους κόμβους-απόγονους του τρέχοντος κόμβου που έχουν έναν αντιστοιχούντα XPathNodeType.
type: docs
weight: 859
url: /el/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) μέθοδος


Επιλέγει όλους τους κόμβους-απόγονους του τρέχοντος κόμβου που έχουν έναν αντιστοιχούντα XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Το XPathNodeType των κόμβων-απόγονων. |
| matchSelf | **bool** | **true** για να συμπεριληφθεί ο κόμβος περιβάλλοντος στην επιλογή· διαφορετικά, **false**. |

### Return Value

Ένα [XPathNodeIterator](../../xpathnodeiterator/) που περιέχει τους επιλεγμένους κόμβους.

## XPathNavigator::SelectDescendants(String, String, bool) μέθοδος


Επιλέγει όλους τους κόμβους-απόγονους του τρέχοντος κόμβου με το τοπικό όνομα και το namespace URI που έχουν καθοριστεί.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το τοπικό όνομα των κόμβων-απόγονων. |
| namespaceURI | [String](../../../system/string/) | Το namespace URI των κόμβων-απόγονων. |
| matchSelf | **bool** | **true** για να συμπεριληφθεί ο κόμβος περιβάλλοντος στην επιλογή· διαφορετικά, **false**. |

### Return Value

Ένα [XPathNodeIterator](../../xpathnodeiterator/) που περιέχει τους επιλεγμένους κόμβους.

## Δείτε επίσης

* Απαρίθμηση [XPathNodeType](../../xpathnodetype/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [XPathNodeIterator](../../xpathnodeiterator/)
* Κλάση [XPathNavigator](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)