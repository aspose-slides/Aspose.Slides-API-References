---
title: InsertComment()
second_title: مرجع API Aspose.Slides للـ C++
description: إدراج تعليق جديد إلى مجموعة عند الفهرس المحدد.
type: docs
weight: 79
url: /ar/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) طريقة


إدراج تعليق جديد إلى مجموعة عند الفهرس المحدد.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | مؤشر العنصر في مجموعة حيث يجب إدراج التعليق. |
| text | [System::String](../../../system/string/) | النص العادي للتعليق الجديد. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) في عرض تقديمي حيث يتم إضافة تعليق جديد. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | الموضع على شريحة حيث يتم إضافة تعليق جديد. |
| creationTime | [System::DateTime](../../../system/datetime/) | وقت إنشاء التعليق. |

### قيمة الإرجاع

التعليق المُدرج.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IComment](../../icomment/)
* فئة [String](../../../system/string/)
* فئة [ISlide](../../islide/)
* فئة [PointF](../../../system.drawing/pointf/)
* فئة [DateTime](../../../system/datetime/)
* فئة [CommentCollection](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)