---
title: InsertComment()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce un nuovo commento in una collezione all'indice specificato.
type: docs
weight: 79
url: /it/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) metodo

Inserisce un nuovo commento in una collezione all'indice specificato.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Indice dell'elemento in una collezione al quale il commento deve essere inserito. |
| text | [System::String](../../../system/string/) | Testo semplice di un nuovo commento. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in una presentazione in cui aggiungere un nuovo commento. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posizione su una diapositiva in cui aggiungere un nuovo commento. |
| creationTime | [System::DateTime](../../../system/datetime/) | Ora di creazione di un commento. |

### Valore di ritorno

Commento inserito.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComment](../../icomment/)
* Classe [String](../../../system/string/)
* Classe [ISlide](../../islide/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [DateTime](../../../system/datetime/)
* Classe [CommentCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)