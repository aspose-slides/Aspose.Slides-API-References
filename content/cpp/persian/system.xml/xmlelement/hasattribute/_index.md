---
title: HasAttribute()
second_title: Aspose.Slides برای C++ - مرجع API
description: تعیین می‌کند که آیا گرهٔ جاری دارای ویژگی‌ای با نام مشخص شده است.
type: docs
weight: 300
url: /fa/system.xml/xmlelement/hasattribute/
---
## متد XmlElement::HasAttribute(String) method

تعیین می‌کند که آیا گرهٔ جاری دارای ویژگی‌ای با نام مشخص شده است.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام ویژگی که باید پیدا شود. این یک نام Qualified است. با مقدار **get_Name** گرهٔ منطبق مقایسه می‌شود. |

### مقدار برگشت

**true** اگر گرهٔ جاری ویژگی مشخص شده را داشته باشد؛ در غیر این صورت، **false**.

## متد XmlElement::HasAttribute(String, String) method

تعیین می‌کند که آیا گرهٔ جاری دارای ویژگی‌ای با نام محلی و URI فضای نام مشخص شده است.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی ویژگی که باید پیدا شود. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام ویژگی که باید پیدا شود. |

### مقدار برگشت

**true** اگر گرهٔ جاری ویژگی مشخص شده را داشته باشد؛ در غیر این صورت، **false**.

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlElement](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)