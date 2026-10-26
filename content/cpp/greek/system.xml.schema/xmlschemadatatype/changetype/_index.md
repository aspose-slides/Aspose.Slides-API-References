---
title: ChangeType()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει την καθορισμένη τιμή, της οποίας ο τύπος είναι μία από τις έγκυρες αναπαραστάσεις του τύπου σχήματος XML που αναπαρίσταται από το XmlSchemaDatatype, στον καθορισμένο τύπο χρόνου εκτέλεσης.
type: docs
weight: 66
url: /el/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) μέθοδος

Μετατρέπει την καθορισμένη τιμή, της οποίας ο τύπος είναι μία από τις έγκυρες αναπαραστάσεις του τύπου σχήματος XML που αναπαρίσταται από το [XmlSchemaDatatype](../), στον καθορισμένο τύπο χρόνου εκτέλεσης.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Η τιμή εισόδου που θα μετατραπεί στον καθορισμένο τύπο. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Ο τύπος-στόχος στον οποίο θα μετατραπεί η τιμή εισόδου. |

### Τιμή Επιστροφής

Η μετατρεπόμενη τιμή εισόδου.

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) μέθοδος

Μετατρέπει την καθορισμένη τιμή, της οποίας ο τύπος είναι μία από τις έγκυρες αναπαραστάσεις του τύπου σχήματος XML που αναπαρίσταται από το [XmlSchemaDatatype](../), στον καθορισμένο τύπο χρόνου εκτέλεσης χρησιμοποιώντας το [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) εφόσον το [XmlSchemaDatatype](../) αντιπροσωπεύει τον τύπο **xs:QName** ή έναν τύπο που προέρχεται από αυτόν.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Η τιμή εισόδου που θα μετατραπεί στον καθορισμένο τύπο. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Ο τύπος-στόχος στον οποίο θα μετατραπεί η τιμή εισόδου. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Ένα [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) που χρησιμοποιείται για την επίλυση προθεμάτων χώρου ονομασίας. Αυτό είναι χρήσιμο μόνο εάν το [XmlSchemaDatatype](../) αντιπροσωπεύει τον τύπο **xs:QName** ή έναν τύπο που προέρχεται από αυτόν. |

### Τιμή Επιστροφής

Η μετατρεπόμενη τιμή εισόδου.

## Δείτε επίσης

* typedef [SharedPtr](../../../system/sharedptr/)
* κλάση [Object](../../../system/object/)
* κλάση [TypeInfo](../../../system/typeinfo/)
* κλάση [XmlSchemaDatatype](../)
* κλάση [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* χώρος ονομασίας [System::Xml::Schema](../../)
* βιβλιοθήκη [Aspose.Slides](../../../)