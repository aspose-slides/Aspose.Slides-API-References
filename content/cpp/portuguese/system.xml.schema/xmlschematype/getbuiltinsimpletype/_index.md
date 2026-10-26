---
title: GetBuiltInSimpleType()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um XmlSchemaSimpleType que representa o tipo simples interno do tipo simples especificado pelo nome qualificado.
type: docs
weight: 183
url: /pt/system.xml.schema/xmlschematype/getbuiltinsimpletype/
---
## XmlSchemaType::GetBuiltInSimpleType(const SharedPtr\<XmlQualifiedName\>\&) método

Retorna um [XmlSchemaSimpleType](../../xmlschemasimpletype/) que representa o tipo simples interno do tipo simples especificado pelo nome qualificado.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | O [XmlQualifiedName](../../../system.xml/xmlqualifiedname/) do tipo simples. |

### Valor de Retorno

O [XmlSchemaSimpleType](../../xmlschemasimpletype/) que representa o tipo simples interno.

## XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode) método

Retorna um [XmlSchemaSimpleType](../../xmlschemasimpletype/) que representa o tipo simples interno do tipo simples especificado.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode typeCode)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | Um dos valores de XmlTypeCode que representam o tipo simples. |

### Valor de Retorno

O [XmlSchemaSimpleType](../../xmlschemasimpletype/) que representa o tipo simples interno.

## Veja Também

* Enum [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchemaSimpleType](../../xmlschemasimpletype/)
* Classe [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Classe [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)