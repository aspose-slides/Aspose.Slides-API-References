---
title: find_shape method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.util/slideutil/find_shape/
weight: 30
---
## find_shape(pres, alt_text) {#ipresentation-str}
在 PPTX 演示文稿中通过替代文本查找形状。

### 返回值

Shape or None.



```python
@staticmethod
def find_shape(pres, alt_text):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pres | [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) | 已扫描的演示文稿。 |
| alt_text | **str** | 形状的替代文本。 |


## find_shape(slide, alt_text) {#ibaseslide-str}
在 PPTX 演示文稿的幻灯片上通过替代文本查找形状。

### 返回值

Shape or None.



```python
@staticmethod
def find_shape(slide, alt_text):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide) | 已扫描的幻灯片。 |
| alt_text | **str** | 形状的替代文本。 |



### 另请参阅
* 类 [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide)
* 类 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)
* 类 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)
* 类 [`SlideUtil`](/slides/python-net/zh/aspose.slides.util/slideutil)
* 模块 [`aspose.slides.util`](/slides/python-net/zh/aspose.slides.util)
* 库 [`Aspose.Slides`](/slides/python-net)