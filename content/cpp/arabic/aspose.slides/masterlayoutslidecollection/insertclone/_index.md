---
title: InsertClone()
second_title: Aspose.Slides لمرجع API للغة C++
description: يدرج نسخة من شريحة تخطيط محددة في الموضع المحدد داخل المجموعة.
type: docs
weight: 14
url: /ar/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) طريقة


يدرج نسخة من شريحة تخطيط محددة في الموضع المحدد داخل المجموعة.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | فهرس الشريحة الجديدة. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) للاستنساخ. |

### قيمة الإرجاع

الشريحة المدخلة.
## ملاحظات



سيتم ربط التخطيط الجديد بشريحة الماستر الأصلية لهذه المجموعة من شرائح التخطيط. وبالتالي فهو مماثل لعملية النسخ/اللصق مع \"Use Destination Theme\" خيار في PowerPoint. 

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)