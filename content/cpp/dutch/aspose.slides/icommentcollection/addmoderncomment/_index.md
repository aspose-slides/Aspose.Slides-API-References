---
title: AddModernComment()
second_title: Aspose.Slides voor C++ API-referentie
description: Voeg een nieuwe moderne opmerking toe aan het einde van een collectie.
type: docs
weight: 27
url: /nl/aspose.slides/icommentcollection/addmoderncomment/
---
## ICommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method

Voeg een nieuwe moderne opmerking toe aan het einde van een collectie.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Platte tekst van een nieuwe moderne opmerking. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in een presentatie waarin een nieuwe moderne opmerking moet worden toegevoegd. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) op een dia waaraan een nieuwe moderne opmerking is gekoppeld. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Positie op een dia waar een nieuwe moderne opmerking moet worden toegevoegd. |
| creationTime | [System::DateTime](../../../system/datetime/) | Tijdstip van het aanmaken van een moderne opmerking. |

### Retourwaarde

Toegevoegde moderne opmerking.
## Opmerkingen

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IModernComment](../../imoderncomment/)
* Klasse [String](../../../system/string/)
* Klasse [ISlide](../../islide/)
* Klasse [IShape](../../ishape/)
* Klasse [PointF](../../../system.drawing/pointf/)
* Klasse [DateTime](../../../system/datetime/)
* Klasse [ICommentCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)