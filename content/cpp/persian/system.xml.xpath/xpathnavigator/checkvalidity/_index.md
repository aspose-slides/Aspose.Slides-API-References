---
title: CheckValidity()
second_title: مرجع API Aspose.Slides برای C++
description: تأیید می‌کند که داده‌های XML در XPathNavigator با زبان تعریف طرح‌واره XML (XSD) ارائه‌شده سازگار هستند.
type: docs
weight: 755
url: /fa/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) method

تأیید می‌کند که داده‌های XML در [XPathNavigator](../) با زبان تعریف XML [Schema](../../../system.xml.schema/) (XSD) ارائه‌شده سازگار باشند.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | XmlSchemaSet شامل طرحواره‌هایی است که برای اعتبارسنجی داده‌های XML موجود در [XPathNavigator](../) استفاده می‌شوند. |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | ValidationEventHandler که اطلاعات مربوط به هشدارها و خطاهای اعتبارسنجی طرحواره را دریافت می‌کند. |

### مقدار بازگشت

**true** اگر هیچ خطای اعتبارسنجی طرحواره‌ای رخ ندهد؛ در غیر این صورت، **false**.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* کلاس [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* کلاس [XPathNavigator](../)
* فضای نام [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)