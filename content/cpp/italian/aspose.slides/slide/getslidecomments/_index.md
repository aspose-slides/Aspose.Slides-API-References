---
title: GetSlideComments()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce tutti i commenti della diapositiva aggiunti da un autore specifico.
type: docs
weight: 209
url: /it/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) metodo

Restituisce tutti i commenti della diapositiva aggiunti da un autore specifico.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Autore dei commenti da trovare o null per restituire tutti i commenti. |

### Valore di ritorno

Array di [Comment](../../comment/).

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComment](../../icomment/)
* Classe [ICommentAuthor](../../icommentauthor/)
* Classe [Slide](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)