---
title: Validate()
second_title: Aspose.Slides برای مرجع API C++
description: "XmlDocument را نسبت به طرح‌واره‌های XML Schema Definition Language (XSD) موجود در لیست XmlDocument::get_Schemas اعتبارسنجی می‌کند."
type: docs
weight: 573
url: /fa/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) متد

[XmlDocument](../) را نسبت به طرح‌واره‌های XML [Schema](../../../system.xml.schema/) Definition Language (XSD) که در فهرست [XmlDocument::get_Schemas](../get_schemas/) موجود است، اعتبارسنجی می‌کند.

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | شی [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) که اطلاعات مربوط به هشدارها و خطاهای اعتبارسنجی طرحواره را دریافت می‌کند. |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) متد

[XmlNode](../../xmlnode/) را نسبت به طرح‌واره‌های XML [Schema](../../../system.xml.schema/) Definition Language (XSD) موجود در فهرست [XmlDocument::get_Schemas](../get_schemas/) اعتبارسنجی می‌کند.

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | شی [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) که اطلاعات مربوط به هشدارها و خطاهای اعتبارسنجی طرحواره را دریافت می‌کند. |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | شی [XmlNode](../../xmlnode/) ایجاد شده از یک [XmlDocument](../) برای اعتبارسنجی. |

## موارد مرتبط

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlDocument](../)
* کلاس [XmlNode](../../xmlnode/)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)