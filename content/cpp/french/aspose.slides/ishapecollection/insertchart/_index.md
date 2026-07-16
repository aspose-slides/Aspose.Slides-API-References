---
title: InsertChart()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nouveau graphique, l'initialise avec des données de séries d'exemple et des paramètres, puis l'insère dans la collection de formes à l'index spécifié.
type: docs
weight: 53
url: /fr/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) méthode

Crée un nouveau graphique, l'initialise avec des données de séries d'exemple et des paramètres, puis l'insère dans la collection de formes à l'index spécifié.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Le type de graphique à créer. |
| x | **float** | La coordonnée x du nouveau graphique, en points. |
| y | **float** | La coordonnée y du nouveau graphique, en points. |
| width | **float** | La largeur du nouveau graphique, en points. |
| height | **float** | La hauteur du nouveau graphique, en points. |
| index | **int32_t** | L'index de base zéro à laquelle insérer le nouveau graphique dans la collection de formes. |

### Valeur de retour

Le [Charts::IChart](../../../aspose.slides.charts/ichart/) nouvellement créé.

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) méthode

Crée un nouveau graphique, l'initialise avec des données de séries d'exemple et des paramètres, puis l'insère dans la collection de formes à l'index spécifié.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Le type de graphique à créer. |
| x | **float** | La coordonnée x du nouveau graphique, en points. |
| y | **float** | La coordonnée y du nouveau graphique, en points. |
| width | **float** | La largeur du nouveau graphique, en points. |
| height | **float** | La hauteur du nouveau graphique, en points. |
| index | **int32_t** | L'index de base zéro à laquelle insérer le nouveau graphique dans la collection de formes. |
| initWithSample | **bool** | Vrai pour initialiser le nouveau graphique avec des données de séries d'exemple et des paramètres ; faux pour créer le graphique sans séries et uniquement avec des paramètres minimaux, ce qui rend la création plus rapide. |

### Valeur de retour

Le [Charts::IChart](../../../aspose.slides.charts/ichart/) nouvellement créé.

## Voir aussi

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)