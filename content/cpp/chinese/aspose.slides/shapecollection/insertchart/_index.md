---
title: InsertChart()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个新图表，使用示例系列数据和设置进行初始化，并将其插入到指定索引的形状集合中。
type: docs
weight: 92
url: /zh/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) 方法

创建一个新图表，使用示例系列数据和设置进行初始化，并将其插入到指定索引的形状集合中。

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 要创建的图表类型。 |
| x | **float** | 新图表的 x 坐标，单位为点。 |
| y | **float** | 新图表的 y 坐标，单位为点。 |
| width | **float** | 新图表的宽度，单位为点。 |
| height | **float** | 新图表的高度，单位为点。 |
| index | **int32_t** | 在形状集合中插入新图表的零基索引。 |

### 返回值

新创建的[Charts::IChart](../../../aspose.slides.charts/ichart/)。

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) 方法

创建一个新图表，使用示例系列数据和设置进行初始化，并将其插入到指定索引的形状集合中。

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 要创建的图表类型。 |
| x | **float** | 新图表的 x 坐标，单位为点。 |
| y | **float** | 新图表的 y 坐标，单位为点。 |
| width | **float** | 新图表的宽度，单位为点。 |
| height | **float** | 新图表的高度，单位为点。 |
| index | **int32_t** | 在形状集合中插入新图表的零基索引。 |
| initWithSample | **bool** | True 表示使用示例系列数据和设置初始化新图表；false 表示创建无系列且仅具最少设置的图表，从而加快创建速度。 |

### 返回值

新创建的[Charts::IChart](../../../aspose.slides.charts/ichart/)。

## 另见

* 枚举 [ChartType](../../../aspose.slides.charts/charttype/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChart](../../../aspose.slides.charts/ichart/)
* 类 [ShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)