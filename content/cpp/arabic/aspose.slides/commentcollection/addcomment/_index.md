---
title: AddComment()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: أضف تعليقًا جديدًا في نهاية مجموعة.
type: docs
weight: 53
url: /ar/aspose.slides/commentcollection/addcomment/
---
## CommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) طريقة

أضف تعليقًا جديدًا في نهاية مجموعة.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | النص العادي لتعليق جديد. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) في عرض تقديمي حيث يتم إضافة تعليق جديد. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | الموضع على الشريحة حيث يتم إضافة تعليق جديد. |
| creationTime | [System::DateTime](../../../system/datetime/) | وقت إنشاء التعليق. |

### قيمة الإرجاع

التعليق المُضاف.

## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IComment](../../icomment/)
* فئة [String](../../../system/string/)
* فئة [ISlide](../../islide/)
* فئة [PointF](../../../system.drawing/pointf/)
* فئة [DateTime](../../../system/datetime/)
* فئة [CommentCollection](../)
* مساحة الاسم [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)