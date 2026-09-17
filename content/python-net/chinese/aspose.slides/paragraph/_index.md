---
title: Paragraph class
second_title: Aspose.Slides 的 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/paragraph/
---
## Paragraph 类

表示一段文本。

Paragraph 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides/paragraph/__init__/#) | 使用默认属性初始化 Paragraph 类的新实例。 |
| [`__init__(self, para)`](/slides/python-net/zh/aspose.slides/paragraph/__init__/#paragraph) | 复制构造函数，用于初始化 Paragraph 类的新实例。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`portions`](/slides/python-net/zh/aspose.slides/paragraph/portions/) | 返回文本部分的集合。<br/>            只读 [`IPortionCollection`](/slides/python-net/zh/aspose.slides/iportioncollection)。 |
| [`paragraph_format`](/slides/python-net/zh/aspose.slides/paragraph/paragraph_format/) | 返回此段落的格式对象。<br/>            只读 [`IParagraphFormat`](/slides/python-net/zh/aspose.slides/iparagraphformat)。 |
| [`text`](/slides/python-net/zh/aspose.slides/paragraph/text/) | 获取或设置段落的纯文本。<br/>            可读写 **str**。 |
| [`end_paragraph_portion_format`](/slides/python-net/zh/aspose.slides/paragraph/end_paragraph_portion_format/) | 指定在最后一个部分之后插入另一个部分时要使用的部分属性。 |
| [`slide`](/slides/python-net/zh/aspose.slides/paragraph/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/paragraph/presentation/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh/aspose.slides/paragraph/get_image/#) | 返回段落的图像。 |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/paragraph/get_image/#float-float) | 返回使用指定比例的段落图像。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh/aspose.slides/paragraph/join_portions_with_same_formatting/#) | 合并具有相同格式的运行。 |
| [`get_rect(self)`](/slides/python-net/zh/aspose.slides/paragraph/get_rect/#) | 获取边界段落的矩形坐标。该矩形包括段落中所有行的文本，<br/>            包括空行。 |
| [`get_lines_count(self)`](/slides/python-net/zh/aspose.slides/paragraph/get_lines_count/#) | 获取段落中的行数。 |


### 另请参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)