---
title: AddComment()
second_title: Aspose.Slides voor C++ API-referentie
description: Voeg een nieuw commentaar toe aan het einde van een collectie.
type: docs
weight: 14
url: /nl/aspose.slides/icommentcollection/addcomment/
---
## ICommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) methode


Voeg een nieuw commentaar toe aan het einde van een collectie.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Platte tekst van een nieuw commentaar. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in een presentatie waar een nieuw commentaar moet worden toegevoegd. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Positie op een dia waar een nieuw commentaar moet worden toegevoegd. |
| creationTime | [System::DateTime](../../../system/datetime/) | Tijd van een commentaarcreatie. |

### Retourwaarde

Toegevoegd commentaar.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IComment](../../icomment/)
* Klasse [String](../../../system/string/)
* Klasse [ISlide](../../islide/)
* Klasse [PointF](../../../system.drawing/pointf/)
* Klasse [DateTime](../../../system/datetime/)
* Klasse [ICommentCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)