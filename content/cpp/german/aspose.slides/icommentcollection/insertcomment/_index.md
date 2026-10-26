---
title: InsertComment()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt einen neuen Kommentar zu einer Sammlung am angegebenen Index ein.
type: docs
weight: 40
url: /de/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) Methode

Fügt einen neuen Kommentar zu einer Sammlung am angegebenen Index ein.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Index des Elements in einer Sammlung, an dem der Kommentar eingefügt werden soll. |
| text | [System::String](../../../system/string/) | Klartext eines neuen Kommentars. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in einer Präsentation, in der ein neuer Kommentar hinzugefügt werden soll. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position auf einer Folie, an der ein neuer Kommentar hinzugefügt werden soll. |
| creationTime | [System::DateTime](../../../system/datetime/) | Zeit der Erstellung eines Kommentars. |

### Rückgabewert

Eingefügter Kommentar.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)