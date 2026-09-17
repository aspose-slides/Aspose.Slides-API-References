---
title: reorder method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/slidecollection/reorder/
weight: 110
---
## reorder(self, index, slide) {#int-islide}
将 slide 从集合中移动到指定位置。


```python
def reorder(self, index, slide):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 目标索引。 |
| slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | 要移动的 Slide。 |


## reorder(self, index, slides) {#int-listislide}
将 slides 从集合中移动到指定位置。 Slides 将从 index 开始按它们在列表中出现的顺序放置。


```python
def reorder(self, index, slides):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 目标索引。 |
| slides | **List[ISlide]** | 要移动的 Slides。 |



### 另请参阅
* 类 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)
* 类 [`SlideCollection`](/slides/python-net/zh/aspose.slides/slidecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)