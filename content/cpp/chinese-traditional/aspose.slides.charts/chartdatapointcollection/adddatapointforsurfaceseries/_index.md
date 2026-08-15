---
title: AddDataPointForSurfaceSeries()
second_title: Aspose.Slides for C++ API 參考
description: "建立新的資料點並將其新增至集合的末端。此方法適用於 chartType 為 Surface 子類型之一的系列（另請參閱 ChartTypeCharacterizer::IsChartTypeSurface(ChartType) 方法）。"
type: docs
weight: 326
url: /zh-hant/aspose.slides.charts/chartdatapointcollection/adddatapointforsurfaceseries/
---
## ChartDataPointCollection::AddDataPointForSurfaceSeries(System::SharedPtr\<IChartDataCell\>) method

建立新的資料點並將其新增至集合的末端。此方法適用於 chartType 為 Surface 子類型之一的系列（另請參閱 [ChartTypeCharacterizer::IsChartTypeSurface(ChartType)](../../charttypecharacterizer/ischarttypesurface/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForSurfaceSeries(System::SharedPtr<IChartDataCell> value) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 資料點值 |

### 傳回值

新的資料點。

## ChartDataPointCollection::AddDataPointForSurfaceSeries(double) method

建立新的資料點並將其新增至集合的末端。此方法適用於 chartType 為 Surface 子類型之一的系列（另請參閱 [ChartTypeCharacterizer::IsChartTypeSurface(ChartType)](../../charttypecharacterizer/ischarttypesurface/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForSurfaceSeries(double value) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **double** | 資料點值 |

### 傳回值

新的資料點。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataPoint](../../ichartdatapoint/)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [ChartDataPointCollection](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)