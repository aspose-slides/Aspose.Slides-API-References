---
title: reorder method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
將指定的 shape 移動到 shape 集合中的新位置。


```python
def reorder(self, index, shape):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 零基的目標索引，shape 將被放置於此。 |
| shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | 在集合中要移動的 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。 |


## reorder(self, index, shapes) {#int-listishape}
將指定的 shapes 在 shape 集合中移動，並從給定的 index 開始放置。


```python
def reorder(self, index, shapes):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 零基的目標索引，第一個指定的 shape 將被放置於此; <br/><br/>            其後的 shapes 按提供的順序依次放置。 |
| shapes | **List[IShape]** | 在集合中要移動的一個或多個 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) 實例。 |



### 參見
* 類別 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)
* 類別 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)