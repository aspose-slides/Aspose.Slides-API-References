---
title: equals method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/masterslide/equals/
weight: 30
---
## equals(self, slide) {#ibaseslide}
确定两个 IBaseSlide 实例是否相等。  
返回值基于幻灯片的结构和静态内容计算。  
两张幻灯片相等，当所有形状、样式、文本、动画以及其他设置等全部相等时。比较不考虑唯一标识符值，例如 SlideId，以及动态内容，例如日期占位符中的当前日期值。

### 返回值

**true** 如果指定的 IBaseSlide 与当前的 IBaseSlide 相等；否则为 **false** 。

```python
def equals(self, slide):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide) | 用于与当前的 IBaseSlide 进行比较的 IBaseSlide。 |

### 另见
* 类 [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide)
* 类 [`MasterSlide`](/slides/python-net/zh/aspose.slides/masterslide)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)