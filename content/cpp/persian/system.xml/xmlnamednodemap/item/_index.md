---
title: Item()
second_title: مرجع API Aspose.Slides برای C++
description: گره‌ای را که در اندیس مشخص شده در XmlNamedNodeMap قرار دارد، بازیابی می‌کند.
type: docs
weight: 53
url: /fa/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) متد

گره‌ای را که در اندیس مشخص شده در [XmlNamedNodeMap](../) قرار دارد، بازیابی می‌کند.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | موقعیت شاخص گره‌ای که باید از [XmlNamedNodeMap](../) بازیابی شود. این اندیس از صفر شروع می‌شود؛ بنابراین، اندیس گرهٔ اول برابر 0 است و اندیس گرهٔ آخر برابر [XmlNamedNodeMap::get_Count](../get_count/) - 1 می‌باشد. |

### مقدار بازگشتی

[XmlNode](../../xmlnode/) در اندیس مشخص‌شده. اگر **index** کمتر از 0 یا بزرگتر یا مساوی مقدار [XmlNamedNodeMap::get_Count](../get_count/) باشد، **nullptr** بازگردانده می‌شود.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNode](../../xmlnode/)
* کلاس [XmlNamedNodeMap](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)