---
title: AddModernComment()
second_title: Riferimento API Aspose.Slides per C++
description: Aggiunge un nuovo commento moderno alla fine di una collezione.
type: docs
weight: 66
url: /it/aspose.slides/commentcollection/addmoderncomment/
---
## CommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method

Aggiunge un nuovo commento moderno alla fine di una collezione.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Testo semplice di un nuovo commento moderno. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in una presentazione dove aggiungere un nuovo commento moderno. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) su una diapositiva a cui è associato un nuovo commento moderno. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posizione su una diapositiva dove aggiungere un nuovo commento moderno. |
| creationTime | [System::DateTime](../../../system/datetime/) | Ora di creazione di un commento moderno. |

### Valore di ritorno

Commento moderno aggiunto.
## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IModernComment](../../imoderncomment/)
* Classe [String](../../../system/string/)
* Classe [ISlide](../../islide/)
* Classe [IShape](../../ishape/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [DateTime](../../../system/datetime/)
* Classe [CommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)