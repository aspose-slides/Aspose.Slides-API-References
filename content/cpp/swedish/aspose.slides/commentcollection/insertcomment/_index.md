---
title: InsertComment()
second_title: Aspose.Slides för C++ API-referens
description: Infoga en ny kommentar i en samling på det angivna indexet.
type: docs
weight: 79
url: /sv/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) metod

Infoga en ny kommentar i en samling på det angivna indexet.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Index för elementet i en samling där kommentaren ska infogas. |
| text | [System::String](../../../system/string/) | Ren text för en ny kommentar. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) i en presentation där en ny kommentar ska läggas till. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position på en bild där en ny kommentar ska läggas till. |
| creationTime | [System::DateTime](../../../system/datetime/) | Tid för skapandet av kommentaren. |

### Returvärde

Infogad kommentar.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IComment](../../icomment/)
* Klass [String](../../../system/string/)
* Klass [ISlide](../../islide/)
* Klass [PointF](../../../system.drawing/pointf/)
* Klass [DateTime](../../../system/datetime/)
* Klass [CommentCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)