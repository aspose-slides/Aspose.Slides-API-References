---
title: AddChart()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个新图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。
type: docs
weight: 27
url: /zh/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) 方法

创建一个新图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 要添加的图表类型。 |
| x | **float** | 新图表的 x 坐标，单位为点。 |
| y | **float** | 新图表的 y 坐标，单位为点。 |
| width | **float** | 图表的宽度，单位为点。 |
| height | **float** | 图表的高度，单位为点。 |

### 返回值

新创建的 [Charts::IChart](../../../aspose.slides.charts/ichart/)。

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) 方法

创建一个新图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 要添加的图表类型。 |
| x | **float** | 新图表的 x 坐标，单位为点。 |
| y | **float** | 新图表的 y 坐标，单位为点。 |
| width | **float** | 图表的宽度，单位为点。 |
| height | **float** | 图表的高度，单位为点。 |
| initWithSample | **bool** | true 表示使用示例系列数据和设置初始化新图表；false 表示创建不带系列且仅包含最小设置的图表，从而加快创建速度。 |

### 返回值

新创建的 [Charts::IChart](../../../aspose.slides.charts/ichart/)。

## 另请参见

* 枚举 [ChartType](../../../aspose.slides.charts/charttype/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChart](../../../aspose.slides.charts/ichart/)
* 类 [IShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)