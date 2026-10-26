---
title: GetBuiltInSimpleType()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个 XmlSchemaSimpleType，表示由限定名称指定的简单类型的内置简单类型。
type: docs
weight: 183
url: /zh/system.xml.schema/xmlschematype/getbuiltinsimpletype/
---
## XmlSchemaType::GetBuiltInSimpleType(const SharedPtr\<XmlQualifiedName\>\&) 方法

返回一个 [XmlSchemaSimpleType](../../xmlschemasimpletype/)，它表示由限定名称指定的简单类型的内置简单类型。

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | 简单类型的 [XmlQualifiedName](../../../system.xml/xmlqualifiedname/) |

### 返回值

表示内置简单类型的 [XmlSchemaSimpleType](../../xmlschemasimpletype/)。

## XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode) 方法

返回一个 [XmlSchemaSimpleType](../../xmlschemasimpletype/)，它表示指定的简单类型的内置简单类型。

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode typeCode)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | 表示该简单类型的 XmlTypeCode 值之一。 |

### 返回值

表示内置简单类型的 [XmlSchemaSimpleType](../../xmlschemasimpletype/)。

## 另见

* Enum [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSimpleType](../../xmlschemasimpletype/)
* Class [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Class [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)