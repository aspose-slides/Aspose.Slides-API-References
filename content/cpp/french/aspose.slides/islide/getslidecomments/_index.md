---
title: GetSlideComments()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie tous les commentaires de diapositive ajoutés par un auteur spécifique.
type: docs
weight: 118
url: /fr/aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) méthode


Renvoie tous les commentaires de diapositive ajoutés par un auteur spécifique.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Auteur des commentaires à rechercher ou null pour renvoyer tous les commentaires. |

### Valeur de retour

Tableau de [IComment](../../icomment/).

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComment](../../icomment/)
* Classe [ICommentAuthor](../../icommentauthor/)
* Classe [ISlide](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)