---
title: AddComment()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إضافة تعليق جديد في نهاية مجموعة.
type: docs
weight: 14
url: /ar/aspose.slides/icommentcollection/addcomment/
---
## ICommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method

إضافة تعليق جديد في نهاية مجموعة.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | نص عادي لتعليق جديد. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) في عرض تقديمي حيث يتم إضافة تعليق جديد. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | الموضع على الشريحة حيث يتم إضافة تعليق جديد. |
| creationTime | [System::DateTime](../../../system/datetime/) | وقت إنشاء التعليق. |

### قيمة الإرجاع

التعليق المضاف.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IComment](../../icomment/)
* فئة [String](../../../system/string/)
* فئة [ISlide](../../islide/)
* فئة [PointF](../../../system.drawing/pointf/)
* فئة [DateTime](../../../system/datetime/)
* فئة [ICommentCollection](../)
* مساحة الاسم [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)