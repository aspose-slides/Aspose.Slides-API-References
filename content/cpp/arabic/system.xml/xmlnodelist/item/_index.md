---
title: Item()
second_title: مرجع API Aspose.Slides للـ C++
description: يسترجع عقدة في الفهرس المحدد.
type: docs
weight: 14
url: /ar/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item(int32_t) طريقة

يسترجع عقدة في الفهرس المحدد.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس القائم على الصفر في قائمة العقد. |

### قيمة الإرجاع

[XmlNode](../../xmlnode/) بالفهرس المحدد في المجموعة. إذا كان **index** أكبر من أو يساوي عدد العقد في القائمة، فإن هذا يُعيد **nullptr**.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [XmlNode](../../xmlnode/)
* الفئة [XmlNodeList](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)