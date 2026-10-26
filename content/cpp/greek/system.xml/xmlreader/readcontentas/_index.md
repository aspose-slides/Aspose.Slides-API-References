---
title: ReadContentAs()
second_title: Αναφορά API του Aspose.Slides για C++
description: Διαβάζει το περιεχόμενο ως αντικείμενο του καθορισμένου τύπου.
type: docs
weight: 456
url: /el/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) μέθοδος

Διαβάζει το περιεχόμενο ως αντικείμενο του καθορισμένου τύπου.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Ο τύπος της τιμής που θα επιστραφεί. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Ένα αντικείμενο [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) που χρησιμοποιείται για την επίλυση τυχόν προθέματος χώρου ονομάτων σχετικών με τη μετατροπή τύπου. Για παράδειγμα, αυτό μπορεί να χρησιμοποιηθεί κατά τη μετατροπή ενός αντικειμένου [XmlQualifiedName](../../xmlqualifiedname/) σε **xs:string**. Αυτή η τιμή μπορεί να είναι **nullptr**. |

### Τιμή Επιστροφής

Το συνενωμένο κείμενο ή η τιμή ιδιότητας που μετατράπηκε στον ζητούμενο τύπο.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [TypeInfo](../../../system/typeinfo/)
* Κλάση [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Κλάση [XmlReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)