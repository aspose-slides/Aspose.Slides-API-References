---
title: XmlSchemaValidator()
second_title: Aspose.Slides voor C++ API-referentie
description: Initialiseert een nieuw exemplaar van de XmlSchemaValidator klasse.
type: docs
weight: 92
url: /nl/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) constructor

Initialiseert een nieuw exemplaar van de [XmlSchemaValidator](../) klasse.

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | Een [XmlNameTable](../../../system.xml/xmlnametable/) object dat element- en attribuutnamen bevat als geatomiseerde strings. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | Een [XmlSchemaSet](../../xmlschemaset/) object dat de XML [Schema](../../) Definitie Taal (XSD) schemata bevat die worden gebruikt voor validatie. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Een [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object dat wordt gebruikt voor het oplossen van naamruimtes die tijdens validatie worden tegengekomen. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | Een XmlSchemaValidationFlags waarde die de schema-validatie-opties specificeert. |

## Zie ook

* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNameTable](../../../system.xml/xmlnametable/)
* Klasse [XmlSchemaSet](../../xmlschemaset/)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klasse [XmlSchemaValidator](../)
* Naamruimte [System::Xml::Schema](../../)
* Bibliotheek [Aspose.Slides](../../../)