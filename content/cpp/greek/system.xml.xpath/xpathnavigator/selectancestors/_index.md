---
title: SelectAncestors()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιλέγει όλους τους γονικούς κόμβους του τρέχοντος κόμβου που έχουν έναν αντίστοιχο XPathNodeType.
type: docs
weight: 846
url: /el/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) method


Επιλέγει όλους τους γονικούς κόμβους του τρέχοντος κόμβου που έχουν έναν αντίστοιχο XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Ο XPathNodeType των γονικών κόμβων. |
| matchSelf | **bool** | Για να συμπεριλάβετε τον κόμβο συμφραζομένων στην επιλογή, **true**· διαφορετικά, **false**. |

### Return Value

Ένα [XPathNodeIterator](../../xpathnodeiterator/) που περιέχει τους επιλεγμένους κόμβους. Οι επιστρεφόμενοι κόμβοι είναι με αντίστροφη σειρά εγγράφου.

## XPathNavigator::SelectAncestors(String, String, bool) method


Επιλέγει όλους τους γονικούς κόμβους του τρέχοντος κόμβου που έχουν το καθορισμένο τοπικό όνομα και το URI του χώρου ονομάτων.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το τοπικό όνομα των γονικών κόμβων. |
| namespaceURI | [String](../../../system/string/) | Το URI του χώρου ονομάτων των γονικών κόμβων. |
| matchSelf | **bool** | Για να συμπεριλάβετε τον κόμβο συμφραζομένων στην επιλογή, **true**· διαφορετικά, **false**. |

### Return Value

Ένα [XPathNodeIterator](../../xpathnodeiterator/) που περιέχει τους επιλεγμένους κόμβους. Οι επιστρεφόμενοι κόμβοι είναι με αντίστροφη σειρά εγγράφου.

## See Also

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)