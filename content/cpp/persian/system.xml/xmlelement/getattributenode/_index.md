---
title: GetAttributeNode()
second_title: مرجع API Aspose.Slides برای C++
description: ویژگی XmlAttribute را با نام مشخص باز می‌گرداند.
type: docs
weight: 248
url: /fa/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) متد

[XmlAttribute](../../xmlattribute/) را با نام مشخص باز می‌گرداند.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام ویژگی برای بازیابی. این یک نام معتبر است. با مقدار **get_Name** گرهٔ همخوان مقایسه می‌شود. |

### مقدار بازگشت

[XmlAttribute](../../xmlattribute/) مشخص یا **nullptr** اگر ویژگی همخوان پیدا نشد.

## XmlElement::GetAttributeNode(String, String) متد

[XmlAttribute](../../xmlattribute/) را با نام محلی و URI فضای نام مشخص باز می‌گرداند.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی ویژگی. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام ویژگی. |

### مقدار بازگشت

[XmlAttribute](../../xmlattribute/) مشخص یا **nullptr** اگر ویژگی همخوان پیدا نشد.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlAttribute](../../xmlattribute/)
* کلاس [String](../../../system/string/)
* کلاس [XmlElement](../)
* فضای نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)