---
title: Item()
second_title: Aspose.Slides برای مرجع API C++
description: گره‌ای را در شاخص داده شده بازیابی می‌کند.
type: docs
weight: 14
url: /fa/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item(int32_t) متد

یک گره را در شاخص داده شده برمی‌گرداند.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | شاخص صفر-محور در فهرست گره‌ها. |

### مقدار بازگشتی

[XmlNode](../../xmlnode/) با شاخص مشخص شده در مجموعه. اگر **index** بزرگتر یا مساوی تعداد گره‌ها در فهرست باشد، این مقدار **nullptr** را برمی‌گرداند.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNode](../../xmlnode/)
* کلاس [XmlNodeList](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)