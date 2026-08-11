---
title: Compile()
second_title: Aspose.Slides برای C++ مرجع API
description: مدل شیء طرح‌واره XML (SOM) را به اطلاعات طرح‌واره برای اعتبارسنجی کامپایل می‌کند. برای بررسی ساختار نحوی و معنایی SOM ساخته‌شده برنامه‌نویسی استفاده می‌شود. بررسی اعتبار معنایی در هنگام کامپایل انجام می‌گیرد.
type: docs
weight: 352
url: /fa/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) متد

مدل XML [Schema](../../)[Object](../../../system/object/) (SOM) را به اطلاعات طرح‌واره برای اعتبارسنجی کامپایل می‌کند. برای بررسی ساختار نحوی و معنایی SOM ساخته‌شده برنامه‌نویسی استفاده می‌شود. بررسی اعتبار معنایی در هنگام کامپایل انجام می‌گیرد.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | مدیر رویداد اعتبارسنجی که اطلاعات مربوط به خطاهای اعتبارسنجی XML [Schema](../../) را دریافت می‌کند. |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) متد

مدل XML [Schema](../../)[Object](../../../system/object/) (SOM) را به اطلاعات طرح‌واره برای اعتبارسنجی کامپایل می‌کند. برای بررسی ساختار نحوی و معنایی SOM ساخته‌شده برنامه‌نویسی استفاده می‌شود. بررسی اعتبار معنایی در هنگام کامپایل انجام می‌گیرد.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | مدیر رویداد اعتبارسنجی که اطلاعات مربوط به خطاهای اعتبارسنجی XML [Schema](../../) را دریافت می‌کند. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/)ی استفاده شده برای حل فضای‌نام‌ها که در عناصر **include** و **import** ارجاع شده‌اند. |

## موارد مرتبط

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)