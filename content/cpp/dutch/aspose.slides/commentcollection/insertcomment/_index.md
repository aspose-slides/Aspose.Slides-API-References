---
title: InsertComment()
second_title: Aspose.Slides voor C++ API-referentie
description: Voeg een nieuw commentaar toe aan een collectie op de opgegeven index.
type: docs
weight: 79
url: /nl/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) methode

Voegt een nieuw commentaar toe aan een collectie op de opgegeven index.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Index van het element in een collectie waarop het commentaar moet worden ingevoegd. |
| text | [System::String](../../../system/string/) | Platte tekst van een nieuw commentaar. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in een presentatie waar een nieuw commentaar moet worden toegevoegd. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Positie op een dia waar een nieuw commentaar moet worden toegevoegd. |
| creationTime | [System::DateTime](../../../system/datetime/) | Tijd van het aanmaken van een commentaar. |

### Retourwaarde

Toegevoegd commentaar.

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