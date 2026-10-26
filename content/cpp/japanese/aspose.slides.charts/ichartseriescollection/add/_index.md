---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいチャート系列を作成し、コレクションに追加します。
type: docs
weight: 14
url: /ja/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) メソッド


新しいチャート系列を作成し、コレクションに追加します。

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | 系列のタイプ |

### 戻り値

New chart series.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) メソッド


[IChartDataCell](../../ichartdatacell/) から新しいチャート系列を作成し、コレクションに追加します。

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) は系列名を含むものです。 |
| type | [ChartType](../../charttype/) | 系列のタイプを設定する型 |

### 戻り値

Added chart series or series that already is in collection.

## 備考


同じセルから作成されたチャート系列が既にコレクションに存在する場合、メソッドは何も追加せず、そのインデックスを返します。

## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) メソッド


[IChartCellCollection](../../ichartcellcollection/) から新しいチャート系列を作成し、コレクションに追加します。

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | 系列名を含むセル。 |
| type | [ChartType](../../charttype/) | 系列のタイプを設定する型 |

### 戻り値

Added chart series or series that already is in collection.

## 備考


同じセルから作成されたチャート系列が既にコレクションに存在する場合、メソッドは何も追加せず、そのインデックスを返します。

## IChartSeriesCollection::Add(System::String, ChartType) メソッド


値から新しいチャート系列を作成し、コレクションに追加します。

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | 系列名。 |
| type | [ChartType](../../charttype/) | 系列のタイプを設定する型 |

### 戻り値

Added chart series.

## 関連項目

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [IChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)