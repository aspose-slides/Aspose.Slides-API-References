---
title: AddComment()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt einen neuen Kommentar am Ende einer Sammlung hinzu.
type: docs
weight: 53
url: /de/aspose.slides/commentcollection/addcomment/
---
## CommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) Methode

Fügt einen neuen Kommentar am Ende einer Sammlung hinzu.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Parameter

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Klartext eines neuen Kommentars. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in einer Präsentation, in der ein neuer Kommentar hinzugefügt werden soll. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position auf einer Folie, an der ein neuer Kommentar hinzugefügt werden soll. |
| creationTime | [System::DateTime](../../../system/datetime/) | Zeitpunkt der Erstellung eines Kommentars. |

### Rückgabewert

Hinzugefügter Kommentar.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [CommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)