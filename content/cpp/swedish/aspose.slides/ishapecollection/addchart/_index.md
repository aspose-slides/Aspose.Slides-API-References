---
title: AddChart()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar och lägger till det i slutet av formsamlingen.
type: docs
weight: 27
url: /sv/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) method

Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar och lägger till det i slutet av formsamlingen.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typen av diagram som ska läggas till. |
| x | **float** | X-koordinaten för det nya diagrammet, i punkter. |
| y | **float** | Y-koordinaten för det nya diagrammet, i punkter. |
| width | **float** | Bredden på diagrammet, i punkter. |
| height | **float** | Höjden på diagrammet, i punkter. |

### Returvärde

Det nyss skapade [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) method

Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar och lägger till det i slutet av formsamlingen.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typen av diagram som ska läggas till. |
| x | **float** | X-koordinaten för det nya diagrammet, i punkter. |
| y | **float** | Y-koordinaten för det nya diagrammet, i punkter. |
| width | **float** | Bredden på diagrammet, i punkter. |
| height | **float** | Höjden på diagrammet, i punkter. |
| initWithSample | **bool** | True för att initiera det nya diagrammet med exempelseriedata och inställningar; false för att skapa diagrammet utan serier och endast med minimala inställningar, vilket gör skapandet snabbare. |

### Returvärde

Det nyss skapade [Charts::IChart](../../../aspose.slides.charts/ichart/).

## See Also

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChart](../../../aspose.slides.charts/ichart/)
* Klass [IShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)