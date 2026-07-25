---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides for C++ API リファレンス
description: "新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Stock のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer::IsChartTypeStock(ChartType) メソッドも参照）。"
type: docs
weight: 209
url: /ja/aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries/
---
## ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) メソッド


新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Stock のサブタイプのいずれかであるシリーズに適用できます（[ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) メソッドも参照）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | データポイントの値。 |

### 戻り値

新しいデータポイント。

## ChartDataPointCollection::AddDataPointForStockSeries(double) メソッド


新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Stock のサブタイプのいずれかであるシリーズに適用できます（[ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) メソッドも参照）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(double value) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **double** | データポイントの値。 |

### 戻り値

新しいデータポイント。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartDataPoint](../../ichartdatapoint/)
* クラス [IChartDataCell](../../ichartdatacell/)
* クラス [ChartDataPointCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)