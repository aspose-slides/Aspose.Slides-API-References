---
title: AddDataPointForRadarSeries()
second_title: Aspose.Slides for C++ APIリファレンス
description: "新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Radar のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer::IsChartTypeRadar(ChartType) メソッドも参照）。"
type: docs
weight: 248
url: /ja/aspose.slides.charts/chartdatapointcollection/adddatapointforradarseries/
---
## ChartDataPointCollection::AddDataPointForRadarSeries(System::SharedPtr\<IChartDataCell\>) メソッド

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Radar のサブタイプのいずれかであるシリーズに適用できます（[ChartTypeCharacterizer::IsChartTypeRadar(ChartType)](../../charttypecharacterizer/ischarttyperadar/) メソッドを参照）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForRadarSeries(System::SharedPtr<IChartDataCell> value) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | データ ポイントの値 |

### 戻り値

新しいデータ ポイント。

## ChartDataPointCollection::AddDataPointForRadarSeries(double) メソッド

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Radar のサブタイプのいずれかであるシリーズに適用できます（[ChartTypeCharacterizer::IsChartTypeRadar(ChartType)](../../charttypecharacterizer/ischarttyperadar/) メソッドを参照）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForRadarSeries(double value) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | データ ポイントの値 |

### 戻り値

新しいデータ ポイント。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IChartDataPoint](../../ichartdatapoint/)
* クラス [IChartDataCell](../../ichartdatacell/)
* クラス [ChartDataPointCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)