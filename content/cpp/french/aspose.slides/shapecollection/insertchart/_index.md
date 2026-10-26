---
title: InsertChart()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nouveau diagramme, l'initialise avec des données de séries d'exemple et des paramètres, puis l'insère dans la collection de formes à l'index spécifié.
type: docs
weight: 92
url: /fr/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) method


Crée un nouveau diagramme, l'initialise avec des données de séries d'exemple et des paramètres, puis l'insère dans la collection de formes à l'index spécifié.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Le type de diagramme à créer. |
| x | **float** | La coordonnée x du nouveau diagramme, en points. |
| y | **float** | La coordonnée y du nouveau diagramme, en points. |
| width | **float** | La largeur du nouveau diagramme, en points. |
| height | **float** | La hauteur du nouveau diagramme, en points. |
| index | **int32_t** | L'index basé sur zéro où insérer le nouveau diagramme dans la collection de formes. |

### Valeur de retour

Le [Charts::IChart](../../../aspose.slides.charts/ichart/) nouvellement créé.

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) method


Crée un nouveau diagramme, l'initialise avec des données de séries d'exemple et des paramètres, puis l'insère dans la collection de formes à l'index spécifié.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Le type de diagramme à créer. |
| x | **float** | La coordonnée x du nouveau diagramme, en points. |
| y | **float** | La coordonnée y du nouveau diagramme, en points. |
| width | **float** | La largeur du nouveau diagramme, en points. |
| height | **float** | La hauteur du nouveau diagramme, en points. |
| index | **int32_t** | L'index basé sur zéro où insérer le nouveau diagramme dans la collection de formes. |
| initWithSample | **bool** | Vrai pour initialiser le nouveau diagramme avec des données de séries d'exemple et des paramètres ; faux pour créer le diagramme sans séries et avec uniquement des paramètres minimaux, ce qui accélère la création. |

### Valeur de retour

Le [Charts::IChart](../../../aspose.slides.charts/ichart/) nouvellement créé.

## Voir aussi

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)