---
title: AddModernComment()
second_title: Aspose.Slides voor C++ API-referentie
description: Voeg een nieuw modern commentaar toe aan het einde van een collectie.
type: docs
weight: 66
url: /nl/aspose.slides/commentcollection/addmoderncomment/
---
## CommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method


Voeg een nieuw modern commentaar toe aan het einde van een collectie.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Platte tekst van een nieuw modern commentaar. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in een presentatie waar een nieuw modern commentaar moet worden toegevoegd. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) op een dia waaraan een nieuw modern commentaar is gekoppeld. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Positie op een dia waar een nieuw modern commentaar moet worden toegevoegd. |
| creationTime | [System::DateTime](../../../system/datetime/) | Tijd van het maken van een modern commentaar. |

### Retourwaarde

Added modern comment.

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
* Class [IModernComment](../../imoderncomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [IShape](../../ishape/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [CommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)