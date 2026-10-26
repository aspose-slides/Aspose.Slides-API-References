---
title: MathParagraph class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathparagraph/
---
## MathParagraph 类

数学段落，是数学块（IMathBlock）的容器

MathParagraph 类型公开以下成员：

## 构造函数

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathparagraph/__init__/#) | 初始化 MathParagraph 类的新实例。 |
| [`__init__(self, math_block)`](/slides/python-net/zh/aspose.slides.mathtext/mathparagraph/__init__/#imathblock) | 初始化 MathParagraph 类的新实例。 |

## 属性

| Property | Description |
| :- | :- |
| [`justification`](/slides/python-net/zh/aspose.slides.mathtext/mathparagraph/justification/) | Paragraph Justification <br/>            默认值: CenteredAsGroup |
| [`count`](/slides/python-net/zh/aspose.slides.mathtext/mathparagraph/count/) | 获取集合中实际包含的元素数量。<br/>            只读 **int**。 |

获取指定索引处的项。
            只读 [`IMathBlock`](/slides/python-net/zh/aspose.slides.mathtext/imathblock)。

## 索引器

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides.mathtext/mathparagraph/__getitem__/) | 要获取的项的零基索引 |

## 方法

| Method | Description |
| :- | :- |
| [`clear(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathparagraph/clear/#) | 从集合中移除所有元素。 |
| [`add(self, math_block)`](/slides/python-net/zh/aspose.slides.mathtext/mathparagraph/add/#imathblock) | 将 IMMathBlock 添加到集合末尾。 |
| [`remove(self, math_block)`](/slides/python-net/zh/aspose.slides.mathtext/mathparagraph/remove/#imathblock) | 从集合中移除特定对象的第一次出现。 |
| [`contains(self, math_block)`](/slides/python-net/zh/aspose.slides.mathtext/mathparagraph/contains/#imathblock) | 确定集合是否包含特定值。 |
| [`index_of(self, math_block)`](/slides/python-net/zh/aspose.slides.mathtext/mathparagraph/index_of/#imathblock) | 确定集合中特定 IMMathBlock 的索引。 |
| [`insert(self, index, math_block)`](/slides/python-net/zh/aspose.slides.mathtext/mathparagraph/insert/#int-imathblock) | 在指定索引处将 IMMathBlock 插入集合。 |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides.mathtext/mathparagraph/remove_at/#int) | 从集合中指定索引处移除项。 |
| [`write_as_math_ml(self, stream)`](/slides/python-net/zh/aspose.slides.mathtext/mathparagraph/write_as_math_ml/#iorawiobase) | 将此 [`MathParagraph`](/slides/python-net/zh/aspose.slides.mathtext/mathparagraph) 的内容保存为 MathML |
| [`to_latex(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathparagraph/to_latex/#) | 获取 LaTeX 格式的数学公式 |


### 另请参阅
* 类 [`IMathBlock`](/slides/python-net/zh/aspose.slides.mathtext/imathblock)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)