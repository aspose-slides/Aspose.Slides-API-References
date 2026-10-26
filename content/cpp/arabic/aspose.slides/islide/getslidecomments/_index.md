---
title: GetSlideComments()
second_title: Aspose.Slides لمرجع API للغة C++
description: يرجع جميع تعليقات الشريحة التي أضيفت من قبل مؤلف محدد.
type: docs
weight: 118
url: /ar/aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) طريقة

يرجع جميع تعليقات الشريحة التي أضيفت من قبل مؤلف محدد.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | مؤلف التعليقات للبحث عنها أو null لإرجاع جميع التعليقات. |

### قيمة الإرجاع

مصفوفة من [IComment](../../icomment/).

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IComment](../../icomment/)
* فئة [ICommentAuthor](../../icommentauthor/)
* فئة [ISlide](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)