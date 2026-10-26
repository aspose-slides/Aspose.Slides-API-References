---
title: XmlSchemaValidator()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αρχικοποιεί μια νέα παρουσία της κλάσης XmlSchemaValidator.
type: docs
weight: 92
url: /el/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) constructor


Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlSchemaValidator](../).

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | Ένα αντικείμενο [XmlNameTable](../../../system.xml/xmlnametable/) που περιέχει ονόματα στοιχείων και χαρακτηριστικών ως ατομικοποιημένες συμβολοσειρές. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | Ένα αντικείμενο [XmlSchemaSet](../../xmlschemaset/) που περιέχει τα σχήματα XML [Schema](../../) Definition Language (XSD) που χρησιμοποιούνται για την επαλήθευση. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Ένα αντικείμενο [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) που χρησιμοποιείται για την επίλυση των χώρων ονομάτων που εντοπίζονται κατά την επαλήθευση. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | Μια τιμή XmlSchemaValidationFlags που καθορίζει τις επιλογές επαλήθευσης σχήματος. |

## Δείτε επίσης

* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../../system.xml/xmlnametable/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)