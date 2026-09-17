---
title: MathPortion class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathportion/
---
## MathPortion 类

表示内部具有数学上下文的文本片段。

**继承:**[`MathPortion`](/slides/python-net/zh/aspose.slides.mathtext/mathportion) → [`Portion`](/slides/python-net/zh/aspose.slides/portion)

MathPortion 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathportion/__init__/#) | 初始化 MathPortion 类的新实例。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`portion_format`](/slides/python-net/zh/aspose.slides.mathtext/mathportion/portion_format/) | 返回格式对象，其中包含对文本片段显式设置的格式属性，且不应用继承。<br/>只读 [`IPortionFormat`](/slides/python-net/zh/aspose.slides/iportionformat)。 |
| [`text`](/slides/python-net/zh/aspose.slides.mathtext/mathportion/text/) | 获取或设置片段的纯文本。<br/>读/写 **str**。 |
| [`field`](/slides/python-net/zh/aspose.slides.mathtext/mathportion/field/) | 返回此片段的字段。<br/>只读 [`IField`](/slides/python-net/zh/aspose.slides/ifield)。 |
| [`math_paragraph`](/slides/python-net/zh/aspose.slides.mathtext/mathportion/math_paragraph/) | 数学段落 |
| [`slide`](/slides/python-net/zh/aspose.slides.mathtext/mathportion/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.mathtext/mathportion/presentation/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathportion/add_field/#ifieldtype) | 将此片段转换为自动更新的字段。 |
| [`add_field(self, internal_string)`](/slides/python-net/zh/aspose.slides.mathtext/mathportion/add_field/#str) | 将此片段转换为自动更新的字段。 |
| [`remove_field(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathportion/remove_field/#) | 将此字段片段转换为普通片段。 |
| [`get_rect(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathportion/get_rect/#) | 获取包围片段的矩形坐标。矩形包括所有行的<br/>文本，包括空行。 |
| [`get_coordinates(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathportion/get_coordinates/#) | 获取片段起始位置的坐标。点的 X 坐标表示从包括左侧间距的第一个字符开始的片段起始位置。<br/>Y 坐标包括上侧间距。 |

### 另见
* 类 [`MathPortion`](/slides/python-net/zh/aspose.slides.mathtext/mathportion)
* 类 [`Portion`](/slides/python-net/zh/aspose.slides/portion)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)