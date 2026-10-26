---
title: InsertChart()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个新图表，使用示例系列数据和设置进行初始化，并将其插入到指定索引的形状集合中。
type: docs
weight: 53
url: /zh/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) method

创建一个新图表，使用示例系列数据和设置进行初始化，并将其插入到指定索引的形状集合中。

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 要创建的图表类型。 |
| x | **float** | 新图表的X坐标（单位：点）。 |
| y | **float** | 新图表的Y坐标（单位：点）。 |
| width | **float** | 新图表的宽度（单位：点）。 |
| height | **float** | 新图表的高度（单位：点）。 |
| index | **int32_t** | 在形状集合中插入新图表的基于零的索引。 |

### 返回值

新创建的 [Charts::IChart](../../../aspose.slides.charts/ichart/)。

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) method

创建一个新图表，使用示例系列数据和设置进行初始化，并将其插入到指定索引的形状集合中。

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 要创建的图表类型。 |
| x | **float** | 新图表的X坐标（单位：点）。 |
| y | **float** | 新图表的Y坐标（单位：点）。 |
| width | **float** | 新图表的宽度（单位：点）。 |
| height | **float** | 新图表的高度（单位：点）。 |
| index | **int32_t** | 在形状集合中插入新图表的基于零的索引。 |
| initWithSample | **bool** | 若为 true，则使用示例系列数据和设置初始化新图表；若为 false，则创建不包含系列且仅含最小设置的图表，从而加快创建速度。 |

### 返回值

新创建的 [Charts::IChart](../../../aspose.slides.charts/ichart/)。

## 参见

* 枚举 [ChartType](../../../aspose.slides.charts/charttype/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChart](../../../aspose.slides.charts/ichart/)
* 类 [IShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)