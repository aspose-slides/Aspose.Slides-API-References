---
title: InsertModernComment()
second_title: Aspose.Slides för C++ API-referens
description: Infoga en ny modern kommentar i en samling på det angivna indexet.
type: docs
weight: 53
url: /sv/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) metod

Infoga en ny modern kommentar i en samling på det angivna indexet.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Index för elementet i en samling där den moderna kommentaren ska infogas. |
| text | [System::String](../../../system/string/) | Vanlig text för en ny modern kommentar. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) i en presentation där en ny modern kommentar ska läggas till. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) på en bild som en ny modern kommentar är associerad med. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position på en bild där en ny modern kommentar ska läggas till. |
| creationTime | [System::DateTime](../../../system/datetime/) | Tid för skapandet av en modern kommentar. |

### Returvärde

Infogad modern kommentar.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IModernComment](../../imoderncomment/)
* Klass [String](../../../system/string/)
* Klass [ISlide](../../islide/)
* Klass [IShape](../../ishape/)
* Klass [PointF](../../../system.drawing/pointf/)
* Klass [DateTime](../../../system/datetime/)
* Klass [ICommentCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)