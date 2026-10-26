---
title: ValueAs()
second_title: Aspose.Slides για C++ API Reference
description: Επιστρέφει την τιμή του τρέχοντος κόμβου ως ο Type που καθορίζεται, χρησιμοποιώντας το αντικείμενο IXmlNamespaceResolver που έχει καθοριστεί για την επίλυση προθεμάτων χώρων ονομάτων.
type: docs
weight: 378
url: /el/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) μέθοδος

Επιστρέφει την τιμή του τρέχοντος κόμβου ως ο Type που καθορίζεται, χρησιμοποιώντας το αντικείμενο [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) που έχει οριστεί για την επίλυση προθεμάτων χώρων ονομάτων.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Ο Type για την επιστροφή της τιμής του τρέχοντος κόμβου. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Το αντικείμενο [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) που χρησιμοποιείται για την επίλυση προθεμάτων χώρων ονομάτων. |

### Τιμή Επιστροφής

Η τιμή του τρέχοντος κόμβου ως ο Type που ζητήθηκε.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)