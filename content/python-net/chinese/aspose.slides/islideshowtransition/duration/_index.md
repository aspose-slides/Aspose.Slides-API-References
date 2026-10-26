---
title: duration property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/islideshowtransition/duration/
weight: 40
---
## duration 属性
获取或设置 duration（以毫秒为单位）的幻灯片过渡效果。
            读/写 **int**.

### 备注

对应于 PresentationML 架构中 `p:transition` 元素的 `p14:dur` 属性。
            如果未设置，则根据 [`ISlideShowTransition.speed`](/slides/python-net/zh/aspose.slides/islideshowtransition/speed) 属性和过渡类型自动确定 duration。

### 定义:
```python
@property
def duration(self):
    ...

@duration.setter
def duration(self, value):
    ...
```

### 另见
* 类 [`ISlideShowTransition`](/slides/python-net/zh/aspose.slides/islideshowtransition)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)