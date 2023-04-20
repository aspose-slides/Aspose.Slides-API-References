---
title: InsertChart()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new Chart, initialize it with sample series data and settings and inserts it to the specified position in the collection.
type: docs
weight: 92
url: /cpp/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) method


Creates a new Chart, initialize it with sample series data and settings and inserts it to the specified position in the collection.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Type of chart. |
| x | **float** | X coordinate of a new chart. |
| y | **float** | Y coordinate of a new chart. |
| width | **float** | Chart's width. |
| height | **float** | Chart's height. |
| index | **int32_t** | Chart's position in the collection. |

### Return Value

Created chart.

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) method


Creates a new Chart and inserts it to the specified position in the collection.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Type of chart. |
| x | **float** | X coordinate of a new chart. |
| y | **float** | Y coordinate of a new chart. |
| width | **float** | Chart's width. |
| height | **float** | Chart's height. |
| index | **int32_t** | Chart's position in the collection. |
| initWithSample | **bool** | If true then new chart will be initialized with sample series data and settings. If false then new chart will have no series and minimum settings. In this case chart creation will be more fast. |

### Return Value

Created chart.

## See Also

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)