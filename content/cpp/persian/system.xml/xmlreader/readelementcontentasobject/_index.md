---
title: ReadElementContentAsObject()
second_title: Aspose.Slides برای C++ مرجع API
description: المان جاری را می‌خواند و محتوا را به عنوان یک شیء بر می‌گرداند.
type: docs
weight: 469
url: /fa/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() متد

المان جاری را می‌خواند و محتوا را به عنوان یک [Object](../../../system/object/) بر می‌گرداند.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```

### مقدار بازگشت

یک شیء بسته‌بندی‌شده از مناسب‌ترین نوع. مقدار [XmlReader::get_ValueType](../get_valuetype/) نوع مناسب را تعیین می‌کند. اگر محتوا به عنوان یک نوع فهرست مشخص شده باشد، این متد یک آرایه از اشیاء بسته‌بندی‌شده از نوع مناسب را برمی‌گرداند.

## XmlReader::ReadElementContentAsObject(String, String) متد

بررسی می‌کند که نام محلی و URI فضای نام مشخص شده با المان جاری مطابقت داشته باشد، سپس المان جاری را می‌خواند و محتوا را به عنوان یک [Object](../../../system/object/) بر می‌گرداند.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی عنصر. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام عنصر. |

### مقدار بازگشت

یک شیء بسته‌بندی‌شده از مناسب‌ترین نوع. مقدار [XmlReader::get_ValueType](../get_valuetype/) نوع مناسب را تعیین می‌کند. اگر محتوا به عنوان یک نوع فهرست مشخص شده باشد، این متد یک آرایه از اشیاء بسته‌بندی‌شده از نوع مناسب را برمی‌گرداند.

## موارد مرتبط

* نوع‌تعریف [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [XmlReader](../)
* کلاس [String](../../../system/string/)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)