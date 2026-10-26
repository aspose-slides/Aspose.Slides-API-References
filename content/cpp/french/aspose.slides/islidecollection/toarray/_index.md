---
title: ToArray()
second_title: Référence API Aspose.Slides for C++
description: Crée et renvoie un tableau contenant toutes les diapositives.
type: docs
weight: 92
url: /fr/aspose.slides/islidecollection/toarray/
---
## ISlideCollection::ToArray() méthode


Crée et renvoie un tableau contenant toutes les diapositives.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray()=0
```


### Valeur de retour

Tableau de [ISlide](../../islide/)

## ISlideCollection::ToArray(int32_t, int32_t) méthode


Crée et renvoie un tableau contenant toutes les diapositives de la plage spécifiée.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | Un indice de la première diapositive à ajouter. |
| count | **int32_t** | Un nombre de diapositives à ajouter. |

### Valeur de retour

Tableau de [ISlide](../../islide/)

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [ISlideCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)