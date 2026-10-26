---
title: idx_get()
second_title: Aspose.Slides لـ C++ مرجع API
description: تُعيد عقدة في الفهرس المحدد.
type: docs
weight: 40
url: /ar/system.xml/xmlnodelist/idx_get/
---
## XmlNodeList::idx_get(int32_t) طريقة

تُرجع عقدة في الفهرس المحدد.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::idx_get(int32_t i)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | **int32_t** | الفهرس الصفري في قائمة العقد. |

### قيمة الإرجاع

الـ [XmlNode](../../xmlnode/) بالفهرس المحدد في المجموعة. إذا كان الفهرس أكبر من أو يساوي عدد العقد في القائمة، فإن هذا يُعيد **nullptr**.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNode](../../xmlnode/)
* فئة [XmlNodeList](../)
* مساحة الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)