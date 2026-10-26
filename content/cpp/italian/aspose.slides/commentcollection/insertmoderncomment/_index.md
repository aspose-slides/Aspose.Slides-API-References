---
title: InsertModernComment()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisci un nuovo commento moderno in una collezione all'indice specificato.
type: docs
weight: 92
url: /it/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method


Inserisci un nuovo commento moderno in una collezione all'indice specificato.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Index of the element in a collection at which modern comment should be inserted. |
| text | [System::String](../../../system/string/) | Testo semplice di un nuovo commento moderno. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in una presentazione in cui aggiungere un nuovo commento moderno. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) su una diapositiva a cui è associato un nuovo commento moderno. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posizione su una diapositiva dove aggiungere un nuovo commento moderno. |
| creationTime | [System::DateTime](../../../system/datetime/) | Orario di creazione di un commento moderno. |

### Valore restituito

Commento moderno inserito.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IModernComment](../../imoderncomment/)
* Classe [String](../../../system/string/)
* Classe [ISlide](../../islide/)
* Classe [IShape](../../ishape/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [DateTime](../../../system/datetime/)
* Classe [CommentCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)