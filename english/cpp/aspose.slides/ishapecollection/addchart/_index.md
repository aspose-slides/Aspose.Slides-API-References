---
title: AddChart()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new Chart, initialize it with sample series data and settings and adds it to the end of the collection.
type: docs
weight: 27
url: /cpp/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart([Charts::ChartType](../../../aspose.slides.charts/charttype/), **float**, **float**, **float**, **float**) method


Creates a new Chart, initialize it with sample series data and settings and adds it to the end of the collection.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Type of chart. |
| x | **float** | X coordinate of a new chart. |
| y | **float** | Y coordinate of a new chart. |
| width | **float** | Chart's width. |
| height | **float** | Chart's height. |

### Return Value

Created chart.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IShapeCollection::AddChart([Charts::ChartType](../../../aspose.slides.charts/charttype/), **float**, **float**, **float**, **float**, **bool**) method


Creates a new Chart and adds it to the end of the collection.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Type of chart. |
| x | **float** | X coordinate of a new chart. |
| y | **float** | Y coordinate of a new chart. |
| width | **float** | Chart's width. |
| height | **float** | Chart's height. |
| initWithSample | **bool** | If true then new chart will be initialized with sample series data and settings. If false then new chart will have no series and minimum settings. In this case chart creation will be more fast. |

### Return Value

Created chart.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
