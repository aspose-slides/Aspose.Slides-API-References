---
title: GetBuiltInSimpleType()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie un XmlSchemaSimpleType qui représente le type simple intégré du type simple spécifié par le nom qualifié.
type: docs
weight: 183
url: /fr/system.xml.schema/xmlschematype/getbuiltinsimpletype/
---
## XmlSchemaType::GetBuiltInSimpleType(const SharedPtr\<XmlQualifiedName\>\&) method

Renvoie un [XmlSchemaSimpleType](../../xmlschemasimpletype/) qui représente le type simple intégré du type simple spécifié par le nom qualifié.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | Le [XmlQualifiedName](../../../system.xml/xmlqualifiedname/) du type simple. |

### Return Value

Le [XmlSchemaSimpleType](../../xmlschemasimpletype/) qui représente le type simple intégré.

## XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode) method

Renvoie un [XmlSchemaSimpleType](../../xmlschemasimpletype/) qui représente le type simple intégré du type simple spécifié.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode typeCode)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | L’une des valeurs XmlTypeCode représentant le type simple. |

### Return Value

Le [XmlSchemaSimpleType](../../xmlschemasimpletype/) qui représente le type simple intégré.

## See Also

* Enum [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSimpleType](../../xmlschemasimpletype/)
* Class [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Class [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)