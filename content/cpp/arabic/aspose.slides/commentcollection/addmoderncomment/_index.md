---
title: AddModernComment()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إضافة تعليق حديث جديد في نهاية مجموعة.
type: docs
weight: 66
url: /ar/aspose.slides/commentcollection/addmoderncomment/
---
## CommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) طريقة

أضف تعليقًا حديثًا جديدًا في نهاية مجموعة.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | نص عادي لتعليق حديث جديد. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) في عرض تقديمي حيث يتم إضافة تعليق حديث جديد. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) على شريحة يتم ربط تعليق حديث جديد بها. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | الموقع على شريحة حيث يتم إضافة تعليق حديث جديد. |
| creationTime | [System::DateTime](../../../system/datetime/) | وقت إنشاء التعليق الحديث. |

### قيمة الإرجاع

تم إضافة التعليق الحديث.

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
* فئة [CommentCollection](../)
* نطاق الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)