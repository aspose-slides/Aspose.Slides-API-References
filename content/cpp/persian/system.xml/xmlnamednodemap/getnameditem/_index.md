---
title: GetNamedItem()
second_title: Aspose.Slides برای C++ مرجع API
description: یک XmlNode را که با نام مشخص شده است بازیابی می‌کند.
type: docs
weight: 14
url: /fa/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) متد

یک [XmlNode](../../xmlnode/) را که با نام مشخص شده است بازیابی می‌کند.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام جامع گره‌ای که باید بازیابی شود. این نام در برابر مقدار [XmlNode::get_Name](../../xmlnode/get_name/) گرهٔ منطبق مقایسه می‌شود. |

### مقدار بازگشت

یک [XmlNode](../../xmlnode/) با نام مشخص شده یا **nullptr** اگر گره منطبق پیدا نشود، برمی‌گرداند.

## XmlNamedNodeMap::GetNamedItem(String, String) متد

گره‌ای را با مقادیر [XmlNode::get_LocalName](../../xmlnode/get_localname/) و [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) منطبق بازیابی می‌کند.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی گره‌ای که باید بازیابی شود. |
| namespaceURI | [String](../../../system/string/) | شناسهٔ یکتا (URI) فضای نام گره‌ای که باید بازیابی شود. |

### مقدار بازگشت

یک [XmlNode](../../xmlnode/) با نام محلی و URI فضای نام منطبق یا **nullptr** اگر گره منطبق یافت نشود.

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNode](../../xmlnode/)
* کلاس [String](../../../system/string/)
* کلاس [XmlNamedNodeMap](../)
* فضای نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)