---
title: add_chart method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
建立新的圖表，使用範例系列資料和設定進行初始化，並將其加入形狀集合的末端。

### 返回值

新建立的 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/zh-hant/aspose.slides.charts/charttype) | 要加入的圖表類型。 |
| x | **float** | 新圖表的 x 座標（點）。 |
| y | **float** | 新圖表的 y 座標（點）。 |
| width | **float** | 圖表的寬度（點）。 |
| height | **float** | 圖表的高度（點）。 |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
建立新的圖表，使用範例系列資料和設定進行初始化，並將其加入形狀集合的末端。

### 返回值

新建立的 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/zh-hant/aspose.slides.charts/charttype) | 要加入的圖表類型。 |
| x | **float** | 新圖表的 x 座標（點）。 |
| y | **float** | 新圖表的 y 座標（點）。 |
| width | **float** | 圖表的寬度（點）。 |
| height | **float** | 圖表的高度（點）。 |
| init_with_sample | **bool** | True 以使用範例系列資料和設定初始化新圖表；<br/><br/>false 以在沒有系列且只有最小設定的情況下建立圖表，這會使建立速度更快。 |



### 另請參閱
* 列舉 [`ChartType`](/slides/python-net/zh-hant/aspose.slides.charts/charttype)
* 類別 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)