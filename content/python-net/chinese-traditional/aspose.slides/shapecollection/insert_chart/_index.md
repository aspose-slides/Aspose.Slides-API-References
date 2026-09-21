---
title: insert_chart method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
建立一個新圖表，使用範例系列資料與設定進行初始化，
            並將其插入至指定索引的形狀集合中。

### 返回

新建立的 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart)。



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/zh-hant/aspose.slides.charts/charttype) | 要建立的圖表類型。 |
| x | **float** | 新圖表的 x 座標（以點為單位）。 |
| y | **float** | 新圖表的 y 座標（以點為單位）。 |
| width | **float** | 新圖表的寬度（以點為單位）。 |
| height | **float** | 新圖表的高度（以點為單位）。 |
| index | **int** | 在形狀集合中插入新圖表的零基索引。 |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
建立一個新圖表，使用範例系列資料與設定進行初始化，
            並將其插入至指定索引的形狀集合中。

### 返回

新建立的 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart)。



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/zh-hant/aspose.slides.charts/charttype) | 要建立的圖表類型。 |
| x | **float** | 新圖表的 x 座標（以點為單位）。 |
| y | **float** | 新圖表的 y 座標（以點為單位）。 |
| width | **float** | 新圖表的寬度（以點為單位）。 |
| height | **float** | 新圖表的高度（以點為單位）。 |
| index | **int** | 在形狀集合中插入新圖表的零基索引。 |
| init_with_sample | **bool** | True 表示使用範例系列資料與設定來初始化新圖表； <br/><br/>            false 表示建立不含任何系列且僅有最少設定的圖表，這可以加快建立速度。 |



### 相關參考
* 列舉 [`ChartType`](/slides/python-net/zh-hant/aspose.slides.charts/charttype)
* 類別 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)