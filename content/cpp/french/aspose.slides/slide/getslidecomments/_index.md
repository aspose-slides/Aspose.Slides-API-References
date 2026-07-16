---
title: GetSlideComments()
second_title: Référence API Aspose.Slides for C++
description: Renvoie tous les commentaires de diapositive ajoutés par un auteur spécifique.
type: docs
weight: 209
url: /fr/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) méthode

Renvoie tous les commentaires de diapositive ajoutés par un auteur spécifique.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Auteur des commentaires à rechercher ou null pour renvoyer tous les commentaires. |

### Valeur de retour

Array of [Comment](../../comment/).

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComment](../../icomment/)
* Classe [ICommentAuthor](../../icommentauthor/)
* Classe [Slide](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)