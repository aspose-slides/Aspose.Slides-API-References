---
title: reorder method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/slidecollection/reorder/
weight: 110
---
## reorder(self, index, slide) {#int-islide}
將投影片從集合中移動到指定位置。


```python
def reorder(self, index, slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 目標索引。 |
| slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 要移動的投影片。 |


## reorder(self, index, slides) {#int-listislide}
將多個投影片從集合中移動到指定位置。
投影片將從索引開始依照在清單中出現的順序依次放置。


```python
def reorder(self, index, slides):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 目標索引。 |
| slides | **List[ISlide]** | 要移動的投影片。 |



### 另請參閱
* 類別 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)
* 類別 [`SlideCollection`](/slides/python-net/zh-hant/aspose.slides/slidecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)