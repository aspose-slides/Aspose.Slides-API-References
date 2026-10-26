---
title: ValueAs()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιστρέφει την επικυρωμένη τιμή του στοιχείου ή του χαρακτηριστικού XML ως τον τύπο που καθορίζεται χρησιμοποιώντας το αντικείμενο IXmlNamespaceResolver που έχει οριστεί για την επίλυση προθεμάτων ονοματοχώρου.
type: docs
weight: 144
url: /el/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method

Επιστρέφει την επικυρωμένη τιμή του στοιχείου ή του χαρακτηριστικού XML ως τον τύπο που καθορίζεται χρησιμοποιώντας το αντικείμενο [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) που έχει οριστεί για την επίλυση προθεμάτων ονοματοχώρου.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Ο τύπος ως τον οποίο θα επιστραφεί η επικυρωμένη τιμή του στοιχείου ή του χαρακτηριστικού XML. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Το αντικείμενο [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) που χρησιμοποιείται για την επίλυση προθεμάτων ονοματοχώρου. |

### Τιμή Επιστροφής

Η τιμή του επικυρωμένου στοιχείου ή χαρακτηριστικού XML ως ο ζητούμενος τύπος.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlAtomicValue](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)