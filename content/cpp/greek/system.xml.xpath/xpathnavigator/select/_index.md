---
title: Select()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιλέγει ένα σύνολο κόμβων, χρησιμοποιώντας την καθορισμένη έκφραση XPath.
type: docs
weight: 794
url: /el/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) μέθοδος

Επιλέγει ένα σύνολο κόμβων, χρησιμοποιώντας την καθορισμένη [XPath](../../) έκφραση.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Μία [String](../../../system/string/) που αντιπροσωπεύει μια [XPath](../../) έκφραση. |

### Τιμή επιστροφής

Ένα [XPathNodeIterator](../../xpathnodeiterator/) που δείχνει στο επιλεγμένο σύνολο κόμβων.

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) μέθοδος

Επιλέγει ένα σύνολο κόμβων χρησιμοποιώντας την καθορισμένη [XPath](../../) έκφραση με το αντικείμενο [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) που καθορίζεται για την επίλυση προθεμάτων ονοματοχώρων.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Μία [String](../../../system/string/) που αντιπροσωπεύει μια [XPath](../../) έκφραση. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Το αντικείμενο [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) που χρησιμοποιείται για την επίλυση προθεμάτων ονοματοχώρων. |

### Τιμή επιστροφής

Ένα [XPathNodeIterator](../../xpathnodeiterator/) που δείχνει στο επιλεγμένο σύνολο κόμβων.

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) μέθοδος

Επιλέγει ένα σύνολο κόμβων χρησιμοποιώντας την καθορισμένη [XPathExpression](../../xpathexpression/).

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Ένα [XPathExpression](../../xpathexpression/) αντικείμενο που περιέχει το μεταγλωτισμένο [XPath](../../) ερώτημα. |

### Τιμή επιστροφής

Ένα [XPathNodeIterator](../../xpathnodeiterator/) που δείχνει στο επιλεγμένο σύνολο κόμβων.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XPathNodeIterator](../../xpathnodeiterator/)
* Κλάση [String](../../../system/string/)
* Κλάση [XPathNavigator](../)
* Κλάση [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Κλάση [XPathExpression](../../xpathexpression/)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)