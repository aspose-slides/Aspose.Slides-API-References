---
title: AddComment()
second_title: Aspose.Slides för C++ API-referens
description: Lägg till en ny kommentar i slutet av en samling.
type: docs
weight: 53
url: /sv/aspose.slides/commentcollection/addcomment/
---
## CommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) metod

Lägg till en ny kommentar i slutet av en samling.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Vanlig text för en ny kommentar. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) i en presentation där du ska lägga till en ny kommentar. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position på en slide där du ska lägga till en ny kommentar. |
| creationTime | [System::DateTime](../../../system/datetime/) | Tid för en kommentarskapning. |

## Returvärde

Tillagd kommentar.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [CommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)