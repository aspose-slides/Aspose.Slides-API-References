---
title: AddModernComment()
second_title: Aspose.Slides för C++ API-referens
description: Lägg till en ny modern kommentar i slutet av en samling.
type: docs
weight: 66
url: /sv/aspose.slides/commentcollection/addmoderncomment/
---
## CommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) metod


Lägg till en ny modern kommentar i slutet av en samling.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Vanlig text för en ny modern kommentar. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) i en presentation där en ny modern kommentar ska läggas till. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) på en bild som en ny modern kommentar är associerad med. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position på en bild där en ny modern kommentar ska läggas till. |
| creationTime | [System::DateTime](../../../system/datetime/) | Tid för skapandet av en modern kommentar. |

### Returvärde

Tillagd modern kommentar.
## Anmärkningar




```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IModernComment](../../imoderncomment/)
* Klass [String](../../../system/string/)
* Klass [ISlide](../../islide/)
* Klass [IShape](../../ishape/)
* Klass [PointF](../../../system.drawing/pointf/)
* Klass [DateTime](../../../system/datetime/)
* Klass [CommentCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)