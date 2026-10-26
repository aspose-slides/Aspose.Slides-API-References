---
title: GetBuiltInComplexType()
second_title: Aspose.Slides for C++ API 參考
description: 傳回一個 XmlSchemaComplexType，表示指定之複合類型的內建複合類型。
type: docs
weight: 196
url: /zh-hant/system.xml.schema/xmlschematype/getbuiltincomplextype/
---
## XmlSchemaType::GetBuiltInComplexType(XmlTypeCode) 方法

傳回一個 [XmlSchemaComplexType](../../xmlschemacomplextype/)，表示指定之複合類型的內建複合類型。

```cpp
static SharedPtr<XmlSchemaComplexType> System::Xml::Schema::XmlSchemaType::GetBuiltInComplexType(XmlTypeCode typeCode)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | 表示該複合類型的 XmlTypeCode 值之一。 |

### 傳回值

表示內建複合類型的 [XmlSchemaComplexType](../../xmlschemacomplextype/)。

## XmlSchemaType::GetBuiltInComplexType(const SharedPtr\<XmlQualifiedName\>\&) 方法

傳回一個 [XmlSchemaComplexType](../../xmlschemacomplextype/)，表示依限定名稱指定之複合類型的內建複合類型。

```cpp
static SharedPtr<XmlSchemaComplexType> System::Xml::Schema::XmlSchemaType::GetBuiltInComplexType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | 複合類型的 [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)。 |

### 傳回值

表示內建複合類型的 [XmlSchemaComplexType](../../xmlschemacomplextype/)。

## 另請參見

* Enum [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaComplexType](../../xmlschemacomplextype/)
* Class [XmlSchemaType](../)
* Class [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)