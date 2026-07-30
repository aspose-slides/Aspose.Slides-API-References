---
title: AddComment()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge un nuovo commento alla fine di una raccolta.
type: docs
weight: 53
url: /it/aspose.slides/commentcollection/addcomment/
---
## CommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) metodo

Aggiunge un nuovo commento alla fine di una raccolta.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Testo semplice di un nuovo commento. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in una presentazione dove aggiungere un nuovo commento. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posizione su una diapositiva dove aggiungere un nuovo commento. |
| creationTime | [System::DateTime](../../../system/datetime/) | Tempo di creazione di un commento. |

### Valore di ritorno

Commento aggiunto.

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