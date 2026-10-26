---
title: is_visible property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/idatalabelcollection/is_visible/
weight: 120
---
## is_visible 属性
False 表示数据标签默认不可见（因此所有 
            Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat 属性为 false).
            只读 **bool**.


### 备注

如果数据标签默认可见，您可以使用 Hide() 方法将其默认隐藏。
            但如果数据标签默认不可见（IsVisible 为 false），您可以将数据标签 "默认
            可见" 并通过将 DefaultDataLabelFormat 属性的 Show*-flags (ShowValue, ...) 设置为 true 状态。

### 定义:
```python
@property
def is_visible(self):
    ...
```


### 另见
* 类 [`IDataLabelCollection`](/slides/python-net/zh/aspose.slides.charts/idatalabelcollection)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)