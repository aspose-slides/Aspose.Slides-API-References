---
title: AddComment()
second_title: Aspose.Slides för C++ API-referens
description: Lägg till en ny kommentar i slutet av en samling.
type: docs
weight: 14
url: /sv/aspose.slides/icommentcollection/addcomment/
---
## ICommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) metod

Lägg till en ny kommentar i slutet av en samling.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Vanlig text för en ny kommentar. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) i en presentation där en ny kommentar ska läggas till. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position på en bild där en ny kommentar ska läggas till. |
| creationTime | [System::DateTime](../../../system/datetime/) | Tid för skapandet av en kommentar. |

### Returvärde

Tillagd kommentar.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IComment](../../icomment/)
* Klass [String](../../../system/string/)
* Klass [ISlide](../../islide/)
* Klass [PointF](../../../system.drawing/pointf/)
* Klass [DateTime](../../../system/datetime/)
* Klass [ICommentCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)