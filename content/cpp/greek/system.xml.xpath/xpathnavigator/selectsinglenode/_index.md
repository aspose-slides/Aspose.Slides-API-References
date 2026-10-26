---
title: SelectSingleNode()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιλέγει έναν μοναδικό κόμβο στον XPathNavigator χρησιμοποιώντας το καθορισμένο ερώτημα XPath.
type: docs
weight: 781
url: /el/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) μέθοδος

Επιλέγει έναν μοναδικό κόμβο στο [XPathNavigator](../) χρησιμοποιώντας το καθορισμένο ερώτημα [XPath](../../).

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Ένα [String](../../../system/string/) που αντιπροσωπεύει μια [XPath](../../) έκφραση. |

### Τιμή Επιστροφής

Ένα αντικείμενο [XPathNavigator](../) που περιέχει τον πρώτο αντίστοιχο κόμβο για το καθορισμένο ερώτημα [XPath](../../)· διαφορετικά, **nullptr** εάν δεν υπάρχουν αποτελέσματα ερωτήματος.

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) μέθοδος

Επιλέγει έναν μοναδικό κόμβο στο αντικείμενο [XPathNavigator](../) χρησιμοποιώντας το καθορισμένο ερώτημα [XPath](../../) με το αντικείμενο [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) που καθορίζεται για την επίλυση προθεμάτων χώρου ονομάτων.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Ένα [String](../../../system/string/) που αντιπροσωπεύει μια [XPath](../../) έκφραση. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Το αντικείμενο [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) που χρησιμοποιείται για την επίλυση προθεμάτων χώρου ονομάτων στο ερώτημα [XPath](../../). |

### Τιμή Επιστροφής

Ένα αντικείμενο [XPathNavigator](../) που περιέχει τον πρώτο αντίστοιχο κόμβο για το καθορισμένο ερώτημα [XPath](../../)· διαφορετικά, **nullptr** εάν δεν υπάρχουν αποτελέσματα ερωτήματος.

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) μέθοδος

Επιλέγει έναν μοναδικό κόμβο στο [XPathNavigator](../) χρησιμοποιώντας το καθορισμένο αντικείμενο [XPathExpression](../../xpathexpression/).

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Ένα [XPathExpression](../../xpathexpression/) αντικείμενο που περιέχει το μεταγλωττισμένο ερώτημα [XPath](../../). |

### Τιμή Επιστροφής

Ένα αντικείμενο [XPathNavigator](../) που περιέχει τον πρώτο αντίστοιχο κόμβο για το καθορισμένο ερώτημα [XPath](../../)· διαφορετικά, **nullptr** εάν δεν υπάρχουν αποτελέσματα ερωτήματος.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../../xpathexpression/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)