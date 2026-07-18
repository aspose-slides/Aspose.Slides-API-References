---
title: ValueAs()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει την τιμή του στοιχείου ως τον καθορισμένο τύπο.
type: docs
weight: 131
url: /el/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) μέθοδος


Επιστρέφει την τιμή του στοιχείου ως τον καθορισμένο τύπο.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Ο τύπος για τον οποίο θα επιστραφεί η τιμή του στοιχείου. |

### Τιμή Επιστροφής

Η τιμή του στοιχείου ως ο ζητούμενος τύπος.

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) μέθοδος


Όταν υπερκαλύπτεται σε μια κληρονομημένη κλάση, επιστρέφει την τιμή του στοιχείου ως τον τύπο που καθορίζεται χρησιμοποιώντας το αντικείμενο [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) για την επίλυση προθεμάτων ονοματοχώρου.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Ο τύπος για τον οποίο θα επιστραφεί η τιμή του στοιχείου. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Το αντικείμενο [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) που χρησιμοποιείται για την επίλυση προθεμάτων ονοματοχώρου. |

### Τιμή Επιστροφής

Η τιμή του στοιχείου ως ο ζητούμενος τύπος.

## Δείτε επίσης

* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [TypeInfo](../../../system/typeinfo/)
* Κλάση [XPathItem](../)
* Κλάση [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)