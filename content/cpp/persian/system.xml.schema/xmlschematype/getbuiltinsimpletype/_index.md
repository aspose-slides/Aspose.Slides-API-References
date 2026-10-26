---
title: GetBuiltInSimpleType()
second_title: Aspose.Slides برای C++ مرجع API
description: یک XmlSchemaSimpleType برمی‌گرداند که نوع ساده داخلی نوع ساده‌ای را که توسط نام کیفی مشخص شده است، نمایش می‌دهد.
type: docs
weight: 183
url: /fa/system.xml.schema/xmlschematype/getbuiltinsimpletype/
---
## XmlSchemaType::GetBuiltInSimpleType(const SharedPtr\<XmlQualifiedName\>\&) متد

یک [XmlSchemaSimpleType](../../xmlschemasimpletype/) بر می‌گرداند که نوع ساده داخلی نوع ساده‌ای را که با نام کیفی مشخص شده است، نمایش می‌دهد.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | [XmlQualifiedName](../../../system.xml/xmlqualifiedname/) نوع ساده. |

### مقدار بازگشت

[XmlSchemaSimpleType](../../xmlschemasimpletype/) که نوع ساده داخلی را نمایش می‌دهد.

## XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode) متد

یک [XmlSchemaSimpleType](../../xmlschemasimpletype/) بر می‌گرداند که نوع ساده داخلی نوع ساده مشخص‌شده را نمایش می‌دهد.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode typeCode)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | یکی از مقادیر XmlTypeCode که نوع ساده را نمایش می‌دهد. |

### مقدار بازگشت

[XmlSchemaSimpleType](../../xmlschemasimpletype/) که نوع ساده داخلی را نمایش می‌دهد.

## موارد مرتبط

* Enum [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSimpleType](../../xmlschemasimpletype/)
* Class [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Class [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)