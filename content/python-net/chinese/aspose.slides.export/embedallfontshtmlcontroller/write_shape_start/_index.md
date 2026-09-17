---
title: write_shape_start method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/
weight: 70
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
在渲染形状之前调用。每个形状调用一次。如果此函数向 generator 写入任何内容，当前幻灯片图像生成将结束，插入已添加的 html 片段，并在前一个图像之上启动新图像。

```python
def write_shape_start(self, generator, shape):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/zh/aspose.slides.export/ihtmlgenerator) | 输出对象。 |
| shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | 即将渲染的形状。 |

### 另请参见
* 类 [`EmbedAllFontsHtmlController`](/slides/python-net/zh/aspose.slides.export/embedallfontshtmlcontroller)
* 类 [`IHtmlGenerator`](/slides/python-net/zh/aspose.slides.export/ihtmlgenerator)
* 类 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)