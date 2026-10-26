---
title: InsertChart()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw chart, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het in de shape collection in op de opgegeven index.
type: docs
weight: 92
url: /nl/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) methode


Maakt een nieuw chart, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het in de shape collection in op de opgegeven index.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Het type chart om te maken. |
| x | **float** | De x-coördinaat van het nieuwe chart, in points. |
| y | **float** | De y-coördinaat van het nieuwe chart, in points. |
| width | **float** | De breedte van het nieuwe chart, in points. |
| height | **float** | De hoogte van het nieuwe chart, in points. |
| index | **int32_t** | De nul-gebaseerde index waarop het nieuwe chart in de shape collection moet worden ingevoegd. |

### Retourwaarde

The newly created [Charts::IChart](../../../aspose.slides.charts/ichart/).

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) methode


Maakt een nieuw chart, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het in de shape collection in op de opgegeven index.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Het type chart om te maken. |
| x | **float** | De x-coördinaat van het nieuwe chart, in points. |
| y | **float** | De y-coördinaat van het nieuwe chart, in points. |
| width | **float** | De breedte van het nieuwe chart, in points. |
| height | **float** | De hoogte van het nieuwe chart, in points. |
| index | **int32_t** | De nul-gebaseerde index waarop het nieuwe chart in de shape collection moet worden ingevoegd. |
| initWithSample | **bool** | Waarbij true om het nieuwe chart te initialiseren met voorbeeldreeksgegevens en instellingen; false om het chart te maken zonder series en alleen met minimale instellingen, waardoor de creatie sneller gaat. |

### Retourwaarde

The newly created [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Zie ook

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChart](../../../aspose.slides.charts/ichart/)
* Klasse [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)