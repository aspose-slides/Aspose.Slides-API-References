---
title: Evaluate()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αξιολογεί την καθορισμένη έκφραση XPath και επιστρέφει το τυποποιημένο αποτέλεσμα.
type: docs
weight: 807
url: /el/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) μέθοδος

Αξιολογεί την καθορισμένη [XPath](../../) έκφραση και επιστρέφει το τυποποιημένο αποτέλεσμα.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Μια συμβολοσειρά που αντιπροσωπεύει μια [XPath](../../) έκφραση που μπορεί να αξιολογηθεί. |

### Τιμή Επιστροφής

Το αποτέλεσμα της έκφρασης ([Boolean](../../../system/boolean/), αριθμός, συμβολοσειρά ή σύνολο κόμβων). Αυτό αντιστοιχεί στα αντικείμενα [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) ή [XPathNodeIterator](../../xpathnodeiterator/) αντίστοιχα.

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) μέθοδος

Αξιολογεί την καθορισμένη [XPath](../../) έκφραση και επιστρέφει το τυποποιημένο αποτέλεσμα, χρησιμοποιώντας το αντικείμενο [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) που καθορίζεται για την επίλυση των προθεμάτων χώρου ονομάτων στην έκφραση [XPath](../../).

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Μια συμβολοσειρά που αντιπροσωπεύει μια [XPath](../../) έκφραση που μπορεί να αξιολογηθεί. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Το αντικείμενο [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) που χρησιμοποιείται για την επίλυση προθεμάτων χώρου ονομάτων στην έκφραση [XPath](../../). |

### Τιμή Επιστροφής

Το αποτέλεσμα της έκφρασης ([Boolean](../../../system/boolean/), αριθμός, συμβολοσειρά ή σύνολο κόμβων). Αυτό αντιστοιχεί στα αντικείμενα [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) ή [XPathNodeIterator](../../xpathnodeiterator/) αντίστοιχα.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) μέθοδος

Αξιολογεί το [XPathExpression](../../xpathexpression/) και επιστρέφει το τυποποιημένο αποτέλεσμα.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Ένα [XPathExpression](../../xpathexpression/) που μπορεί να αξιολογηθεί. |

### Τιμή Επιστροφής

Το αποτέλεσμα της έκφρασης ([Boolean](../../../system/boolean/), αριθμός, συμβολοσειρά ή σύνολο κόμβων). Αυτό αντιστοιχεί στα αντικείμενα [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) ή [XPathNodeIterator](../../xpathnodeiterator/) αντίστοιχα.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) μέθοδος

Χρησιμοποιεί το παρεχόμενο συμφραζόμενο για την αξιολόγηση του [XPathExpression](../../xpathexpression/) και επιστρέφει το τυποποιημένο αποτέλεσμα.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Ένα [XPathExpression](../../xpathexpression/) που μπορεί να αξιολογηθεί. |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | Ένα [XPathNodeIterator](../../xpathnodeiterator/) που δείχνει στο επιλεγμένο σύνολο κόμβων πάνω στο οποίο θα εκτελεστεί η αξιολόγηση. |

### Τιμή Επιστροφής

Το αποτέλεσμα της έκφρασης ([Boolean](../../../system/boolean/), αριθμός, συμβολοσειρά ή σύνολο κόμβων). Αυτό αντιστοιχεί στα αντικείμενα [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) ή [XPathNodeIterator](../../xpathnodeiterator/) αντίστοιχα.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [String](../../../system/string/)
* Κλάση [XPathNavigator](../)
* Κλάση [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Κλάση [XPathExpression](../../xpathexpression/)
* Κλάση [XPathNodeIterator](../../xpathnodeiterator/)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)