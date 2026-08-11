---
title: SetAttribute()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار ویژگی را با نام مشخص شده تنظیم می‌کند.
type: docs
weight: 222
url: /fa/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) متد

مقدار ویژگی با نام مشخص شده را تنظیم می‌کند.

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام ویژگی برای ایجاد یا تغییر. این یک نام دارای‌صلاحیت است. اگر نام شامل دو نقطه باشد، به اجزای پیشوند و نام محلی تقسیم می‌شود. |
| value | [String](../../../system/string/) | مقداری که برای ویژگی تنظیم می‌شود. |

## XmlElement::SetAttribute(String, String, String) متد

مقدار ویژگی با نام محلی و URI فضای نام مشخص شده را تنظیم می‌کند.

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی ویژگی. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام ویژگی. |
| value | [String](../../../system/string/) | مقداری که برای ویژگی تنظیم می‌شود. |

### مقدار بازگشتی

مقدار ویژگی.

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlElement](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)