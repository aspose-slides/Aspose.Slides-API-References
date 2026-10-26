---
title: CreateAttribute()
second_title: Aspose.Slides برای C++ مرجع API
description: یک XmlAttribute با نام مشخص شده ایجاد می‌کند.
type: docs
weight: 274
url: /fa/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) method

یک [XmlAttribute](../../xmlattribute/) با نام مشخص ایجاد می‌کند.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | نام کامل صفت. اگر نام شامل دو نقطه باشد، مقدار [XmlNode::get_Prefix](../../xmlnode/get_prefix/) بخش نام پیش از اولین دو نقطه و مقدار [XmlDocument::get_LocalName](../get_localname/) بخش پس از اولین دو نقطه را نشان می‌دهد. [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) خالی می‌ماند مگر این‌که پیشوندی شناخته‌شده پیش‌ساخته مانند **xmlns** باشد. در این حالت get_NamespaceURI دارای مقدار [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/) است. |

### مقدار بازگشتی

‏[XmlAttribute](../../xmlattribute/) جدید.

## XmlDocument::CreateAttribute(const String\&, const String\&) method

یک [XmlAttribute](../../xmlattribute/) با نام کامل مشخص و [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ایجاد می‌کند.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | نام کامل صفت. اگر نام شامل دو نقطه باشد، مقدار [XmlNode::get_Prefix](../../xmlnode/get_prefix/) بخش پیش از دو نقطه و مقدار [XmlDocument::get_LocalName](../get_localname/) بخش پس از دو نقطه را نشان می‌دهد. |
| namespaceURI | const [String](../../../system/string/)\& | namespaceURI صفت. اگر نام کامل شامل پیشوند **xmlns** باشد، این پارامتر باید [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/) باشد. |

### مقدار بازگشتی

‏[XmlAttribute](../../xmlattribute/) جدید.

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) method

یک [XmlAttribute](../../xmlattribute/) با [XmlNode::get_Prefix](../../xmlnode/get_prefix/)، [XmlDocument::get_LocalName](../get_localname/) و [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) مشخص ایجاد می‌کند.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | پیشوند صفت (در صورت وجود). [String::Empty](../../../system/string/empty/) و **nullptr** معادل هستند. |
| localName | const [String](../../../system/string/)\& | نام محلی صفت. |
| namespaceURI | const [String](../../../system/string/)\& | URI فضای‌نام صفت (در صورت وجود). [String::Empty](../../../system/string/empty/) و **nullptr** معادل هستند. اگر **prefix** برابر **xmlns** باشد، این پارامتر باید [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) باشد، در غیر این صورت استثنا پرتاب می‌شود. |

### مقدار بازگشتی

‏[XmlAttribute](../../xmlattribute/) جدید.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlAttribute](../../xmlattribute/)
* کلاس [String](../../../system/string/)
* کلاس [XmlDocument](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)