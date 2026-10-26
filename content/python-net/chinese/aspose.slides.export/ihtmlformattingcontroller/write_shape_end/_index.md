---
title: write_shape_end method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/
weight: 30
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，当前幻灯片图像生成将结束，插入添加的 html 片段并在前一个图像之上开始生成新图像。

```python
def write_shape_end(self, generator, shape):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/zh/aspose.slides.export/ihtmlgenerator) | 输出对象。 |
| shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | 最后渲染的 shape。 |

### 另请参见
* 类 [`IHtmlFormattingController`](/slides/python-net/zh/aspose.slides.export/ihtmlformattingcontroller)
* 类 [`IHtmlGenerator`](/slides/python-net/zh/aspose.slides.export/ihtmlgenerator)
* 类 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)