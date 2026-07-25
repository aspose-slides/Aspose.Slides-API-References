---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいチャートシリーズを作成し、コレクションに追加します。
type: docs
weight: 53
url: /ja/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) メソッド


新しいチャートシリーズを作成し、コレクションに追加します。

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | シリーズのタイプ |

### 戻り値

新しいチャートシリーズ。

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) メソッド


[ChartDataCell](../../chartdatacell/) から新しいチャートシリーズを作成し、コレクションに追加します。

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) がシリーズ名を含む。 |
| type | [ChartType](../../charttype/) | シリーズのタイプを設定する型 |

### 戻り値

追加されたチャートシリーズ、またはすでにコレクションに存在するシリーズ。

## 備考


同じセルから作成されたチャートシリーズがすでにコレクションにある場合、メソッドは何も追加せず、そのインデックスを返します。



## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) メソッド


[ChartCellCollection](../../chartcellcollection/) から新しいチャートシリーズを作成し、コレクションに追加します。

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | シリーズ名を含むセル。 |
| type | [ChartType](../../charttype/) | シリーズのタイプを設定する型 |

### 戻り値

追加されたチャートシリーズ、またはすでにコレクションに存在するシリーズ。

## 備考


同じセルから作成されたチャートシリーズがすでにコレクションにある場合、メソッドは何も追加せず、そのインデックスを返します。



## ChartSeriesCollection::Add(System::String, ChartType) メソッド


値から新しいチャートシリーズを作成し、コレクションに追加します。

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | シリーズ名。 |
| type | [ChartType](../../charttype/) | シリーズのタイプを設定する型 |

### 戻り値

追加されたチャートシリーズ。

## 参照

* 列挙型 [ChartType](../../charttype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartSeries](../../ichartseries/)
* クラス [ChartSeriesCollection](../)
* クラス [IChartDataCell](../../ichartdatacell/)
* クラス [IChartCellCollection](../../ichartcellcollection/)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)