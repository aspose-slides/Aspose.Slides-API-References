---
title: Item()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يسترجع العقدة في الفهرس المحدد في XmlNamedNodeMap.
type: docs
weight: 53
url: /ar/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) طريقة


يسترجع العقدة الموجودة في الفهرس المحدد في [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | موضع الفهرس للعقدة التي يتم استرجاعها من [XmlNamedNodeMap](../). الفهرس يبدأ من الصفر؛ وبالتالي، فهرس أول عقدة هو 0 وفهرس آخر عقدة هو [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### قيمة الإرجاع

الـ[XmlNode](../../xmlnode/) في الفهرس المحدد. إذا كان **index** أقل من 0 أو أكبر من أو يساوي قيمة [XmlNamedNodeMap::get_Count](../get_count/)، يتم إرجاع **nullptr**.

## راجع أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNode](../../xmlnode/)
* فئة [XmlNamedNodeMap](../)
* مساحة الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)