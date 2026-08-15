---
title: AddChart()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個新圖表，使用範例系列資料和設定進行初始化，並將其新增至形狀集合的末端。
type: docs
weight: 27
url: /zh-hant/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) 方法

建立一個新圖表，使用範例系列資料和設定進行初始化，並將其新增至形狀集合的末端。

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 要加入的圖表類型。 |
| x | **float** | 新圖表的 x 坐標（單位為點）。 |
| y | **float** | 新圖表的 y 坐標（單位為點）。 |
| width | **float** | 圖表的寬度（單位為點）。 |
| height | **float** | 圖表的高度（單位為點）。 |

### 返回值

新建立的 [Charts::IChart](../../../aspose.slides.charts/ichart/)。

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) 方法

建立一個新圖表，使用範例系列資料和設定進行初始化，並將其新增至形狀集合的末端。

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 要加入的圖表類型。 |
| x | **float** | 新圖表的 x 坐標（單位為點）。 |
| y | **float** | 新圖表的 y 坐標（單位為點）。 |
| width | **float** | 圖表的寬度（單位為點）。 |
| height | **float** | 圖表的高度（單位為點）。 |
| initWithSample | **bool** | 若為 true，則以範例系列資料和設定初始化新圖表；若為 false，則建立沒有系列且僅含最小設定的圖表，這樣可以加快建立速度。 |

### 返回值

新建立的 [Charts::IChart](../../../aspose.slides.charts/ichart/)。

## 另請參閱

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IChart](../../../aspose.slides.charts/ichart/)
* 類別 [IShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)