---
title: add method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
如果集合中已存在該類別，則返回它。否則從 [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell) 建立新的圖表類別並將其加入集合。

### 回傳
已加入或已存在的類別。

```python
def add(self, chart_data_cell):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell) | 用於建立圖表類別的儲存格。 |

## add(self, value) {#any}
從值建立新的 [`ChartCategory`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory) 並將其加入集合。

### 回傳
已加入 [`IChartCategory`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory)。

```python
def add(self, value):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| value | **any** | 此值。 |

### 備註
此方法會新增名稱為 AUTO_DATA 的工作表，並將所有值加入該工作表。若您使用 [`ChartDataWorkbook`](/slides/python-net/zh-hant/aspose.slides.charts/chartdataworkbook) 來新增或編輯儲存格值，請確保不要使用此工作表
            使用此方法新增的值的最大數量不得超過 16711680

### 例外情況
| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 若超過限制 |

### 另請參閱
* 類別 [`ChartCategory`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategory)
* 類別 [`ChartCategoryCollection`](/slides/python-net/zh-hant/aspose.slides.charts/chartcategorycollection)
* 類別 [`ChartDataWorkbook`](/slides/python-net/zh-hant/aspose.slides.charts/chartdataworkbook)
* 類別 [`IChartCategory`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategory)
* 類別 [`IChartDataCell`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatacell)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)