---
title: PrependChild()
second_title: مرجع API Aspose.Slides برای C++
description: گرهٔ مشخص‌شده را به ابتدای لیست گره‌های فرزند این گره اضافه می‌کند.
type: docs
weight: 261
url: /fa/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) متد

گرهٔ مشخص شده را به ابتدای لیست گره‌های فرزند این گره اضافه می‌کند.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) برای اضافه کردن. اگر یک [XmlDocumentFragment](../../xmldocumentfragment/) باشد، تمام محتوای قطعه سند به لیست فرزندان این گره منتقل می‌شود. |

### مقدار برگشتی

[XmlNode](../../xmlnode/) اضافه شد.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNode](../../xmlnode/)
* کلاس [XmlAttribute](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)