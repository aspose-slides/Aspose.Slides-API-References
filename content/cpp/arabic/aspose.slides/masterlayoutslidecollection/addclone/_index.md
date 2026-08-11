---
title: AddClone()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف نسخة من شريحة تخطيط محددة إلى نهاية المجموعة.
type: docs
weight: 1
url: /ar/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) طريقة

يضيف نسخة من شريحة تخطيط محددة إلى نهاية المجموعة.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) للتكرار. |

### قيمة الإرجاع

الشريحة المضافة.

## ملاحظات

1) سيتم ربط التصميم الجديد مع الشريحة الرئيسية الأصلية لمجموعة شرائح التصميم هذه. لذلك فهذا يعادل النسخ/اللصق مع خيار "Use Destination Theme" في PowerPoint. 2) نظير هذه الطريقة هو الطريقة [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) التي يتم الوصول إليها عبر خاصية [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ILayoutSlide](../../ilayoutslide/)
* فئة [MasterLayoutSlideCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)