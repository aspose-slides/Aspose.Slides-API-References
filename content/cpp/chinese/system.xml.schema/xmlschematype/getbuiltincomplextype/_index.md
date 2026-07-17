---
title: GetBuiltInComplexType()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个 XmlSchemaComplexType，它表示指定的复杂类型的内置复杂类型。
type: docs
weight: 196
url: /zh/system.xml.schema/xmlschematype/getbuiltincomplextype/
---
## XmlSchemaType::GetBuiltInComplexType(XmlTypeCode) 方法

返回一个[XmlSchemaComplexType](../../xmlschemacomplextype/)，它表示指定的复杂类型的内置复杂类型。

```cpp
static SharedPtr<XmlSchemaComplexType> System::Xml::Schema::XmlSchemaType::GetBuiltInComplexType(XmlTypeCode typeCode)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | 表示该复杂类型的 XmlTypeCode 值之一。 |

### 返回值

返回[XmlSchemaComplexType](../../xmlschemacomplextype/)，它表示内置复杂类型。

## XmlSchemaType::GetBuiltInComplexType(const SharedPtr\<XmlQualifiedName\>\&) 方法

返回一个[XmlSchemaComplexType](../../xmlschemacomplextype/)，它表示由限定名称指定的复杂类型的内置复杂类型。

```cpp
static SharedPtr<XmlSchemaComplexType> System::Xml::Schema::XmlSchemaType::GetBuiltInComplexType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | 复杂类型的[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)。 |

### 返回值

返回[XmlSchemaComplexType](../../xmlschemacomplextype/)，它表示内置复杂类型。

## 参见

* Enum [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaComplexType](../../xmlschemacomplextype/)
* Class [XmlSchemaType](../)
* Class [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)