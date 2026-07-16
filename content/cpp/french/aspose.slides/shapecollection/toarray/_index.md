---
title: ToArray()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée et renvoie un tableau qui contient toutes les formes.
type: docs
weight: 326
url: /fr/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() méthode

Crée et renvoie un tableau qui contient toutes les formes.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```

### Valeur de retour

Un tableau d'objets [IShape](../../ishape/).

## ShapeCollection::ToArray(int32_t, int32_t) méthode

Crée et renvoie un tableau qui contient toutes les formes dans la plage spécifiée.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | L'index de la première forme à renvoyer. |
| count | **int32_t** | Le nombre de formes à renvoyer. |

### Valeur de retour

Un tableau d'objets [IShape](../../ishape/).

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [ShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)