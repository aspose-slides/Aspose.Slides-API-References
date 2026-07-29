---
title: InsertChart()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och infogar det i shape collection på det angivna indexet.
type: docs
weight: 53
url: /sv/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) metod


Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och lägger in det i shape collection på det angivna indexet.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typen av diagram som ska skapas. |
| x | **float** | X-koordinaten för det nya diagrammet, i punkter. |
| y | **float** | Y-koordinaten för det nya diagrammet, i punkter. |
| width | **float** | Bredden på det nya diagrammet, i punkter. |
| height | **float** | Höjden på det nya diagrammet, i punkter. |
| index | **int32_t** | Det nollbaserade indexet där det nya diagrammet ska infogas i shape collection. |

### Returvärde

Den nyss skapade [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) metod


Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och lägger in det i shape collection på det angivna indexet.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typen av diagram som ska skapas. |
| x | **float** | X-koordinaten för det nya diagrammet, i punkter. |
| y | **float** | Y-koordinaten för det nya diagrammet, i punkter. |
| width | **float** | Bredden på det nya diagrammet, i punkter. |
| height | **float** | Höjden på det nya diagrammet, i punkter. |
| index | **int32_t** | Det nollbaserade indexet där det nya diagrammet ska infogas i shape collection. |
| initWithSample | **bool** | Sant för att initiera det nya diagrammet med exempelseriedata och inställningar; falskt för att skapa diagrammet utan serier och endast minimala inställningar, vilket gör skapandet snabbare. |

### Returvärde

Den nyss skapade [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Se även

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChart](../../../aspose.slides.charts/ichart/)
* Klass [IShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)