---
title: get_LocalName()
second_title: مرجع API Aspose.Slides برای C++
description: هنگامی که در یک کلاس مشتق شده بازنویسی شود، نام محلی گرهٔ فعلی را برمی‌گرداند.
type: docs
weight: 40
url: /fa/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() متد

هنگامی که در یک کلاس مشتق‌شده بازنویسی شود، نام محلی گرهٔ جاری را برمی‌گرداند.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```

### مقدار بازگشت

نام گرهٔ جاری پس از حذف پیشوند. به عنوان مثال، **LocalName** برای عنصر **<bk:book>** برابر با **book** است. برای انواع گره‌ای که نام ندارند (مانند **[Text](../../../system.text/)**، **Comment**، و غیره)، این متد [String::Empty](../../../system/string/empty/) را برمی‌گرداند.

## مراجع

* کلاس [String](../../../system/string/)
* کلاس [XmlReader](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)