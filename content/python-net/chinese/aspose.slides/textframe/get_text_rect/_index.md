---
title: get_text_rect method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/textframe/get_text_rect/
weight: 10
---
## get_text_rect(self) {#}
获取由父形状的几何定义的文本矩形。

### 返回

一个 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)，它定义了文本区域。



```python
def get_text_rect(self):
    ...
```


### 备注

矩形坐标相对于父形状的左上角。

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 文本框未关联到几何形状。 |



### 另请参见
* 类 [`TextFrame`](/slides/python-net/zh/aspose.slides/textframe)
* 类 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)