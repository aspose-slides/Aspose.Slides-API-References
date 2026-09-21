---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
建立指定形狀的副本，並將其新增至形狀集合的末端。
    已克隆的形狀保留原始形狀的位置與大小。

### 返回

新建立的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。



```python
def add_clone(self, source_shape):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | 要克隆的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。 |


## add_clone(self, source_shape, x, y) {#ishape-float-float}
建立指定形狀的副本，並將其新增至形狀集合的末端。
    新形狀保留 `source_shape` 的寬度與高度。

### 返回

新建立的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。



```python
def add_clone(self, source_shape, x, y):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | 要克隆的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。 |
| x | **float** | 已克隆形狀框架的 x 坐標（單位：點）。 |
| y | **float** | 已克隆形狀框架的 y 坐標（單位：點）。 |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
建立指定形狀的副本，並將其新增至形狀集合的末端。

### 返回

新建立的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | 要克隆的形狀。 |
| x | **float** | 已克隆形狀框架的 x 坐標（單位：點）。 |
| y | **float** | 已克隆形狀框架的 y 坐標（單位：點）。 |
| width | **float** | 已克隆形狀框架的寬度（單位：點）。 |
| height | **float** | 已克隆形狀框架的高度（單位：點）。 |



### 另請參閱
* 類別 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)
* 類別 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)