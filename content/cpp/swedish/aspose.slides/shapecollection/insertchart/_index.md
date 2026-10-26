---
title: InsertChart()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och infogar det i shape-samlingen på det angivna indexet.
type: docs
weight: 92
url: /sv/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) method


Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och infogar det i shape-samlingen på det angivna indexet.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typen av diagram att skapa. |
| x | **float** | X-koordinaten för det nya diagrammet, i punkter. |
| y | **float** | Y-koordinaten för det nya diagrammet, i punkter. |
| width | **float** | Bredden på det nya diagrammet, i punkter. |
| height | **float** | Höjden på det nya diagrammet, i punkter. |
| index | **int32_t** | Det nollbaserade index där diagrammet ska infogas i shape-samlingen. |

### Returvärde

Det nyss skapade [Charts::IChart](../../../aspose.slides.charts/ichart/).

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) method


Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och infogar det i shape-samlingen på det angivna indexet.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typen av diagram att skapa. |
| x | **float** | X-koordinaten för det nya diagrammet, i punkter. |
| y | **float** | Y-koordinaten för det nya diagrammet, i punkter. |
| width | **float** | Bredden på det nya diagrammet, i punkter. |
| height | **float** | Höjden på det nya diagrammet, i punkter. |
| index | **int32_t** | Det nollbaserade index där diagrammet ska infogas i shape-samlingen. |
| initWithSample | **bool** | True för att initiera det nya diagrammet med exempelseriedata och inställningar; false för att skapa diagrammet utan serier och bara med minimala inställningar, vilket gör skapandet snabbare. |

### Returvärde

Det nyss skapade [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Se även

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChart](../../../aspose.slides.charts/ichart/)
* Klass [ShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)