---
title: SetNamedItem()
second_title: Aspose.Slides برای C++ مرجع API
description: "یک XmlNode را با استفاده از مقدار XmlNode::get_Name آن اضافه می‌کند."
type: docs
weight: 27
url: /fa/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) متد

یک [XmlNode](../../xmlnode/) را با استفاده از مقدار [XmlNode::get_Name](../../xmlnode/get_name/) آن اضافه می‌کند.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | یک [XmlNode](../../xmlnode/) برای ذخیره‌سازی در [XmlNamedNodeMap](../). اگر گره‌ای با همان نام قبلاً در نقشه وجود داشته باشد، توسط گره جدید جایگزین می‌شود. |

### مقدار بازگشت

اگر **node** یک گره موجود با همان نام را جایگزین کند، گرهٔ قبلی بازگردانده می‌شود؛ در غیر اینصورت، **nullptr** بازگردانده می‌شود.

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNode](../../xmlnode/)
* کلاس [XmlNamedNodeMap](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)