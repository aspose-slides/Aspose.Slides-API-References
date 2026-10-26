---
title: ValidateElement()
second_title: مرجع API Aspose.Slides برای C++
description: عنصر را در زمینه فعلی اعتبارسنجی می‌کند.
type: docs
weight: 131
url: /fa/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) متد

عنصر را در زمینه فعلی اعتبارسنجی می‌کند.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | نام محلی عنصری که باید اعتبارسنجی شود. |
| namespaceUri | const [String](../../../system/string/)\& | URI فضای‌نام عنصر برای اعتبارسنجی. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | یک شیء [XmlSchemaInfo](../../xmlschemainfo/) که خصوصیات آن پس از اعتبارسنجی موفقیت‌آمیز نام عنصر تنظیم می‌شود. این پارامتر می‌تواند **nullptr** باشد. |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) متد

عنصر را در زمینه فعلی با مقادیر ویژگی **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** و **xsi:NoNamespaceSchemaLocation** مشخص‌شده اعتبارسنجی می‌کند.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | نام محلی عنصری که باید اعتبارسنجی شود. |
| namespaceUri | const [String](../../../system/string/)\& | URI فضای‌نام عنصر برای اعتبارسنجی. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | یک شیء [XmlSchemaInfo](../../xmlschemainfo/) که خصوصیات آن پس از اعتبارسنجی موفقیت‌آمیز نام عنصر تنظیم می‌شود. این پارامتر می‌تواند **nullptr** باشد. |
| xsiType | const [String](../../../system/string/)\& | مقدار ویژگی **xsi:Type** عنصر. این پارامتر می‌تواند **nullptr** باشد. |
| xsiNil | const [String](../../../system/string/)\& | مقدار ویژگی **xsi:Nil** عنصر. این پارامتر می‌تواند **nullptr** باشد. |
| xsiSchemaLocation | const [String](../../../system/string/)\& | مقدار ویژگی **xsi:SchemaLocation** عنصر. این پارامتر می‌تواند **nullptr** باشد. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | مقدار ویژگی **xsi:NoNamespaceSchemaLocation** عنصر. این پارامتر می‌تواند **nullptr** باشد. |

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [XmlSchemaInfo](../../xmlschemainfo/)
* کلاس [XmlSchemaValidator](../)
* فضای‌نام [System::Xml::Schema](../../)
* کتابخانه [Aspose.Slides](../../../)