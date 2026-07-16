---
title: InsertConnector()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une nouvelle forme de connecteur et l'insère dans la collection de formes à l'indice spécifié, en appliquant le style de modèle par défaut.
type: docs
weight: 391
url: /fr/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) méthode


Crée une nouvelle forme de connecteur et l’insère dans la collection de formes à l’indice spécifié, en appliquant le style de modèle par défaut.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’indice basé sur zéro où insérer la forme de connecteur. |
| shapeType | [ShapeType](../../shapetype/) | Le [ShapeType](../../shapetype/) de la forme de connecteur à insérer. |
| x | **float** | La coordonnée x du cadre du connecteur, en points. |
| y | **float** | La coordonnée y du cadre du connecteur, en points. |
| width | **float** | La largeur du cadre du connecteur, en points. |
| height | **float** | La hauteur du cadre du connecteur, en points. |

### Valeur de retour

Le [IConnector](../../iconnector/) nouvellement créé.

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) méthode


Crée une nouvelle forme de connecteur et l’insère dans la collection de formes à l’indice spécifié, en appliquant éventuellement le style de modèle par défaut.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’indice basé sur zéro où insérer la forme de connecteur. |
| shapeType | [ShapeType](../../shapetype/) | Le [ShapeType](../../shapetype/) de la forme de connecteur à insérer. |
| x | **float** | La coordonnée x du cadre du connecteur, en points. |
| y | **float** | La coordonnée y du cadre du connecteur, en points. |
| width | **float** | La largeur du cadre du connecteur, en points. |
| height | **float** | La hauteur du cadre du connecteur, en points. |
| createFromTemplate | **bool** | True pour appliquer le style de modèle par défaut (nom non vide, style simple) ; false pour créer le connecteur avec les valeurs de propriétés par défaut. |

### Valeur de retour

Le [IConnector](../../iconnector/) nouvellement créé.

## Voir aussi

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)