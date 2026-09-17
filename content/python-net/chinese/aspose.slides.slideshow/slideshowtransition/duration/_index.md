---
title: duration property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.slideshow/slideshowtransition/duration/
weight: 40
---
## duration 属性
获取或设置幻灯片转换效果的 duration（以毫秒为单位）。
            读/写 **int**。


### 备注

对应于 PresentationML 架构中 `p:transition` 元素的 `p14:dur` 属性。
            如果未设置，则 duration 将根据 [`SlideShowTransition.speed`](/slides/python-net/zh/aspose.slides.slideshow/slideshowtransition/speed) 属性和转换类型自动确定。

### 定义:
```python
@property
def duration(self):
    ...

@duration.setter
def duration(self, value):
    ...
```


### 另请参见
* 类 [`SlideShowTransition`](/slides/python-net/zh/aspose.slides.slideshow/slideshowtransition)
* 模块 [`aspose.slides.slideshow`](/slides/python-net/zh/aspose.slides.slideshow)
* 库 [`Aspose.Slides`](/slides/python-net)