---
title: RemoveAttributeNode()
second_title: مرجع API Aspose.Slides برای C++
description: ویژگی XmlAttribute مشخص شده را حذف می‌کند.
type: docs
weight: 274
url: /fa/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) متد

مورد [XmlAttribute](../../xmlattribute/) مشخص شده را حذف می‌کند.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | گره [XmlAttribute](../../xmlattribute/) برای حذف. اگر ویژگی حذف‌شده مقدار پیش‌فرض داشته باشد، بلافاصله جایگزین می‌شود. |

### مقدار بازگشت

[XmlAttribute](../../xmlattribute/) حذف‌شده یا **nullptr** اگر **oldAttr** گره ویژگی از [XmlElement](../) نباشد.

## XmlElement::RemoveAttributeNode(String, String) متد

[XmlAttribute](../../xmlattribute/) را بر اساس نام محلی و URI فضای نام حذف می‌کند. (اگر ویژگی حذف‌شده مقدار پیش‌فرض داشته باشد، بلافاصله جایگزین می‌شود).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی ویژگی. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام ویژگی. |

### مقدار بازگشت

[XmlAttribute](../../xmlattribute/) حذف‌شده یا **nullptr** اگر [XmlElement](../) ویژگی منطبقی نداشته باشد.

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)