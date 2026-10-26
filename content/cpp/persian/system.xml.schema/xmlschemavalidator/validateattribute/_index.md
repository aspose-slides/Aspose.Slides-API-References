---
title: ValidateAttribute()
second_title: Aspose.Slides برای C++ مرجع API
description: نام ویژگی، URI فضای نام و مقدار را در زمینه عنصر فعلی اعتبارسنجی می‌کند.
type: docs
weight: 144
url: /fa/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) method

نام ویژگی، URI فضای نام، و مقدار آن را در زمینه عنصر فعلی اعتبارسنجی می‌کند.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | نام محلی ویژگی برای اعتبارسنجی. |
| namespaceUri | const [String](../../../system/string/)\& | URI فضای نام ویژگی برای اعتبارسنجی. |
| attributeValue | const [String](../../../system/string/)\& | مقدار ویژگی برای اعتبارسنجی. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | یک شیء [XmlSchemaInfo](../../xmlschemainfo/) که خصوصیات آن پس از اعتبارسنجی موفق ویژگی تنظیم می‌شود. این پارامتر می‌تواند **nullptr** باشد. |

### مقدار برگشتی

مقدار ویژگی اعتبارسنجی‌شده.

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) method

نام ویژگی، URI فضای نام، و مقدار آن را در زمینه عنصر فعلی اعتبارسنجی می‌کند.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | نام محلی ویژگی برای اعتبارسنجی. |
| namespaceUri | const [String](../../../system/string/)\& | URI فضای نام ویژگی برای اعتبارسنجی. |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | یک فراخوانی XmlValueGetter که برای انتقال مقدار ویژگی به عنوان نوعی سازگار با زبان تعریف XML [Schema](../../) (XSD) ویژگی استفاده می‌شود. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | یک شیء [XmlSchemaInfo](../../xmlschemainfo/) که خصوصیات آن پس از اعتبارسنجی موفق ویژگی تنظیم می‌شود. این پارامتر می‌تواند **nullptr** باشد. |

### مقدار برگشتی

مقدار ویژگی اعتبارسنجی‌شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* کلاس [Object](../../../system/object/)
* کلاس [String](../../../system/string/)
* کلاس [XmlSchemaInfo](../../xmlschemainfo/)
* کلاس [XmlSchemaValidator](../)
* فضای‌نام [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)