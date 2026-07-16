---
title: InsertConnector()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une nouvelle forme de connecteur et l'insère dans la collection de formes à l'index spécifié, en appliquant le style de modèle par défaut.
type: docs
weight: 430
url: /fr/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) méthode

Crée une nouvelle forme de connecteur et l'insère dans la collection de formes à l'index spécifié, en appliquant le style de modèle par défaut.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index zéro à partir duquel insérer la forme de connecteur. |
| shapeType | [ShapeType](../../shapetype/) | Le [ShapeType](../../shapetype/) de la forme de connecteur à insérer. |
| x | **float** | La coordonnée x du cadre du connecteur, en points. |
| y | **float** | La coordonnée y du cadre du connecteur, en points. |
| width | **float** | La largeur du cadre du connecteur, en points. |
| height | **float** | La hauteur du cadre du connecteur, en points. |

### Valeur de retour

Le [IConnector](../../iconnector/) nouvellement créé.

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) méthode

Crée une nouvelle forme de connecteur et l'insère dans la collection de formes à l'index spécifié, en appliquant éventuellement le style de modèle par défaut.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index zéro à partir duquel insérer la forme de connecteur. |
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
* Classe [IConnector](../../iconnector/)
* Classe [ShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)