---
title: AddAutoShape()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une nouvelle forme auto avec le formatage par défaut et l'ajoute à la fin de la collection de formes.
type: docs
weight: 313
url: /fr/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) méthode


Crée une nouvelle forme auto avec le formatage par défaut et l’ajoute à la fin de la collection de formes.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Le [ShapeType](../../shapetype/) de la forme auto à ajouter. |
| x | **float** | La coordonnée x du cadre de la forme, en points. |
| y | **float** | La coordonnée y du cadre de la forme, en points. |
| width | **float** | La largeur du cadre de la forme, en points. |
| height | **float** | La hauteur du cadre de la forme, en points. |

### Valeur de retour

Le [IAutoShape](../../iautoshape/) nouvellement créé.

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) méthode


Crée une nouvelle forme auto et l’ajoute à la fin de la collection de formes, en l’initialisant éventuellement avec le formatage de modèle par défaut.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Le [ShapeType](../../shapetype/) de la forme auto à ajouter. |
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
* Class [IAutoShape](../../iautoshape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)