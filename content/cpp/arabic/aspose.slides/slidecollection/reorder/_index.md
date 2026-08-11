---
title: Reorder()
second_title: دليل واجهة برمجة التطبيقات Aspose.Slides للـ C++
description: ينقل الشريحة من المجموعة إلى الموضع المحدد.
type: docs
weight: 157
url: /ar/aspose.slides/slidecollection/reorder/
---
## SlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) طريقة

ينقل الشريحة من المجموعة إلى الموضع المحدد.

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الهدف. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) للنقل. |

## SlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) طريقة

ينقل الشرائح من المجموعة إلى الموضع المحدد. سيتم وضع [Slides](../../) بدءًا من الفهرس وفقًا لترتيب ظهورها في القائمة.

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الهدف. |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) للنقل. |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [ISlide](../../islide/)
* فئة [SlideCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)