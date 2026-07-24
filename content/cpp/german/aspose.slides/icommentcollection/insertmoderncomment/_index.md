---
title: InsertModernComment()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt einen neuen modernen Kommentar zu einer Sammlung am angegebenen Index ein.
type: docs
weight: 53
url: /de/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) Methode

Fügt einen neuen modernen Kommentar zu einer Sammlung an der angegebenen Position ein.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Index des Elements in einer Sammlung, an der der moderne Kommentar eingefügt werden soll. |
| text | [System::String](../../../system/string/) | Klartext des neuen modernen Kommentars. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in einer Präsentation, in der ein neuer moderner Kommentar hinzugefügt wird. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) auf einer Folie, der ein neuer moderner Kommentar zugeordnet ist. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position auf einer Folie, an der ein neuer moderner Kommentar hinzugefügt wird. |
| creationTime | [System::DateTime](../../../system/datetime/) | Zeitpunkt der Erstellung eines modernen Kommentars. |

### Rückgabewert

Eingefügter moderner Kommentar.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IModernComment](../../imoderncomment/)
* Klasse [String](../../../system/string/)
* Klasse [ISlide](../../islide/)
* Klasse [IShape](../../ishape/)
* Klasse [PointF](../../../system.drawing/pointf/)
* Klasse [DateTime](../../../system/datetime/)
* Klasse [ICommentCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)