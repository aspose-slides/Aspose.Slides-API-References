---
title: AddChart()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new chart, initializes it with sample series data and settings, and adds it to the end of the shape collection.
type: docs
weight: 27
url: /aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) method


Creates a new chart, initializes it with sample series data and settings, and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | The type of chart to add. |
| x | **float** | The x-coordinate of the new chart, in points. |
| y | **float** | The y-coordinate of the new chart, in points. |
| width | **float** | The width of the chart, in points. |
| height | **float** | The height of the chart, in points. |

### Return Value

The newly created [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) method


Creates a new chart, initializes it with sample series data and settings, and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | The type of chart to add. |
| x | **float** | The x-coordinate of the new chart, in points. |
| y | **float** | The y-coordinate of the new chart, in points. |
| width | **float** | The width of the chart, in points. |
| height | **float** | The height of the chart, in points. |
| initWithSample | **bool** | True to initialize the new chart with sample series data and settings; false to create the chart with no series and only minimal settings, which makes creation faster. |

### Return Value

The newly created [Charts::IChart](../../../aspose.slides.charts/ichart/).

## See Also

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)