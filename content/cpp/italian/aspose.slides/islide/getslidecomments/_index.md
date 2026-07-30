---
title: GetSlideComments()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce tutti i commenti della diapositiva aggiunti da uno specifico autore.
type: docs
weight: 118
url: /it/aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) metodo

Restituisce tutti i commenti della diapositiva aggiunti da un autore specifico.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Autore dei commenti da trovare o null per restituire tutti i commenti. |

### Valore di ritorno

Array di [IComment](../../icomment/).

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComment](../../icomment/)
* Classe [ICommentAuthor](../../icommentauthor/)
* Classe [ISlide](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)