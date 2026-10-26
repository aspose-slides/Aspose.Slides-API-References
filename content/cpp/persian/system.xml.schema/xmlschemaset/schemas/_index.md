---
title: Schemas()
second_title: مرجع API Aspose.Slides برای C++
description: یک مجموعه از تمام طرح‌واره‌های زبان تعریف XML Schema (XSD) در XmlSchemaSet برمی‌گرداند.
type: docs
weight: 248
url: /fa/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() متد

یک مجموعه از تمام طرح‌واره‌های زبان تعریف XML [Schema](../../) (XSD) در [XmlSchemaSet](../) را برمی‌گرداند.

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```

### مقدار بازگشتی

یک شیء IList که حاوی تمام طرح‌واره‌هایی است که به [XmlSchemaSet](../) اضافه شده‌اند. اگر هیچ طرح‌واره‌ای به [XmlSchemaSet](../) اضافه نشده باشد، یک مجموعه خالی برگردانده می‌شود.

## XmlSchemaSet::Schemas(String) متد

یک مجموعه از تمام طرح‌واره‌های زبان تعریف XML [Schema](../../) (XSD) در [XmlSchemaSet](../) که به فضای‌نام داده‌شده تعلق دارند را برمی‌گرداند.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | خاصیت **targetNamespace** طرح‌واره. |

### مقدار بازگشتی

یک شیء IList که حاوی تمام طرح‌واره‌هایی است که به [XmlSchemaSet](../) اضافه شده‌اند و به فضای‌نام داده‌شده تعلق دارند. اگر هیچ طرح‌واره‌ای به [XmlSchemaSet](../) اضافه نشده باشد، یک مجموعه خالی برگردانده می‌شود.

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IList](../../../system.collections.generic/ilist/)
* کلاس [XmlSchema](../../xmlschema/)
* کلاس [XmlSchemaSet](../)
* کلاس [List](../../../system.collections.generic/list/)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Xml::Schema](../../)
* کتابخانه [Aspose.Slides](../../../)