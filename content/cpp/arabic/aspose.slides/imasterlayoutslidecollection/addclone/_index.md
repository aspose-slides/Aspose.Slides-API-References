---
title: AddClone()
second_title: Aspose.Slides لـ C++ مرجع API
description: يضيف نسخة من شريحة تخطيط محددة إلى نهاية المجموعة.
type: docs
weight: 1
url: /ar/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) طريقة


يضيف نسخة من شريحة تخطيط محددة إلى نهاية المجموعة.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) للنسخ. |

### قيمة الإرجاع

الشريحة المضافة.
## ملاحظات



1) سيتم ربط التصميم الجديد بشريحة الماستر الأصلية لمجموعة شرائح التصميم هذه. لذا هذا يشبه النسخ/اللصق مع خيار \"Use Destination Theme\" في PowerPoint. 2) نظير هذه الطريقة هو الطريقة [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) التي يتم الوصول إليها عبر خاصية [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ILayoutSlide](../../ilayoutslide/)
* فئة [IMasterLayoutSlideCollection](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)