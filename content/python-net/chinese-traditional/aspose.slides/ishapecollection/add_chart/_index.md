---
title: add_chart method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
建立一個新圖表，使用樣本系列資料和設定進行初始化，並將其加入形狀集合的末端。

### 傳回

The newly created [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/zh-hant/aspose.slides.charts/charttype) | 要加入的圖表類型。 |
| x | **float** | 新圖表的 x 座標（單位：點）。 |
| y | **float** | 新圖表的 y 座標（單位：點）。 |
| width | **float** | 圖表的寬度（單位：點）。 |
| height | **float** | 圖表的高度（單位：點）。 |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
建立一個新圖表，使用樣本系列資料和設定進行初始化，並將其加入形狀集合的末端。

### 傳回

The newly created [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/zh-hant/aspose.slides.charts/charttype) | 要加入的圖表類型。 |
| x | **float** | 新圖表的 x 座標（單位：點）。 |
| y | **float** | 新圖表的 y 座標（單位：點）。 |
| width | **float** | 圖表的寬度（單位：點）。 |
| height | **float** | 圖表的高度（單位：點）。 |
| init_with_sample | **bool** | True 代表使用樣本系列資料和設定來初始化新圖表； <br/><br/>            false 代表建立不含系列且僅有最小設定的圖表，這會使建立速度更快。 |



### 另請參閱
* 列舉 [`ChartType`](/slides/python-net/zh-hant/aspose.slides.charts/charttype)
* 類別 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart)
* 類別 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)