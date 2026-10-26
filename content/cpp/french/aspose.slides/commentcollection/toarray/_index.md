---
title: ToArray()
second_title: Référence API Aspose.Slides pour C++
description: Crée et renvoie un tableau contenant tous les commentaires.
type: docs
weight: 105
url: /fr/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() méthode


Crée et renvoie un tableau contenant tous les commentaires.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```


### Valeur de retour

Tableau de [Comment](../../comment/).

## CommentCollection::ToArray(int32_t, int32_t) méthode


Crée et renvoie un tableau contenant tous les commentaires de la plage spécifiée.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | Un indice du premier commentaire à renvoyer. |
| count | **int32_t** | Un nombre de commentaires à renvoyer. |

### Valeur de retour

Tableau de [Comment](../../comment/).

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComment](../../icomment/)
* Classe [CommentCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)