---
title: add method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
如果集合中已存在類別，則返回它。否則從
            [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell) 建立新的圖表類別並將其新增至集合。

### 返回值

已新增或已存在的類別。

```python
def add(self, chart_data_cell):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell) | 用於建立圖表類別的儲存格。 |

## add(self, value) {#any}
從值建立新的 [`IChartCategory`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory) 並將其新增至集合。

### 返回值

已新增 [`IChartCategory`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory)。

```python
def add(self, value):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| value | **any** | 值。 |

### 備註

此方法會新增名稱為 AUTO_DATA 的工作表，並將所有值新增於其中。若您使用 [`IChartDataWorkbook`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdataworkbook) 來新增或編輯儲存格值，請確保不要使用此工作表
            使用此方法新增的最大值數量不得超過 16711680

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 超過限制時拋出 |

### 另請參閱
* class [`IChartCategory`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory)
* class [`IChartCategoryCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection)
* class [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell)
* class [`IChartDataWorkbook`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdataworkbook)
* module [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)