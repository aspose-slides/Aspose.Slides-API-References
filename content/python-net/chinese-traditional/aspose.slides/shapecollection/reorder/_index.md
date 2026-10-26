---
title: reorder method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
將指定的 shape 移動到 shape collection 中的新位置。

```python
def reorder(self, index, shape):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | shape 將被放置的零基目標索引。 |
| shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | 要在集合中移動的[`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。 |

## reorder(self, index, shapes) {#int-listishape}
在 shape collection 中移動指定的 shapes，並從給定的索引開始放置它們。

```python
def reorder(self, index, shapes):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 第一個指定的 shape 將被放置的零基目標索引；<br/><br/>            隨後的 shapes 按提供的順序依次放置。 |
| shapes | **List[IShape]** | 要在集合中移動的一個或多個[`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)實例。 |

### 參見
* 類別 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)