---
title: InsertModernComment()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce un nuovo commento moderno in una collezione all'indice specificato.
type: docs
weight: 53
url: /it/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) metodo

Inserisci un nuovo commento moderno in una collezione all'indice specificato.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Indice dell'elemento in una collezione in cui dovrebbe essere inserito il commento moderno. |
| text | [System::String](../../../system/string/) | Testo semplice di un nuovo commento moderno. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in una presentazione dove aggiungere un nuovo commento moderno. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) su una diapositiva a cui è associato un nuovo commento moderno. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posizione su una diapositiva dove aggiungere un nuovo commento moderno. |
| creationTime | [System::DateTime](../../../system/datetime/) | Tempo di creazione di un commento moderno. |

### Valore di ritorno

Commento moderno inserito.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IModernComment](../../imoderncomment/)
* Classe [String](../../../system/string/)
* Classe [ISlide](../../islide/)
* Classe [IShape](../../ishape/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [DateTime](../../../system/datetime/)
* Classe [ICommentCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)