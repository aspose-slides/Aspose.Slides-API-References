---
title: AddComment()
second_title: Aspose.Slides voor C++ API-referentie
description: Voeg een nieuwe opmerking toe aan het einde van een collectie.
type: docs
weight: 53
url: /nl/aspose.slides/commentcollection/addcomment/
---
## CommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) methode

Voeg een nieuwe opmerking toe aan het einde van een collectie.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Platte tekst van een nieuwe opmerking. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in een presentatie waarin een nieuwe opmerking moet worden toegevoegd. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Positie op een dia waar een nieuwe opmerking moet worden toegevoegd. |
| creationTime | [System::DateTime](../../../system/datetime/) | Tijd van het aanmaken van een opmerking. |

### Retourwaarde

Toegevoegde opmerking.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IComment](../../icomment/)
* Klasse [String](../../../system/string/)
* Klasse [ISlide](../../islide/)
* Klasse [PointF](../../../system.drawing/pointf/)
* Klasse [DateTime](../../../system/datetime/)
* Klasse [CommentCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)