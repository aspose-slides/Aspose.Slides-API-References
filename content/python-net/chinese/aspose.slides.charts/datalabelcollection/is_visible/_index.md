---
title: is_visible property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/datalabelcollection/is_visible/
weight: 120
---
## is_visible 属性
False 表示数据标签默认不可见（并且
            Show*-标志（ShowValue，...） of the DefaultDataLabelFormat property 均为 false）。
            只读 **bool**。

### 备注

如果数据标签默认可见，您可以使用 Hide() 方法将其默认隐藏。
            但如果数据标签默认不可见（IsVisible 为 false），您可以通过将 DefaultDataLabelFormat property 的 Show*-标志（ShowValue，...）设置为 true 状态，使数据标签“默认可见”。

### 定义：
```python
@property
def is_visible(self):
    ...
```

### 另见
* 类 [`DataLabelCollection`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)