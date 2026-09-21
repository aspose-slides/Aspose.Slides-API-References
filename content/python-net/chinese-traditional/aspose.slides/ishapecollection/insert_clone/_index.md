---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
建立指定圖形的副本，並將其插入圖形集合中指定的索引位置。
            克隆的圖形保留原始圖形的位置與大小。

### 回傳

新建立的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。

```python
def insert_clone(self, index, source_shape):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入克隆圖形的零基索引。 |
| source_shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | 要克隆的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。 |

## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
建立指定圖形的副本，並將其插入圖形集合中指定的索引位置。
            新的圖形保留 `source_shape` 的寬度與高度。

### 回傳

新建立的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。

```python
def insert_clone(self, index, source_shape, x, y):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入克隆圖形的零基索引。 |
| source_shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | 要克隆的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。 |
| x | **float** | 克隆圖形框架的 x 座標，以點為單位。 |
| y | **float** | 克隆圖形框架的 y 座標，以點為單位。 |

## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
建立指定圖形的副本，並將其插入圖形集合中指定的索引位置。

### 回傳

新建立的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。

```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入克隆圖形的零基索引。 |
| source_shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | 要克隆的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。 |
| x | **float** | 克隆圖形框架的 x 座標，以點為單位。 |
| y | **float** | 克隆圖形框架的 y 座標，以點為單位。 |
| width | **float** | 克隆圖形框架的寬度，以點為單位。 |
| height | **float** | 克隆圖形框架的高度，以點為單位。 |

### 另請參閱
* 類別 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)
* 類別 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)