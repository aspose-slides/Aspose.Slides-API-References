---
title: is_visible property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/idatalabelcollection/is_visible/
weight: 130
---
## is_visible 属性
False 表示数据标签默认不可见（因此 DefaultDataLabelFormat 属性的所有 Show*-flags（ShowValue，...）均为 false）。只读 **bool**。

### Remarks

如果数据标签默认可见，可以使用 Hide() 方法将其默认隐藏。  
但是，如果数据标签默认不可见（IsVisible 为 false），可以通过将 DefaultDataLabelFormat 属性的 Show*-flags（ShowValue，...）设置为 true 状态，使数据标签“默认可见”。

### 定义:
```python
@property
def is_visible(self):
    ...
```

### 另请参见
* 类 [`IDataLabelCollection`](/slides/python-net/zh/aspose.slides.charts/idatalabelcollection)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)