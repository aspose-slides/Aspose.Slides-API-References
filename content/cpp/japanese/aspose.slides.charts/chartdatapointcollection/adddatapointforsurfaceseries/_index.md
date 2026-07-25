---
title: AddDataPointForSurfaceSeries()
second_title: Aspose.Slides for C++ APIリファレンス
description: "新しいデータポイントを作成し、コレクションの末尾に追加します。Series の chartType が Surface のサブタイプのいずれかである場合に適用可能です（ChartTypeCharacterizer::IsChartTypeSurface(ChartType) メソッドも参照）。"
type: docs
weight: 326
url: /ja/aspose.slides.charts/chartdatapointcollection/adddatapointforsurfaceseries/
---
## ChartDataPointCollection::AddDataPointForSurfaceSeries(System::SharedPtr\<IChartDataCell\>) メソッド

新しいデータポイントを作成し、コレクションの末尾に追加します。Series の chartType が Surface のサブタイプのいずれかである場合に適用可能です（[ChartTypeCharacterizer::IsChartTypeSurface(ChartType)](../../charttypecharacterizer/ischarttypesurface/) メソッドも参照）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForSurfaceSeries(System::SharedPtr<IChartDataCell> value) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | データポイントの値 |

### 戻り値

新しいデータポイント。

## ChartDataPointCollection::AddDataPointForSurfaceSeries(double) メソッド

新しいデータポイントを作成し、コレクションの末尾に追加します。Series の chartType が Surface のサブタイプのいずれかである場合に適用可能です（[ChartTypeCharacterizer::IsChartTypeSurface(ChartType)](../../charttypecharacterizer/ischarttypesurface/) メソッドも参照）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForSurfaceSeries(double value) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **double** | データポイントの値 |

### 戻り値

新しいデータポイント。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartDataPoint](../../ichartdatapoint/)
* クラス [IChartDataCell](../../ichartdatacell/)
* クラス [ChartDataPointCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)