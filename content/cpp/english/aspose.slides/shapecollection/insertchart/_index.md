---
title: InsertChart()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new chart, initializes it with sample series data and settings, and inserts it into the shape collection at the specified index.
type: docs
weight: 92
url: /aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) method


Creates a new chart, initializes it with sample series data and settings, and inserts it into the shape collection at the specified index.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | The type of chart to create. |
| x | **float** | The x-coordinate of the new chart, in points. |
| y | **float** | The y-coordinate of the new chart, in points. |
| width | **float** | The width of the new chart, in points. |
| height | **float** | The height of the new chart, in points. |
| index | **int32_t** | The zero-based index at which to insert the new chart in the shape collection. |

### Return Value

The newly created [Charts::IChart](../../../aspose.slides.charts/ichart/).

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) method


Creates a new chart, initializes it with sample series data and settings, and inserts it into the shape collection at the specified index.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | The type of chart to create. |
| x | **float** | The x-coordinate of the new chart, in points. |
| y | **float** | The y-coordinate of the new chart, in points. |
| width | **float** | The width of the new chart, in points. |
| height | **float** | The height of the new chart, in points. |
| index | **int32_t** | The zero-based index at which to insert the new chart in the shape collection. |
| initWithSample | **bool** | True to initialize the new chart with sample series data and settings; false to create the chart with no series and only minimal settings, which makes creation faster. |

### Return Value

The newly created [Charts::IChart](../../../aspose.slides.charts/ichart/).

## See Also

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)