---
title: GetBuiltInSimpleType()
second_title: Aspose.Slides for C++ API Referansı
description: Nitelikli ad ile belirtilen basit türün yerleşik basit türünü temsil eden bir XmlSchemaSimpleType döndürür.
type: docs
weight: 183
url: /tr/system.xml.schema/xmlschematype/getbuiltinsimpletype/
---
## XmlSchemaType::GetBuiltInSimpleType(const SharedPtr\<XmlQualifiedName\>\&) metodu

Nitelikli ad tarafından belirtilen basit türün yerleşik basit türünü temsil eden bir [XmlSchemaSimpleType](../../xmlschemasimpletype/) döndürür.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | Basit türün [XmlQualifiedName](../../../system.xml/xmlqualifiedname/). |

### Return Value

Yerleşik basit türü temsil eden [XmlSchemaSimpleType](../../xmlschemasimpletype/).

## XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode) metodu

Belirtilen basit türün yerleşik basit türünü temsil eden bir [XmlSchemaSimpleType](../../xmlschemasimpletype/) döndürür.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode typeCode)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | Basit türü temsil eden XmlTypeCode değerlerinden biri. |

### Return Value

Yerleşik basit türü temsil eden [XmlSchemaSimpleType](../../xmlschemasimpletype/).

## Ayrıca Bakınız

* Enum [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlSchemaSimpleType](../../xmlschemasimpletype/)
* Sınıf [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Sınıf [XmlSchemaType](../)
* Ad alanı [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)