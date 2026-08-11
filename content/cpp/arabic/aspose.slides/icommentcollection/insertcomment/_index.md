---
title: InsertComment()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إدراج تعليق جديد إلى مجموعة في الفهرس المحدد.
type: docs
weight: 40
url: /ar/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) طريقة

إدراج تعليق جديد إلى مجموعة في الفهرس المحدد.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | فهرس العنصر في المجموعة التي يجب إدراج التعليق عنده. |
| text | [System::String](../../../system/string/) | النص العادي لتعليق جديد. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) في عرض تقديمي حيث يتم إضافة تعليق جديد. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | الموقع على الشريحة حيث يتم إضافة التعليق الجديد. |
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
* فئة [ICommentCollection](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)