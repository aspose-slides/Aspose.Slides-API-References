---
title: IsDerivedFrom()
second_title: مرجع API Aspose.Slides برای C++
description: مقداری را برمی‌گرداند که نشان می‌دهد آیا نوع schema مشتق‌شدهٔ مشخص شده از نوع schema پایهٔ مشخص شده مشتق شده است.
type: docs
weight: 209
url: /fa/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) متد

مقداری را برمی‌گرداند که نشان می‌دهد آیا نوع schema مشتق‌شدهٔ مشخص شده از نوع schema پایهٔ مشخص شده مشتق شده است.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | شیء [XmlSchemaType](../) مشتق برای آزمایش |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | پایه [XmlSchemaType](../) برای آزمایش [XmlSchemaType](../) مشتق |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | یکی از مقادیر XmlSchemaDerivationMethod که نشان‌دهندهٔ روش استخراج نوع برای حذف از آزمایش است |

### مقدار بازگشت

**true** اگر نوع مشتق از نوع پایه مشتق شده باشد؛ در غیر اینصورت، **false**.

## مراجع

* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)