---
title: InsertClone()
second_title: مرجع API Aspose.Slides للغة C++
description: يدرج نسخة من شريحة تخطيط محددة في الموضع المحدد داخل المجموعة.
type: docs
weight: 14
url: /ar/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) method


يدرج نسخة من شريحة تخطيط محددة في الموضع المحدد داخل المجموعة.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | فهرس الشريحة الجديدة. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) للاستنساخ. |

### قيمة الإرجاع

الشريحة المُدخلة.

## ملاحظات



سيتم ربط التخطيط الجديد بالشريحة الرئيسية الأم لمجموعة شرائح التخطيط هذه. لذا فهذا يُعادل النسخ/اللصق مع خيار "Use Destination Theme" في PowerPoint. 

## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)