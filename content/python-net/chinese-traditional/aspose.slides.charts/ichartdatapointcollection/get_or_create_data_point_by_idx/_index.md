---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
如果集合已經包含索引為 `index` 的資料點，則返回該資料點。
如果集合不包含索引為 `index`==N 的資料點
（當此集合中的資料點數量小於或等於 N 時）
則會新增缺少的資料點並返回最後一個（即具請求索引的資料點）。
例如，集合的索引為 {0, 1, 2}，請求的索引為 5。
則方法會新增缺少的資料點：{0, 1, 2, 3, 4, 5}。並返回索引為 5 的資料點。

### 返回值

返回具有請求索引的資料點。



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| index | **int** | 索引。 |



### 參見
* 類別 [`IChartDataPoint`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapoint)
* 類別 [`IChartDataPointCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdatapointcollection)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)