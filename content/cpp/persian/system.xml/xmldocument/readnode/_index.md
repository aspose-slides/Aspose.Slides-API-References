---
title: ReadNode()
second_title: مرجع API Aspose.Slides برای C++
description: یک شیء XmlNode را بر اساس اطلاعات موجود در XmlReader ایجاد می‌کند. خواننده باید روی یک گره یا ویژگی قرار داشته باشد.
type: docs
weight: 495
url: /fa/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) method

یک شیء [XmlNode](../../xmlnode/) را بر اساس اطلاعات موجود در [XmlReader](../../xmlreader/) ایجاد می‌کند. خواننده باید روی یک گره یا ویژگی قرار داشته باشد.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | منبع XML. |

### مقدار بازگشت

شیء جدید [XmlNode](../../xmlnode/) یا **nullptr** در صورتی که گره‌های بیشتری وجود نداشته باشد.

## همچنین نگاه کنید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNode](../../xmlnode/)
* کلاس [XmlReader](../../xmlreader/)
* کلاس [XmlDocument](../)
* فضای‌نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)