---
title: add method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
新しいチャートシリーズを作成し、コレクションに追加します。

### 戻り値

新しいチャートシリーズ。

```python
def add(self, type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype) | シリーズのタイプ |

## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
[`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell)から新しいチャートシリーズを作成し、コレクションに追加します。

### 戻り値

コレクションに追加されたチャートシリーズ、または既にコレクションに存在するシリーズ。

```python
def add(self, cell_with_series_name, type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell) | シリーズ名を含むセル。 |
| type | [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype) | シリーズのタイプを設定する型 |

### 備考

同じセルから作成されたチャートシリーズが既にコレクションに存在する場合、メソッドは何も追加せず、そのインデックスを返します。

## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
[`IChartCellCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcellcollection)から新しいチャートシリーズを作成し、コレクションに追加します。

### 戻り値

コレクションに追加されたチャートシリーズ、または既にコレクションに存在するシリーズ。

```python
def add(self, cells_with_series_name, type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcellcollection) | シリーズ名を含むセル群。 |
| type | [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype) | シリーズのタイプを設定する型 |

### 備考

同じセルから作成されたチャートシリーズが既にコレクションに存在する場合、メソッドは何も追加せず、そのインデックスを返します。

## add(self, name, type) {#str-charttype}
値から新しいチャートシリーズを作成し、コレクションに追加します。

### 戻り値

追加されたチャートシリーズ。

```python
def add(self, name, type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | **str** | シリーズ名。 |
| type | [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype) | シリーズのタイプを設定する型 |

### 参照
* 列挙体 [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype)
* クラス [`IChartCellCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcellcollection)
* クラス [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell)
* クラス [`IChartSeries`](/slides/python-net/ja/aspose.slides.charts/ichartseries)
* クラス [`IChartSeriesCollection`](/slides/python-net/ja/aspose.slides.charts/ichartseriescollection)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)