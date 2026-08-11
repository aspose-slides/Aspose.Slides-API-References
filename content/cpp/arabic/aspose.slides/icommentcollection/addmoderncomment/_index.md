---
title: AddModernComment()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إضافة تعليق حديث جديد في نهاية مجموعة.
type: docs
weight: 27
url: /ar/aspose.slides/icommentcollection/addmoderncomment/
---
## ICommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) طريقة

إضافة تعليق حديث جديد في نهاية مجموعة.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | النص العادي لتعليق حديث جديد. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) في عرض تقديمي حيث يتم إضافة تعليق حديث جديد. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) على شريحة يرتبط بها تعليق حديث جديد. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | الموضع على شريحة حيث يتم إضافة تعليق حديث جديد. |
| creationTime | [System::DateTime](../../../system/datetime/) | وقت إنشاء التعليق الحديث. |

### قيمة الإرجاع

تمت إضافة التعليق الحديث.

## ملاحظات


```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```


## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IModernComment](../../imoderncomment/)
* فئة [String](../../../system/string/)
* فئة [ISlide](../../islide/)
* فئة [IShape](../../ishape/)
* فئة [PointF](../../../system.drawing/pointf/)
* فئة [DateTime](../../../system/datetime/)
* فئة [ICommentCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)