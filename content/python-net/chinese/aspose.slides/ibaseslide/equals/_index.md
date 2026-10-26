---
title: equals method
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides/ibaseslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
确定两个 IBaseSlide 实例是否相等。
返回值根据幻灯片的结构和静态内容进行计算。
如果所有形状、样式、文本、动画以及其他设置等均相等，则两个幻灯片相等。
比较时不考虑唯一标识符的值，例如 SlideId，以及动态内容，例如日期占位符中的当前日期值。

### 返回
**true**  如果指定的 IBaseSlide 与当前的 IBaseSlide 相等；否则，**false** 。

```python
def equals(self, slide):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide) | 要与当前 IBaseSlide 比较的 IBaseSlide。 |

### 另见
* 类 [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)