---
title: AddAutoShape()
second_title: Référence API Aspose.Slides for C++
description: Crée une nouvelle forme auto avec un formatage par défaut et l’ajoute à la fin de la collection de formes.
type: docs
weight: 352
url: /fr/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) méthode

Crée une nouvelle forme automatique avec un formatage par défaut et l'ajoute à la fin de la collection de formes.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Le [ShapeType](../../shapetype/) de la forme automatique à ajouter. |
| x | **float** | La coordonnée x du cadre de la forme, en points. |
| y | **float** | La coordonnée y du cadre de la forme, en points. |
| width | **float** | La largeur du cadre de la forme, en points. |
| height | **float** | La hauteur du cadre de la forme, en points. |

### Valeur de retour

Le [IAutoShape](../../iautoshape/) nouvellement créé.

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) méthode

Crée une nouvelle forme automatique et l'ajoute à la fin de la collection de formes, en initialisant éventuellement avec le formatage de modèle par défaut.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Le [ShapeType](../../shapetype/) de la forme automatique à ajouter. |
| x | **float** | La coordonnée x du cadre de la forme, en points. |
| y | **float** | La coordonnée y du cadre de la forme, en points. |
| width | **float** | La largeur du cadre de la forme, en points. |
| height | **float** | La hauteur du cadre de la forme, en points. |
| createFromTemplate | **bool** | True pour appliquer le style de modèle par défaut (style simple, texte centré et nom non vide) à la nouvelle forme ; false pour créer la forme avec toutes les propriétés définies à leurs valeurs par défaut. |

### Valeur de retour

Le [IAutoShape](../../iautoshape/) nouvellement créé.

## Voir aussi

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [ShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)