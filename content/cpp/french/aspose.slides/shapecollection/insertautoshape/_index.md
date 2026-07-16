---
title: InsertAutoShape()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une nouvelle forme automatique et l'insère dans la collection de formes à l'indice spécifié, en appliquant le formatage du modèle par défaut.
type: docs
weight: 378
url: /fr/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) méthode

Crée une nouvelle forme automatique et l’insère dans la collection de formes à l’indice spécifié, en appliquant le formatage du modèle par défaut.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’indice basé sur zéro à laquelle insérer la nouvelle forme automatique. |
| shapeType | [ShapeType](../../shapetype/) | Le [ShapeType](../../shapetype/) de la forme automatique à insérer. |
| x | **float** | La coordonnée x du cadre de la forme, en points. |
| y | **float** | La coordonnée y du cadre de la forme, en points. |
| width | **float** | La largeur du cadre de la forme, en points. |
| height | **float** | La hauteur du cadre de la forme, en points. |

### Valeur de retour

Le [IAutoShape](../../iautoshape/) nouvellement créé.

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) méthode

Crée une nouvelle forme automatique et l’insère dans la collection de formes à l’indice spécifié, en l’initialisant éventuellement avec le style de modèle par défaut.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’indice basé sur zéro à laquelle insérer la forme automatique. |
| shapeType | [ShapeType](../../shapetype/) | Le [ShapeType](../../shapetype/) de la forme automatique à insérer. |
| x | **float** | La coordonnée x du cadre de la forme, en points. |
| y | **float** | La coordonnée y du cadre de la forme, en points. |
| width | **float** | La largeur du cadre de la forme, en points. |
| height | **float** | La hauteur du cadre de la forme, en points. |
| createFromTemplate | **bool** | Vrai pour appliquer le style de modèle par défaut (incluant un nom non vide, un style simple et un texte centré) ; faux pour créer la forme avec toutes les propriétés définies à leurs valeurs par défaut. |

### Valeur de retour

Le [IAutoShape](../../iautoshape/) nouvellement créé.

## Voir aussi

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)