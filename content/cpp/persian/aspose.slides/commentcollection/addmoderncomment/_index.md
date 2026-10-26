---
title: AddModernComment()
second_title: مرجع API Aspose.Slides برای C++
description: یک نظر مدرن جدید را در انتهای یک مجموعه اضافه می‌کند.
type: docs
weight: 66
url: /fa/aspose.slides/commentcollection/addmoderncomment/
---
## CommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) متد

یک نظر مدرن جدید را در انتهای مجموعه اضافه کنید.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | متن ساده یک نظر مدرن جدید. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) در ارائه‌ای که قرار است یک نظر مدرن جدید به آن اضافه شود. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) روی اسلایدی که یک نظر مدرن جدید به آن مرتبط است. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | موقعیت روی اسلایدی که قرار است یک نظر مدرن جدید به آن اضافه شود. |
| creationTime | [System::DateTime](../../../system/datetime/) | زمان ایجاد یک نظر مدرن. |

### مقدار بازگشتی

نظر مدرن اضافه شد.
## توضیحات

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IModernComment](../../imoderncomment/)
* کلاس [String](../../../system/string/)
* کلاس [ISlide](../../islide/)
* کلاس [IShape](../../ishape/)
* کلاس [PointF](../../../system.drawing/pointf/)
* کلاس [DateTime](../../../system/datetime/)
* کلاس [CommentCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)