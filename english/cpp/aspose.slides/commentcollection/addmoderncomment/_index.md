---
title: AddModernComment()
second_title: Aspose.Slides for C++ API Reference
description: Add new modern comment at the end of a collection.
type: docs
weight: 66
url: /cpp/aspose.slides/commentcollection/addmoderncomment/
---
## CommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method


Add new modern comment at the end of a collection.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Plain text of a new modern comment. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in a presentation where to add a new modern comment. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) on a slide to which a new modern comment is associated. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position on a slide where to add a new modern comment. |
| creationTime | [System::DateTime](../../../system/datetime/) | Time of a modern comment creation. |

### Return Value

Added modern comment.
## Remarks




```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IModernComment](../../imoderncomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [IShape](../../ishape/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [CommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)