---
title: equals method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/masterhandoutslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
确定两个IBaseSlide实例是否相等。  
返回值基于幻灯片的结构和静态内容计算。  
如果所有形状、样式、文本、动画以及其他设置等均相等，则两个幻灯片相等。比较时不考虑唯一标识符值，例如SlideId，以及动态内容，例如日期占位符中的当前日期值。

### 返回值

**true**  如果指定的IBaseSlide等于当前的IBaseSlide；否则，**false** 。

```python
def equals(self, slide):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide) | 用于与当前IBaseSlide比较的IBaseSlide。 |

### 参见
* 类 [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide)
* 类 [`MasterHandoutSlide`](/slides/python-net/zh/aspose.slides/masterhandoutslide)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)