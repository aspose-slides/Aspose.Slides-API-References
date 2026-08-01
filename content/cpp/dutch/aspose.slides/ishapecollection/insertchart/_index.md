---
title: InsertChart()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuwe grafiek, initialiseert deze met voorbeeldreeksgegevens en instellingen, en voegt deze in de vormverzameling in op de opgegeven index.
type: docs
weight: 53
url: /nl/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) methode

Maakt een nieuwe grafiek, initialiseert deze met voorbeeldreeksgegevens en instellingen, en voegt deze in de vormverzameling in op de opgegeven index.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Het type grafiek om te maken. |
| x | **float** | De x-coördinaat van de nieuwe grafiek, in punten. |
| y | **float** | De y-coördinaat van de nieuwe grafiek, in punten. |
| width | **float** | De breedte van de nieuwe grafiek, in punten. |
| height | **float** | De hoogte van de nieuwe grafiek, in punten. |
| index | **int32_t** | De nulgebaseerde index waarop de nieuwe grafiek in de vormverzameling moet worden ingevoegd. |

### Retourwaarde

De nieuw aangemaakte [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) methode

Maakt een nieuwe grafiek, initialiseert deze met voorbeeldreeksgegevens en instellingen, en voegt deze in de vormverzameling in op de opgegeven index.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Het type grafiek om te maken. |
| x | **float** | De x-coördinaat van de nieuwe grafiek, in punten. |
| y | **float** | De y-coördinaat van de nieuwe grafiek, in punten. |
| width | **float** | De breedte van de nieuwe grafiek, in punten. |
| height | **float** | De hoogte van de nieuwe grafiek, in punten. |
| index | **int32_t** | De nulgebaseerde index waarop de nieuwe grafiek in de vormverzameling moet worden ingevoegd. |
| initWithSample | **bool** | True om de nieuwe grafiek te initialiseren met voorbeeldreeksgegevens en instellingen; false om de grafiek te maken zonder reeksen en alleen met minimale instellingen, waardoor de creatie sneller gaat. |

### Retourwaarde

De nieuw aangemaakte [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Zie ook

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChart](../../../aspose.slides.charts/ichart/)
* Klasse [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)