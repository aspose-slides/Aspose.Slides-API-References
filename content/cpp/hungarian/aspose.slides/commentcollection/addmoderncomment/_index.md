---
title: AddModernComment()
second_title: Aspose.Slides C++ API referenciája
description: Új modern megjegyzés hozzáadása a gyűjtemény végén.
type: docs
weight: 66
url: /hu/aspose.slides/commentcollection/addmoderncomment/
---
## CommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) metódus


Új modern megjegyzés hozzáadása a gyűjtemény végéhez.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Az új modern megjegyzés egyszerű szövege. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) egy prezentációban, ahol új modern megjegyzést kell hozzáadni. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) egy dián, amelyhez új modern megjegyzés kapcsolódik. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozíció a dián, ahol új modern megjegyzést kell hozzáadni. |
| creationTime | [System::DateTime](../../../system/datetime/) | Egy modern megjegyzés létrehozásának időpontja. |

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

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IModernComment](../../imoderncomment/)
* Osztály [String](../../../system/string/)
* Osztály [ISlide](../../islide/)
* Osztály [IShape](../../ishape/)
* Osztály [PointF](../../../system.drawing/pointf/)
* Osztály [DateTime](../../../system/datetime/)
* Osztály [CommentCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)