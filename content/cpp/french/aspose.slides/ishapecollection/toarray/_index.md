---
title: ToArray()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée et renvoie un tableau contenant toutes les formes.
type: docs
weight: 287
url: /fr/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() méthode


Crée et renvoie un tableau contenant toutes les formes.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```


### Valeur de retour

Un tableau d'objets [IShape](../../ishape/).

## IShapeCollection::ToArray(int32_t, int32_t) méthode


Crée et renvoie un tableau contenant toutes les formes dans la plage spécifiée.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | L'indice de la première forme à renvoyer. |
| count | **int32_t** | Le nombre de formes à renvoyer. |

### Valeur de retour

Un tableau d'objets [IShape](../../ishape/).

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [IShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)