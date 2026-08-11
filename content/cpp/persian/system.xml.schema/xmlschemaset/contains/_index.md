---
title: Contains()
second_title: Aspose.Slides برای C++ مرجع API
description: نشان می‌دهد که آیا یک طرح‌واره زبان تعریف XML (XSD) با URI نام‌فضای هدف مشخص در XmlSchemaSet موجود است یا خیر.
type: docs
weight: 196
url: /fa/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) متد

نشان می‌دهد که آیا یک طرح‌واره XML [Schema](../../) زبان تعریف (XSD) با نام‌فضای هدف URI مشخص در [XmlSchemaSet](../) موجود است یا خیر.

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | ویژگی **targetNamespace** طرح‌واره. |

### مقدار برگردانده شده

**true** اگر طرح‌واره‌ای با نام‌فضای هدف URI مشخص در [XmlSchemaSet](../) موجود باشد؛ در غیر این صورت، **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) متد

نشان می‌دهد که آیا شیء [XmlSchema](../../xmlschema/) XML [Schema](../../) زبان تعریف (XSD) مشخص در [XmlSchemaSet](../) موجود است یا خیر.

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | شیء [XmlSchema](../../xmlschema/). |

### مقدار برگردانده شده

**true** اگر شیء [XmlSchema](../../xmlschema/) در [XmlSchemaSet](../) موجود باشد؛ در غیر این صورت، **false**.

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Class [XmlSchema](../../xmlschema/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)