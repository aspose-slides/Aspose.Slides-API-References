---
title: InsertAutoShape()
second_title: Référence API Aspose.Slides pour C++
description: Crée une nouvelle forme auto et l’insère dans la collection de formes à l’indice spécifié, en appliquant le formatage de modèle par défaut.
type: docs
weight: 339
url: /fr/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) method

Crée une nouvelle forme auto et l’insère dans la collection de formes à l’indice spécifié, en appliquant le formatage de modèle par défaut.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’indice basé sur zéro à laquelle insérer la nouvelle forme auto. |
| shapeType | [ShapeType](../../shapetype/) | Le [ShapeType](../../shapetype/) de la forme auto à insérer. |
| x | **float** | La coordonnée x du cadre de la forme, en points. |
| y | **float** | La coordonnée y du cadre de la forme, en points. |
| width | **float** | La largeur du cadre de la forme, en points. |
| height | **float** | La hauteur du cadre de la forme, en points. |

### Valeur de retour

Le [IAutoShape](../../iautoshape/) nouvellement créé.

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) method

Crée une nouvelle forme auto et l’insère dans la collection de formes à l’indice spécifié, en initialisant éventuellement avec le style de modèle par défaut.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’indice basé sur zéro à laquelle insérer la forme auto. |
| shapeType | [ShapeType](../../shapetype/) | Le [ShapeType](../../shapetype/) de la forme auto à insérer. |
| x | **float** | La coordonnée x du cadre de la forme, en points. |
| y | **float** | La coordonnée y du cadre de la forme, en points. |
| width | **float** | La largeur du cadre de la forme, en points. |
| height | **float** | La hauteur du cadre de la forme, en points. |
| createFromTemplate | **bool** | True pour appliquer le style de modèle par défaut (y compris un nom non vide, un style simple et du texte centré) ; false pour créer la forme avec toutes les propriétés définies à leurs valeurs par défaut. |

### Valeur de retour

Le [IAutoShape](../../iautoshape/) nouvellement créé.

## Voir aussi

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)