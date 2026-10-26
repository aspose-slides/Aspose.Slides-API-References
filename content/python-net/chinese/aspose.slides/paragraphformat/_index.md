---
title: ParagraphFormat class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/paragraphformat/
---
## ParagraphFormat 类

此类包含段落格式属性。与 [`IParagraphFormatEffectiveData`](/slides/python-net/zh/aspose.slides/iparagraphformateffectivedata) 不同，此类的所有属性均可写。

**Inheritance:**[`ParagraphFormat`](/slides/python-net/zh/aspose.slides/paragraphformat) → [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)

The ParagraphFormat type exposes the following members:

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides/paragraphformat/__init__/#) | 初始化 [`ParagraphFormat`](/slides/python-net/zh/aspose.slides/paragraphformat) 类的新实例。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`alignment`](/slides/python-net/zh/aspose.slides/paragraphformat/alignment/) | 返回或设置段落中文本对齐方式，且不继承。<br/>            读/写 [`TextAlignment`](/slides/python-net/zh/aspose.slides/textalignment)。 |
| [`space_within`](/slides/python-net/zh/aspose.slides/paragraphformat/space_within/) | 返回或设置段落中基线之间的间距。正值表示百分比，负值表示点数大小。不继承。<br/>            读/写 **float**。 |
| [`space_before`](/slides/python-net/zh/aspose.slides/paragraphformat/space_before/) | 返回或设置段落中第一行之前的间距，且不继承。<br/>            正值指定空白空间应为字体大小的百分比。<br/>            负值指定空白空间的点数大小。<br/>            读/写 **float**。 |
| [`space_after`](/slides/python-net/zh/aspose.slides/paragraphformat/space_after/) | 返回或设置段落中最后一行之后的间距，且不继承。<br/>            正值指定空白空间应为字体大小的百分比。<br/>            负值指定空白空间的点数大小。<br/>            读/写 **float**。 |
| [`east_asian_line_break`](/slides/python-net/zh/aspose.slides/paragraphformat/east_asian_line_break/) | 确定段落是否使用东亚换行规则。不继承。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`right_to_left`](/slides/python-net/zh/aspose.slides/paragraphformat/right_to_left/) | 确定段落是否使用从右到左书写。不继承。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`latin_line_break`](/slides/python-net/zh/aspose.slides/paragraphformat/latin_line_break/) | 确定段落是否使用拉丁换行规则。不继承。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`hanging_punctuation`](/slides/python-net/zh/aspose.slides/paragraphformat/hanging_punctuation/) | 确定段落是否使用悬挂标点。不继承。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`margin_left`](/slides/python-net/zh/aspose.slides/paragraphformat/margin_left/) | 返回或设置段落的左边距，且不继承。<br/>            读/写 **float**。 |
| [`margin_right`](/slides/python-net/zh/aspose.slides/paragraphformat/margin_right/) | 返回或设置段落的右边距，且不继承。<br/>            读/写 **float**。 |
| [`indent`](/slides/python-net/zh/aspose.slides/paragraphformat/indent/) | 返回或设置段落的首行缩进/悬挂缩进，且不继承。悬挂缩进可以使用负值定义。<br/>            读/写 **float**。 |
| [`default_tab_size`](/slides/python-net/zh/aspose.slides/paragraphformat/default_tab_size/) | 返回或设置默认制表位大小，且不继承。<br/>            读/写 **float**。 |
| [`tabs`](/slides/python-net/zh/aspose.slides/paragraphformat/tabs/) | 返回段落的制表位。不继承。<br/>            只读 [`ITabCollection`](/slides/python-net/zh/aspose.slides/itabcollection)。 |
| [`font_alignment`](/slides/python-net/zh/aspose.slides/paragraphformat/font_alignment/) | 返回或设置段落中的字体对齐方式，且不继承。<br/>            读/写 [`FontAlignment`](/slides/python-net/zh/aspose.slides/fontalignment)。 |
| [`slide`](/slides/python-net/zh/aspose.slides/paragraphformat/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/paragraphformat/presentation/) |  |
| [`bullet`](/slides/python-net/zh/aspose.slides/paragraphformat/bullet/) |  |
| [`depth`](/slides/python-net/zh/aspose.slides/paragraphformat/depth/) |  |
| [`default_portion_format`](/slides/python-net/zh/aspose.slides/paragraphformat/default_portion_format/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/zh/aspose.slides/paragraphformat/get_effective/#) | 获取已应用继承的有效段落格式数据。 |

### 备注

此类用于返回和操作特定段落定义的段落格式属性。这意味着在获取值时不应用继承，因此在大多数情况下您会得到表示“未定义”的值。

为了获取包括继承在内的有效格式参数值，需要使用 [`ParagraphFormat.get_effective`](/slides/python-net/zh/aspose.slides/paragraphformat/get_effective) 方法，该方法返回一个 [`IParagraphFormatEffectiveData`](/slides/python-net/zh/aspose.slides/iparagraphformateffectivedata) 实例。

### 另见
* 类 [`IParagraphFormatEffectiveData`](/slides/python-net/zh/aspose.slides/iparagraphformateffectivedata)
* 类 [`ParagraphFormat`](/slides/python-net/zh/aspose.slides/paragraphformat)
* 类 [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)