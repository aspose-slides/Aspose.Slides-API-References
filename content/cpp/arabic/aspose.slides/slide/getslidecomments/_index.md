---
title: GetSlideComments()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: يرجّع جميع تعليقات الشريحة التي أضيفت بواسطة مؤلف محدد.
type: docs
weight: 209
url: /ar/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) الطريقة

يرجع جميع تعليقات الشريحة التي أضيفت بواسطة مؤلف محدد.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | مؤلف التعليقات للبحث عنها أو null لاسترجاع جميع التعليقات. |

### قيمة الإرجاع

مصفوفة من [Comment](../../comment/).

## انظر أيضاً

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IComment](../../icomment/)
* فئة [ICommentAuthor](../../icommentauthor/)
* فئة [Slide](../)
* نطاق اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)