---
title: InsertModernComment()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een nieuwe moderne opmerking toe aan een collectie op de opgegeven index.
type: docs
weight: 92
url: /nl/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) methode

Voegt een nieuwe moderne opmerking toe aan een collectie op de opgegeven index.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Index van het element in een collectie waarop de moderne opmerking moet worden ingevoegd. |
| text | [System::String](../../../system/string/) | Platte tekst van een nieuwe moderne opmerking. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in een presentatie waarin een nieuwe moderne opmerking moet worden toegevoegd. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) op een dia waaraan een nieuwe moderne opmerking is gekoppeld. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Positie op een dia waar een nieuwe moderne opmerking moet worden toegevoegd. |
| creationTime | [System::DateTime](../../../system/datetime/) | Tijdstip van de creatie van een moderne opmerking. |

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
* Klasse [CommentCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)