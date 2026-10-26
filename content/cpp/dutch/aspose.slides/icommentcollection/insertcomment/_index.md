---
title: InsertComment()
second_title: Aspose.Slides voor C++ API-referentie
description: Voeg een nieuwe opmerking toe aan een collectie op de opgegeven index.
type: docs
weight: 40
url: /nl/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method


Voeg een nieuwe opmerking toe aan een collectie op de opgegeven index.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Index van het element in een collectie waarop de opmerking moet worden ingevoegd. |
| text | [System::String](../../../system/string/) | Platte tekst van een nieuwe opmerking. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in een presentatie waar een nieuwe opmerking moet worden toegevoegd. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Positie op een dia waar een nieuwe opmerking moet worden toegevoegd. |
| creationTime | [System::DateTime](../../../system/datetime/) | Tijd van het aanmaken van een opmerking. |

### Retourwaarde

Ingevoegde opmerking.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IComment](../../icomment/)
* Klasse [String](../../../system/string/)
* Klasse [ISlide](../../islide/)
* Klasse [PointF](../../../system.drawing/pointf/)
* Klasse [DateTime](../../../system/datetime/)
* Klasse [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)