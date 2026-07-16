---
title: AddChart()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nouveau graphique, l'initialise avec des données de séries d'exemple et des paramètres, et l'ajoute à la fin de la collection de formes.
type: docs
weight: 27
url: /fr/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) method

Crée un nouveau graphique, l'initialise avec des données de séries d'exemple et des paramètres, et l'ajoute à la fin de la collection de formes.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```

### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Le type de graphique à ajouter. |
| x | **float** | La coordonnée x du nouveau graphique, en points. |
| y | **float** | La coordonnée y du nouveau graphique, en points. |
| width | **float** | La largeur du graphique, en points. |
| height | **float** | La hauteur du graphique, en points. |

### Valeur de retour

Le [Charts::IChart](../../../aspose.slides.charts/ichart/) nouvellement créé.

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) method

Crée un nouveau graphique, l'initialise avec des données de séries d'exemple et des paramètres, et l'ajoute à la fin de la collection de formes.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```

### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Le type de graphique à ajouter. |
| x | **float** | La coordonnée x du nouveau graphique, en points. |
| y | **float** | La coordonnée y du nouveau graphique, en points. |
| width | **float** | La largeur du graphique, en points. |
| height | **float** | La hauteur du graphique, en points. |
| initWithSample | **bool** | Vrai pour initialiser le nouveau graphique avec des données de séries d'exemple et des paramètres ; faux pour créer le graphique sans séries et avec seulement des paramètres minimaux, ce qui rend la création plus rapide. |

### Valeur de retour

Le [Charts::IChart](../../../aspose.slides.charts/ichart/) nouvellement créé.

## Voir aussi

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)