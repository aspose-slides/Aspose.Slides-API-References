---
title: Remove()
second_title: مرجع API Aspose.Slides للغة C++
description: يزيل تخطيطًا من المجموعة.
type: docs
weight: 66
url: /ar/aspose.slides/layoutslidecollection/remove/
---
## LayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) طريقة

يزيل تخطيطًا من المجموعة.

```cpp
void Aspose::Slides::LayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | شريحة التخطيط التي سيتم إزالتها من المجموعة. |

## ملاحظات

1) لتجنب حدوث استثناء PptxEditException، تحقق من خاصية HasDependingSlides للتخطيط مسبقًا. 2) يمكنك أيضًا استخدام طريقة [ILayoutSlide::Remove](../../ilayoutslide/remove/) لتبسيط الشيفرة. 

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ILayoutSlide](../../ilayoutslide/)
* فئة [LayoutSlideCollection](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)