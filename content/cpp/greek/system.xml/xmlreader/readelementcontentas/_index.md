---
title: ReadElementContentAs()
second_title: Aspose.Slides για C++ Αναφορά API
description: Διαβάζει το περιεχόμενο του στοιχείου ως τον ζητούμενο τύπο.
type: docs
weight: 586
url: /el/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) μέθοδος

Διαβάζει το περιεχόμενο του στοιχείου ως τον ζητούμενο τύπο.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Ο τύπος της τιμής που θα επιστραφεί. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Ένα αντικείμενο [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) που χρησιμοποιείται για την επίλυση τυχόν πρόθεμα χώρου ονομάτων που σχετίζονται με τη μετατροπή τύπου. |

### Τιμή Επιστροφής

Το περιεχόμενο του στοιχείου μετατρεπόμενο στο ζητούμενο αντικείμενο τύπου.

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) μέθοδος

Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI του χώρου ονομάτων ταιριάζουν με αυτά του τρέχοντος στοιχείου, στη συνέχεια διαβάζει το περιεχόμενο του στοιχείου ως τον ζητούμενο τύπο.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Ο τύπος της τιμής που θα επιστραφεί. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Ένα αντικείμενο [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) που χρησιμοποιείται για την επίλυση τυχόν πρόθεμα χώρου ονομάτων που σχετίζονται με τη μετατροπή τύπου. |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του στοιχείου. |
| namespaceURI | [String](../../../system/string/) | Το URI του χώρου ονομάτων του στοιχείου. |

### Τιμή Επιστροφής

Το περιεχόμενο του στοιχείου μετατρεπόμενο στο ζητούμενο αντικείμενο τύπου.

## Δείτε Επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [TypeInfo](../../../system/typeinfo/)
* Κλάση [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Κλάση [XmlReader](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)