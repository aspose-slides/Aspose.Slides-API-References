---
title: add method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
新しいチャート系列を作成し、コレクションに追加します。

### 戻り値

新しいチャート系列。

```python
def add(self, type):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype) | シリーズの型 |

## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
[`ChartDataCell`](/slides/python-net/ja/aspose.slides.charts/chartdatacell) から新しいチャート系列を作成し、コレクションに追加します。

### 戻り値

追加されたチャート系列、または既にコレクションに存在する系列。

```python
def add(self, cell_with_series_name, type):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell) | シリーズ名を含む Cell |
| type | [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype) | シリーズの type を設定する |

### 備考

同じセルから作成されたチャート系列が既にコレクションにある場合、メソッドは何も追加せず、そのインデックスを返します。

## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
[`ChartCellCollection`](/slides/python-net/ja/aspose.slides.charts/chartcellcollection) から新しいチャート系列を作成し、コレクションに追加します。

### 戻り値

追加されたチャート系列、または既にコレクションに存在する系列。

```python
def add(self, cells_with_series_name, type):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcellcollection) | シリーズ名を含むセル |
| type | [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype) | シリーズの type を設定する |

### 備考

同じセルから作成されたチャート系列が既にコレクションにある場合、メソッドは何も追加せず、そのインデックスを返します。

## add(self, name, type) {#str-charttype}
値から新しいチャート系列を作成し、コレクションに追加します。

### 戻り値

追加されたチャート系列。

```python
def add(self, name, type):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| name | **str** | シリーズ名 |
| type | [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype) | シリーズの type を設定する |

### 参照
* クラス [`ChartCellCollection`](/slides/python-net/ja/aspose.slides.charts/chartcellcollection)
* クラス [`ChartDataCell`](/slides/python-net/ja/aspose.slides.charts/chartdatacell)
* クラス [`ChartSeriesCollection`](/slides/python-net/ja/aspose.slides.charts/chartseriescollection)
* 列挙体 [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype)
* クラス [`IChartCellCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcellcollection)
* クラス [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell)
* クラス [`IChartSeries`](/slides/python-net/ja/aspose.slides.charts/ichartseries)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)