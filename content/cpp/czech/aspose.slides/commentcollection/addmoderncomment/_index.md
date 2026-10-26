---
title: AddModernComment()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Přidá nový moderní komentář na konec kolekce.
type: docs
weight: 66
url: /cs/aspose.slides/commentcollection/addmoderncomment/
---
## CommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) metoda

Přidá nový moderní komentář na konec kolekce.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Prostý text nového moderního komentáře. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) v prezentaci, kde se má přidat nový moderní komentář. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) na snímku, ke kterému je nový moderní komentář přiřazen. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozice na snímku, kde se má přidat nový moderní komentář. |
| creationTime | [System::DateTime](../../../system/datetime/) | Čas vytvoření moderního komentáře. |

### Návratová hodnota

Přidán moderní komentář.

## Poznámky




```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IModernComment](../../imoderncomment/)
* Třída [String](../../../system/string/)
* Třída [ISlide](../../islide/)
* Třída [IShape](../../ishape/)
* Třída [PointF](../../../system.drawing/pointf/)
* Třída [DateTime](../../../system/datetime/)
* Třída [CommentCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)