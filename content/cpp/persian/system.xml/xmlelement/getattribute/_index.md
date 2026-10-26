---
title: GetAttribute()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار ویژگی با نام مشخص‌شده را برمی‌گرداند.
type: docs
weight: 209
url: /fa/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) متد

مقدار ویژگی با نام مشخص‌شده را برمی‌گرداند.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام ویژگی که باید بازیابی شود. این یک نام معتبر است. با مقدار **get_Name** گرهٔ مطابق مقایسه می‌شود. |

### مقدار برگشتی

مقدار ویژگی مشخص‌شده. اگر ویژگی مطابق پیدا نشود یا ویژگی مقدار مشخص یا پیش‌فرض نداشته باشد، یک رشتهٔ خالی برگردانده می‌شود.

## XmlElement::GetAttribute(String, String) متد

مقدار ویژگی با نام محلی و URI فضای نام مشخص‌شده را برمی‌گرداند.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی ویژگی که باید بازیابی شود. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام ویژگی که باید بازیابی شود. |

### مقدار برگشتی

مقدار ویژگی مشخص‌شده. اگر ویژگی مطابق پیدا نشود یا ویژگی مقدار مشخص یا پیش‌فرض نداشته باشد، یک رشتهٔ خالی برگردانده می‌شود.

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlElement](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)