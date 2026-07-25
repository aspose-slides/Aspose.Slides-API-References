---
title: AddDataPointForLineSeries()
second_title: Aspose.Slides for C++ API リファレンス
description: "新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Line のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer::IsChartTypeLine(ChartType) メソッドも参照）。"
type: docs
weight: 222
url: /ja/aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries/
---
## ChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr\<IChartDataCell\>) メソッド

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Line のサブタイプのいずれかであるシリーズに適用できます（[ChartTypeCharacterizer::IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) メソッドも参照）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr<IChartDataCell> value) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | データ ポイントの値。 |

### 戻り値

新しいデータ ポイント。

## ChartDataPointCollection::AddDataPointForLineSeries(double) メソッド

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Line のサブタイプのいずれかであるシリーズに適用できます（[ChartTypeCharacterizer::IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) メソッドも参照）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForLineSeries(double value) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **double** | データ ポイントの値。 |

### 戻り値

新しいデータ ポイント。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartDataPoint](../../ichartdatapoint/)
* クラス [IChartDataCell](../../ichartdatacell/)
* クラス [ChartDataPointCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)