---
title: InsertComment()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt einen neuen Kommentar zu einer Sammlung an dem angegebenen Index ein.
type: docs
weight: 79
url: /de/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) Methode

Fügt einen neuen Kommentar in einer Sammlung an dem angegebenen Index ein.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Index des Elements in einer Sammlung, an dem der Kommentar eingefügt werden soll. |
| text | [System::String](../../../system/string/) | Klartext des neuen Kommentars. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in einer Präsentation, in der ein neuer Kommentar hinzugefügt werden soll. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position auf einer Folie, an der ein neuer Kommentar hinzugefügt werden soll. |
| creationTime | [System::DateTime](../../../system/datetime/) | Zeitpunkt der Erstellung eines Kommentars. |

### Rückgabewert

Eingefügter Kommentar.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IComment](../../icomment/)
* Klasse [String](../../../system/string/)
* Klasse [ISlide](../../islide/)
* Klasse [PointF](../../../system.drawing/pointf/)
* Klasse [DateTime](../../../system/datetime/)
* Klasse [CommentCollection](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)