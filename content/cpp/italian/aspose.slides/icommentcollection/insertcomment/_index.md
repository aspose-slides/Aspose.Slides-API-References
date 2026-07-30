---
title: InsertComment()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce un nuovo commento in una collezione all'indice specificato.
type: docs
weight: 40
url: /it/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) metodo

Inserisce un nuovo commento in una collezione all'indice specificato.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Indice dell'elemento in una collezione in cui il commento deve essere inserito. |
| text | [System::String](../../../system/string/) | Testo semplice di un nuovo commento. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in una presentazione dove aggiungere un nuovo commento. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posizione su una diapositiva in cui aggiungere un nuovo commento. |
| creationTime | [System::DateTime](../../../system/datetime/) | Ora di creazione del commento. |

### Valore restituito

Commento inserito.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComment](../../icomment/)
* Classe [String](../../../system/string/)
* Classe [ISlide](../../islide/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [DateTime](../../../system/datetime/)
* Classe [ICommentCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)