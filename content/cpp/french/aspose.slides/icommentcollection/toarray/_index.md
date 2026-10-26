---
title: ToArray()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée et renvoie un tableau contenant tous les commentaires.
type: docs
weight: 66
url: /fr/aspose.slides/icommentcollection/toarray/
---
## ICommentCollection::ToArray() méthode

Crée et renvoie un tableau contenant tous les commentaires.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray()=0
```

### Valeur de retour

Tableau de [IComment](../../icomment/).

## ICommentCollection::ToArray(int32_t, int32_t) méthode

Crée et renvoie un tableau contenant tous les commentaires de la plage spécifiée.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | Un indice du premier commentaire à renvoyer. |
| count | **int32_t** | Un nombre de commentaires à renvoyer. |

### Valeur de retour

Tableau de [IComment](../../icomment/).

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComment](../../icomment/)
* Classe [ICommentCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)