---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Column または Bar のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeColumn(ChartType) と ChartTypeCharacterizer.IsChartTypeBar(ChartType) メソッドも参照）。
type: docs
weight: 196
url: /ja/aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries/
---
## IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) メソッド

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が [Column](../../../aspose.slides/column/) または Bar サブタイプのいずれかであるシリーズに適用できます（[ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) と [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) メソッドも参照）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | データ ポイントの値 |

### 戻り値

新しいデータ ポイント。

## IChartDataPointCollection::AddDataPointForBarSeries(double) メソッド

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が [Column](../../../aspose.slides/column/) または Bar サブタイプのいずれかであるシリーズに適用できます（[ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) と [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) メソッドも参照）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(double value)=0
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
* クラス [IChartDataPointCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)