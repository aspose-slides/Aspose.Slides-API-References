---
title: InsertChart()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新圖表，使用範例系列資料和設定進行初始化，並將其插入至指定索引的形狀集合中。
type: docs
weight: 92
url: /zh-hant/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) 方法

建立一個新的圖表，使用範例系列資料和設定進行初始化，並將其插入至指定索引的形狀集合中。

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 要建立的圖表類型。 |
| x | **float** | 新圖表的 x 座標，以點為單位。 |
| y | **float** | 新圖表的 y 座標，以點為單位。 |
| width | **float** | 新圖表的寬度，以點為單位。 |
| height | **float** | 新圖表的高度，以點為單位。 |
| index | **int32_t** | 要在形狀集合中插入新圖表的零基索引。 |

### 傳回值

新建立的 [Charts::IChart](../../../aspose.slides.charts/ichart/)。

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) 方法

建立一個新的圖表，使用範例系列資料和設定進行初始化，並將其插入至指定索引的形狀集合中。

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 要建立的圖表類型。 |
| x | **float** | 新圖表的 x 座標，以點為單位。 |
| y | **float** | 新圖表的 y 座標，以點為單位。 |
| width | **float** | 新圖表的寬度，以點為單位。 |
| height | **float** | 新圖表的高度，以點為單位。 |
| index | **int32_t** | 要在形狀集合中插入新圖表的零基索引。 |
| initWithSample | **bool** | 若為 true，則以範例系列資料和設定初始化新圖表；若為 false，則建立沒有系列且僅有最小設定的圖表，這會使建立更快速。 |

### 傳回值

新建立的 [Charts::IChart](../../../aspose.slides.charts/ichart/)。

## 另請參閱

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)