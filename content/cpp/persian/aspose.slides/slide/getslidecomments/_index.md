---
title: GetSlideComments()
second_title: Aspose.Slides برای مرجع API C++
description: تمام نظرات اسلاید اضافه‌شده توسط نویسنده خاص را برمی‌گرداند.
type: docs
weight: 209
url: /fa/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) متد

تمام نظرات اسلاید اضافه‌شده توسط نویسنده خاص را برمی‌گرداند.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | نویسندهٔ نظرات برای جستجو یا null برای برگرداندن همه نظرات. |

### مقدار بازگشتی

آرایه‌ای از [Comment](../../comment/).

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IComment](../../icomment/)
* کلاس [ICommentAuthor](../../icommentauthor/)
* کلاس [Slide](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)