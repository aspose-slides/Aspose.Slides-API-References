---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
建立指定圖形的副本，並將其插入形狀集合中指定的索引位置。
已克隆的圖形保留原始圖形的位置與大小。

### 返回值

新建立的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。

```python
def insert_clone(self, index, source_shape):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 要插入已克隆圖形的零基索引。 |
| source_shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | 要克隆的[`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。 |

## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
建立指定圖形的副本，並將其插入形狀集合中指定的索引位置。
新圖形保留 `source_shape` 的寬度與高度。

### 返回值

新建立的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。

```python
def insert_clone(self, index, source_shape, x, y):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 要插入已克隆圖形的零基索引。 |
| source_shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | 要克隆的[`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。 |
| x | **float** | 已克隆圖形框架的 x 座標，單位為點。 |
| y | **float** | 已克隆圖形框架的 y 座標，單位為點。 |

## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
建立指定圖形的副本，並將其插入形狀集合中指定的索引位置。

### 返回值

新建立的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。

```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 要插入已克隆圖形的零基索引。 |
| source_shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | 要克隆的[`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。 |
| x | **float** | 已克隆圖形框架的 x 座標，單位為點。 |
| y | **float** | 已克隆圖形框架的 y 座標，單位為點。 |
| width | **float** | 已克隆圖形框架的寬度，單位為點。 |
| height | **float** | 已克隆圖形框架的高度，單位為點。 |

### 另請參閱
* 類別 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)