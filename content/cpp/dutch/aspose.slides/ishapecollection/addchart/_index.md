---
title: AddChart()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw diagram, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het toe aan het einde van de shape-collectie.
type: docs
weight: 27
url: /nl/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) methode

Maakt een nieuw diagram, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het toe aan het einde van de shape-collectie.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Het type diagram om toe te voegen. |
| x | **float** | De x-coördinaat van het nieuwe diagram, in punten. |
| y | **float** | De y-coördinaat van het nieuwe diagram, in punten. |
| width | **float** | De breedte van het diagram, in punten. |
| height | **float** | De hoogte van het diagram, in punten. |

### Retourwaarde

Het nieuw aangemaakte [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) methode

Maakt een nieuw diagram, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het toe aan het einde van de shape-collectie.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Het type diagram om toe te voegen. |
| x | **float** | De x-coördinaat van het nieuwe diagram, in punten. |
| y | **float** | De y-coördinaat van het nieuwe diagram, in punten. |
| width | **float** | De breedte van het diagram, in punten. |
| height | **float** | De hoogte van het diagram, in punten. |
| initWithSample | **bool** | true om het nieuwe diagram te initialiseren met voorbeeldreeksgegevens en instellingen; false om het diagram te maken zonder series en alleen met minimale instellingen, waardoor het aanmaken sneller gaat. |

### Retourwaarde

Het nieuw aangemaakte [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Zie ook

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChart](../../../aspose.slides.charts/ichart/)
* Klasse [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)