---
title: InsertModernComment()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إدراج تعليق حديث جديد إلى مجموعة في الفهرس المحدد.
type: docs
weight: 53
url: /ar/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) طريقة


إدراج تعليق حديث جديد إلى مجموعة في الفهرس المحدد.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | فهرس العنصر في مجموعة يتم فيها إدراج التعليق الحديث. |
| text | [System::String](../../../system/string/) | النص العادي لتعليق حديث جديد. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) في عرض تقديمي حيث يتم إضافة تعليق حديث جديد. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) على شريحة يرتبط بها تعليق حديث جديد. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | الموضع على شريحة حيث يتم إضافة تعليق حديث جديد. |
| creationTime | [System::DateTime](../../../system/datetime/) | وقت إنشاء التعليق الحديث. |

### Return Value

التعليق الحديث المدرج.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IModernComment](../../imoderncomment/)
* فئة [String](../../../system/string/)
* فئة [ISlide](../../islide/)
* فئة [IShape](../../ishape/)
* فئة [PointF](../../../system.drawing/pointf/)
* فئة [DateTime](../../../system/datetime/)
* فئة [ICommentCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)