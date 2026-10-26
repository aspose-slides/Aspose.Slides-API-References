---
title: InsertModernComment()
second_title: Aspose.Slides voor C++ API-referentie
description: Voeg een nieuwe moderne opmerking toe aan een verzameling op de opgegeven index.
type: docs
weight: 53
url: /nl/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) methode

Voeg een nieuwe moderne opmerking toe aan een verzameling op de opgegeven index.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Index van het element in een verzameling waarop een moderne opmerking moet worden ingevoegd. |
| text | [System::String](../../../system/string/) | Platte tekst van een nieuwe moderne opmerking. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in een presentatie waar een nieuwe moderne opmerking moet worden toegevoegd. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) op een dia waaraan een nieuwe moderne opmerking is gekoppeld. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Positie op een dia waar een nieuwe moderne opmerking moet worden toegevoegd. |
| creationTime | [System::DateTime](../../../system/datetime/) | Tijdstip van het aanmaken van een moderne opmerking. |

### Retourwaarde

Ingevoegde moderne opmerking.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IModernComment](../../imoderncomment/)
* Klasse [String](../../../system/string/)
* Klasse [ISlide](../../islide/)
* Klasse [IShape](../../ishape/)
* Klasse [PointF](../../../system.drawing/pointf/)
* Klasse [DateTime](../../../system/datetime/)
* Klasse [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)