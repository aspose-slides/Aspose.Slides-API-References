---
title: RemoveNamedItem()
second_title: مرجع API Aspose.Slides برای C++
description: گره را از XmlNamedNodeMap حذف می‌کند.
type: docs
weight: 40
url: /fa/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) متد

گره را از [XmlNamedNodeMap](../) حذف می‌کند.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام کامل گره برای حذف. این نام با مقدار [XmlNode::get_Name](../../xmlnode/get_name/) گره مطابقت داده می‌شود. |

### مقدار بازگشت

[XmlNode](../../xmlnode/) حذف‌شده از این [XmlNamedNodeMap](../) یا **nullptr** اگر گره‌ای مطابقت‌دهنده یافت نشد.

## XmlNamedNodeMap::RemoveNamedItem(String, String) متد

گره‌ای با مقادیر [XmlNode::get_LocalName](../../xmlnode/get_localname/) و [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) مطابقت‌دهنده حذف می‌کند.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی گره برای حذف. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام گره برای حذف. |

### مقدار بازگشت

[XmlNode](../../xmlnode/) حذف‌شده یا **nullptr** اگر گره‌ای مطابقت‌دهنده یافت نشد.

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNode](../../xmlnode/)
* کلاس [String](../../../system/string/)
* کلاس [XmlNamedNodeMap](../)
* فضای‌نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)