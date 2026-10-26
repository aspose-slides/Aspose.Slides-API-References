---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides 用於 Python（通過 .NET）API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
如果集合已經包含索引為 `index` 的資料點，則回傳此資料點。
如果集合不包含索引為 `index`==N 的資料點（當此集合中的資料點數量小於或等於 N 時），則會新增不足的資料點，並回傳最後一個（即具有請求索引的資料點）。
例如，集合的索引為 {0, 1, 2}，而請求的索引為 5。於是方法會新增不足的資料點：{0, 1, 2, 3, 4, 5}，並回傳索引為 5 的資料點。

### 回傳

回傳具有請求索引的資料點。

```python
def get_or_create_data_point_by_idx(self, index):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 索引。 |

### 另見
* 類別 [`ChartDataPointCollection`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatapointcollection)
* 類別 [`IChartDataPoint`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)