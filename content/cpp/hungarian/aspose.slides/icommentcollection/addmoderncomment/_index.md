---
title: AddModernComment()
second_title: Aspose.Slides C++ API referencia
description: Új modern megjegyzést ad a gyűjtemény végéhez.
type: docs
weight: 27
url: /hu/aspose.slides/icommentcollection/addmoderncomment/
---
## ICommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) metódus


Új modern megjegyzést ad a gyűjtemény végéhez.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Az új modern megjegyzés egyszerű szövege. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) egy prezentációban, ahol új modern megjegyzést adunk hozzá. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) egy dián, amelyhez egy új modern megjegyzés kapcsolódik. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozíció egy dián, ahol új modern megjegyzést adunk hozzá. |
| creationTime | [System::DateTime](../../../system/datetime/) | Az új modern megjegyzés létrehozásának ideje. |

### Visszatérési érték

Hozzáadott modern megjegyzés.
## Megjegyzések




```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IModernComment](../../imoderncomment/)
* Osztály [String](../../../system/string/)
* Osztály [ISlide](../../islide/)
* Osztály [IShape](../../ishape/)
* Osztály [PointF](../../../system.drawing/pointf/)
* Osztály [DateTime](../../../system/datetime/)
* Osztály [ICommentCollection](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)