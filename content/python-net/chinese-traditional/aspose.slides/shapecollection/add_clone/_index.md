---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
建立指定圖形的副本，並將其添加到圖形集合的末端。
            複製的圖形保留原始圖形的位置和大小。

### 回傳

新建立的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。



```python
def add_clone(self, source_shape):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | 要複製的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。 |


## add_clone(self, source_shape, x, y) {#ishape-float-float}
建立指定圖形的副本，並將其添加到圖形集合的末端。
            新圖形保留 `source_shape` 的寬度和高度。

### 回傳

新建立的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。



```python
def add_clone(self, source_shape, x, y):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | 要複製的圖形。 |
| x | **float** | 新圖形框架的 x 座標（以點為單位）。 |
| y | **float** | 新圖形框架的 y 座標（以點為單位）。 |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
建立指定圖形的副本，並將其添加到圖形集合的末端。

### 回傳

新建立的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | 要複製的圖形。 |
| x | **float** | 新圖形框架的 x 座標（以點為單位）。 |
| y | **float** | 新圖形框架的 y 座標（以點為單位）。 |
| width | **float** | 新圖形框架的寬度（以點為單位）。 |
| height | **float** | 新圖形框架的高度（以點為單位）。 |



### 另請參閱
* 類別 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)