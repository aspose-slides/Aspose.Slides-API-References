---
title: CreateElement()
second_title: Aspose.Slides برای C++ مرجع API
description: عنصری با نام مشخص شده ایجاد می‌کند.
type: docs
weight: 339
url: /fa/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) متد

یک عنصر با نام مشخص شده ایجاد می‌کند.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | نام کامل عنصر. اگر نام شامل دو نقطه باشد، مقدار [XmlNode::get_Prefix](../../xmlnode/get_prefix/) بخش قبل از دو نقطه را نشان می‌دهد و مقدار [XmlDocument::get_LocalName](../get_localname/) بخش پس از دو نقطه را نشان می‌دهد. نام کامل نمی‌تواند پیشوند **xmlns** داشته باشد. |

### Return Value

[XmlElement](../../xmlelement/) جدید.

## XmlDocument::CreateElement(const String\&, const String\&) متد

یک [XmlElement](../../xmlelement/) با نام کامل و [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ایجاد می‌کند.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | نام کامل عنصر. اگر نام شامل دو نقطه باشد، مقدار [XmlNode::get_Prefix](../../xmlnode/get_prefix/) بخش قبل از دو نقطه را نشان می‌دهد و مقدار [XmlDocument::get_LocalName](../get_localname/) بخش پس از دو نقطه را نشان می‌دهد. نام کامل نمی‌تواند پیشوند **xmlns** داشته باشد. |
| namespaceURI | const [String](../../../system/string/)\& | URI فضای نام عنصر. |

### Return Value

[XmlElement](../../xmlelement/) جدید.

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) متد

یک عنصر با [XmlNode::get_Prefix](../../xmlnode/get_prefix/)، [XmlDocument::get_LocalName](../get_localname/) و [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) مشخص شده ایجاد می‌کند.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | پیشوند عنصر جدید (در صورت وجود). [String::Empty](../../../system/string/empty/) و **nullptr** معادل هستند. |
| localName | const [String](../../../system/string/)\& | نام محلی عنصر جدید. |
| namespaceURI | const [String](../../../system/string/)\& | URI فضای نام عنصر جدید (در صورت وجود). [String::Empty](../../../system/string/empty/) و **nullptr** معادل هستند. |

### Return Value

[XmlElement](../../xmlelement/) جدید.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlElement](../../xmlelement/)
* کلاس [String](../../../system/string/)
* کلاس [XmlDocument](../)
* فضای نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)