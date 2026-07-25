---
title: AddDataPointForPieSeries()
second_title: Aspose.Slides for C++ APIリファレンス
description: "新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Pie のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer::IsChartTypePie(ChartType) メソッドも参照）。"
type: docs
weight: 287
url: /ja/aspose.slides.charts/chartdatapointcollection/adddatapointforpieseries/
---
## ChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr\<IChartDataCell\>) メソッド

新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Pie のサブタイプのいずれかであるシリーズに適用できます（[ChartTypeCharacterizer::IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) メソッドも参照）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr<IChartDataCell> value) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Data point Value |

### 戻り値

New data point.

## ChartDataPointCollection::AddDataPointForPieSeries(double) メソッド

新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Pie のサブタイプのいずれかであるシリーズに適用できます（[ChartTypeCharacterizer::IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) メソッドも参照）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForPieSeries(double value) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **double** | Data point Value |

### 戻り値

New data point.

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartDataPoint](../../ichartdatapoint/)
* クラス [IChartDataCell](../../ichartdatacell/)
* クラス [ChartDataPointCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)