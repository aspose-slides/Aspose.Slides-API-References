---
title: Reorder()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينقل الشريحة من المجموعة إلى الموضع المحدد.
type: docs
weight: 105
url: /ar/aspose.slides/islidecollection/reorder/
---
## ISlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) طريقة

ينقل الشريحة من المجموعة إلى الموضع المحدد.

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide)=0
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | فهرس الهدف. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) للنقل. |

## ISlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) طريقة

ينقل الشرائح من المجموعة إلى الموضع المحدد. [Slides](../../) سيتم وضعه بدءًا من الفهرس وفقًا للترتيب الذي يظهر به في القائمة.

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides)=0
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | فهرس الهدف. |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) للنقل. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [ISlide](../../islide/)
* فئة [ISlideCollection](../)
* فضاء الاسم [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)