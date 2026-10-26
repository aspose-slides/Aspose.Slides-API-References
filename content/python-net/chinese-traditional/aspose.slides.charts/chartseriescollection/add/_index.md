---
title: add method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
建立新的圖表系列並將其加入集合。

### Returns
回傳值

新的圖表系列。

```python
def add(self, type):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/zh-hant/aspose.slides.charts/charttype) | 系列的類型 |

## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
從 [`ChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatacell) 建立新的圖表系列並將其加入集合。

### Returns
回傳值

已加入的圖表系列或集合中已存在的系列。

```python
def add(self, cell_with_series_name, type):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell) | 包含系列名稱的儲存格。 |
| type | [`ChartType`](/slides/python-net/zh-hant/aspose.slides.charts/charttype) | 系列類型的設定類型 |

### Remarks
如果已從相同儲存格建立的圖表系列已在集合中，則此方法不會新增任何內容，並返回其索引。

## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
從 [`ChartCellCollection`](/slides/python-net/zh-hant/aspose.slides.charts/chartcellcollection) 建立新的圖表系列並將其加入集合。

### Returns
回傳值

已加入的圖表系列或集合中已存在的系列。

```python
def add(self, cells_with_series_name, type):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcellcollection) | 包含系列名稱的儲存格。 |
| type | [`ChartType`](/slides/python-net/zh-hant/aspose.slides.charts/charttype) | 系列類型的設定類型 |

### Remarks
如果已從相同儲存格建立的圖表系列已在集合中，則此方法不會新增任何內容，並返回其索引。

## add(self, name, type) {#str-charttype}
從值建立新的圖表系列並將其加入集合。

### Returns
回傳值

已加入的圖表系列。

```python
def add(self, name, type):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| name | **str** | 系列名稱。 |
| type | [`ChartType`](/slides/python-net/zh-hant/aspose.slides.charts/charttype) | 系列類型的設定類型 |

### See Also
* 類別 [`ChartCellCollection`](/slides/python-net/zh-hant/aspose.slides.charts/chartcellcollection)
* 類別 [`ChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatacell)
* 類別 [`ChartSeriesCollection`](/slides/python-net/zh-hant/aspose.slides.charts/chartseriescollection)
* 列舉 [`ChartType`](/slides/python-net/zh-hant/aspose.slides.charts/charttype)
* 類別 [`IChartCellCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcellcollection)
* 類別 [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell)
* 類別 [`IChartSeries`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)