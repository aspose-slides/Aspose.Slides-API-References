---
title: AddModernComment()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt einen neuen modernen Kommentar am Ende einer Sammlung hinzu.
type: docs
weight: 66
url: /de/aspose.slides/commentcollection/addmoderncomment/
---
## CommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method

Fügt einen neuen modernen Kommentar am Ende einer Sammlung hinzu.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Einfacher Text eines neuen modernen Kommentars. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in einer Präsentation, in der ein neuer moderner Kommentar hinzugefügt werden soll. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) auf einer Folie, der ein neuer moderner Kommentar zugeordnet ist. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position auf einer Folie, an der ein neuer moderner Kommentar hinzugefügt wird. |
| creationTime | [System::DateTime](../../../system/datetime/) | Zeit der Erstellung eines modernen Kommentars. |

### Rückgabewert

Hinzugefügter moderner Kommentar.

## Anmerkungen

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

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