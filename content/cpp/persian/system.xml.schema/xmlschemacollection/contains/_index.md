---
title: Contains()
second_title: Aspose.Slides برای C++ مرجع API
description: مقدار را برمی‌گرداند که نشان می‌دهد آیا targetNamespace از XmlSchema مشخص‌شده در مجموعه موجود است یا خیر.
type: docs
weight: 66
url: /fa/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) متد

مقداری را برمی‌گرداند که نشان می‌دهد آیا **targetNamespace** از [XmlSchema](../../xmlschema/) مشخص شده در مجموعه موجود است یا خیر.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | شیء [XmlSchema](../../xmlschema/). |

### مقدار بازگشت

**true** اگر یک schema در مجموعه با **targetNamespace** یکسان وجود داشته باشد؛ در غیر این صورت، **false**.

## XmlSchemaCollection::Contains(const String\&) متد

مقداری را برمی‌گرداند که نشان می‌دهد آیا یک schema با فضای‌نام مشخص شده در مجموعه موجود است یا خیر.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI فضای‌نام مرتبط با schema. برای XML Schemas، معمولاً این فضای‌نام هدف خواهد بود. |

### مقدار بازگشت

**true** اگر یک schema در مجموعه با **targetNamespace** یکسان وجود داشته باشد؛ در غیر این صورت، **false**.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlSchema](../../xmlschema/)
* کلاس [XmlSchemaCollection](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)