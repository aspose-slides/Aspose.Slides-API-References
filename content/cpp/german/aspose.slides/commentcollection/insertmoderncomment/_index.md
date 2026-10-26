---
title: InsertModernComment()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt einen neuen modernen Kommentar zu einer Sammlung an dem angegebenen Index ein.
type: docs
weight: 92
url: /de/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) Methode

Fügt einen neuen modernen Kommentar zu einer Sammlung an der angegebenen Position ein.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Index des Elements in einer Sammlung, an dem der moderne Kommentar eingefügt werden soll. |
| text | [System::String](../../../system/string/) | Klartext eines neuen modernen Kommentars. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in einer Präsentation, in der ein neuer moderner Kommentar hinzugefügt werden soll. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) auf einer Folie, mit der ein neuer moderner Kommentar verknüpft ist. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position auf einer Folie, an der ein neuer moderner Kommentar hinzugefügt werden soll. |
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
* Klasse [CommentCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)