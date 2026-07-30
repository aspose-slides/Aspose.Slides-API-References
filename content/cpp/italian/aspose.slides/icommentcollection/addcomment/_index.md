---
title: AddComment()
second_title: Riferimento API Aspose.Slides per C++
description: Aggiunge un nuovo commento alla fine di una raccolta.
type: docs
weight: 14
url: /it/aspose.slides/icommentcollection/addcomment/
---
## ICommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) metodo

Aggiunge un nuovo commento alla fine di una raccolta.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Testo semplice di un nuovo commento. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in una presentazione in cui aggiungere un nuovo commento. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posizione su una diapositiva in cui aggiungere un nuovo commento. |
| creationTime | [System::DateTime](../../../system/datetime/) | Tempo di creazione di un commento. |

### Valore di ritorno

Commento aggiunto.

## Vedi anche

* Definizione di tipo [SharedPtr](../../../system/sharedptr/)
* Classe [IComment](../../icomment/)
* Classe [String](../../../system/string/)
* Classe [ISlide](../../islide/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [DateTime](../../../system/datetime/)
* Classe [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)