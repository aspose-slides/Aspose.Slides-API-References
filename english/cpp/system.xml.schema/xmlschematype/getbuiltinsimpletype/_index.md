---
title: GetBuiltInSimpleType()
second_title: Aspose.Slides for C++ API Reference
description: Returns an XmlSchemaSimpleType that represents the built-in simple type of the simple type that is specified by the qualified name.
type: docs
weight: 183
url: /cpp/system.xml.schema/xmlschematype/getbuiltinsimpletype/
---
## XmlSchemaType::GetBuiltInSimpleType(const SharedPtr\<XmlQualifiedName\>\&) method


Returns an [XmlSchemaSimpleType](../../xmlschemasimpletype/) that represents the built-in simple type of the simple type that is specified by the qualified name.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | The [XmlQualifiedName](../../../system.xml/xmlqualifiedname/) of the simple type. |

### Return Value

The [XmlSchemaSimpleType](../../xmlschemasimpletype/) that represents the built-in simple type.

## XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode) method


Returns an [XmlSchemaSimpleType](../../xmlschemasimpletype/) that represents the built-in simple type of the specified simple type.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode typeCode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | One of the XmlTypeCode values representing the simple type. |

### Return Value

The [XmlSchemaSimpleType](../../xmlschemasimpletype/) that represents the built-in simple type.

## See Also

* Enum [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSimpleType](../../xmlschemasimpletype/)
* Class [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Class [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)