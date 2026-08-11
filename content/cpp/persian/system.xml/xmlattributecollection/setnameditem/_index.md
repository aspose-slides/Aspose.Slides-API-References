---
title: SetNamedItem()
second_title: مرجع API Aspose.Slides برای C++
description: "یک XmlNode را با استفاده از نتیجه XmlNode::get_Name آن اضافه می‌کند."
type: docs
weight: 14
url: /fa/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) متد

یک [XmlNode](../../xmlnode/) را با استفاده از نتیجه [XmlNode::get_Name](../../xmlnode/get_name/) آن اضافه می‌کند.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | یک گره ویژگی برای ذخیره در این مجموعه. گره بعداً با استفاده از نام گره قابل دسترسی خواهد بود. اگر گره‌ای با همان نام قبلاً در مجموعه موجود باشد، با گره جدید جایگزین می‌شود؛ در غیر این صورت، گره به انتهای مجموعه اضافه می‌شود. |

### مقدار بازگشت

اگر **node** یک گره موجود با همان نام را جایگزین کند، گرهٔ قدیمی بازگردانده می‌شود؛ در غیر این صورت، گرهٔ اضافه‌شده بازگردانده می‌شود.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNode](../../xmlnode/)
* کلاس [XmlAttributeCollection](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)