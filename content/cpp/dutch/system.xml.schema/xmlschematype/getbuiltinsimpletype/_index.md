---
title: GetBuiltInSimpleType()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een XmlSchemaSimpleType die het ingebouwde eenvoudige type van het eenvoudige type weergeeft dat gespecificeerd wordt door de gekwalificeerde naam.
type: docs
weight: 183
url: /nl/system.xml.schema/xmlschematype/getbuiltinsimpletype/
---
## XmlSchemaType::GetBuiltInSimpleType(const SharedPtr\<XmlQualifiedName\>\&) methode

Retourneert een [XmlSchemaSimpleType](../../xmlschemasimpletype/) die het ingebouwde eenvoudige type van het eenvoudige type weergeeft dat gespecificeerd wordt door de gekwalificeerde naam.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | De [XmlQualifiedName](../../../system.xml/xmlqualifiedname/) van het eenvoudige type. |

### Retourwaarde

De [XmlSchemaSimpleType](../../xmlschemasimpletype/) die het ingebouwde eenvoudige type weergeeft.

## XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode) methode

Retourneert een [XmlSchemaSimpleType](../../xmlschemasimpletype/) die het ingebouwde eenvoudige type van het opgegeven eenvoudige type weergeeft.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode typeCode)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | Een van de XmlTypeCode-waarden die het eenvoudige type vertegenwoordigen. |

### Retourwaarde

De [XmlSchemaSimpleType](../../xmlschemasimpletype/) die het ingebouwde eenvoudige type weergeeft.

## Zie ook

* Enum [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchemaSimpleType](../../xmlschemasimpletype/)
* Klasse [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Klasse [XmlSchemaType](../)
* Naamruimte [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)