---
title: InsertChart()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新圖表，使用樣本系列資料和設定進行初始化，並將其插入到指定索引的形狀集合中。
type: docs
weight: 53
url: /zh-hant/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) 方法

建立一個新圖表，使用樣本系列資料和設定進行初始化，並將其插入到指定索引的形狀集合中。

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 要建立的圖表類型。 |
| x | **float** | 新圖表的 x 座標，單位為點。 |
| y | **float** | 新圖表的 y 座標，單位為點。 |
| width | **float** | 新圖表的寬度，單位為點。 |
| height | **float** | 新圖表的高度，單位為點。 |
| index | **int32_t** | 在形狀集合中插入新圖表的零基索引。 |

### 回傳值

新建立的 [Charts::IChart](../../../aspose.slides.charts/ichart/)。

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) 方法

建立一個新圖表，使用樣本系列資料和設定進行初始化，並將其插入到指定索引的形狀集合中。

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 要建立的圖表類型。 |
| x | **float** | 新圖表的 x 座標，單位為點。 |
| y | **float** | 新圖表的 y 座標，單位為點。 |
| width | **float** | 新圖表的寬度，單位為點。 |
| height | **float** | 新圖表的高度，單位為點。 |
| index | **int32_t** | 在形狀集合中插入新圖表的零基索引。 |
| initWithSample | **bool** | true：使用樣本系列資料和設定初始化新圖表；false：建立沒有系列且僅具最小設定的圖表，可加快建立速度。 |

### 回傳值

新建立的 [Charts::IChart](../../../aspose.slides.charts/ichart/)。

## 參考

* 列舉 [ChartType](../../../aspose.slides.charts/charttype/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChart](../../../aspose.slides.charts/ichart/)
* 類別 [IShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)