---
title: IParagraphFormat class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iparagraphformat/
---
## IParagraphFormat 类

此类包含段落格式属性。与 [`IParagraphFormatEffectiveData`](/slides/python-net/zh/aspose.slides/iparagraphformateffectivedata) 不同，此类的所有属性均可写。

IParagraphFormat 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`bullet`](/slides/python-net/zh/aspose.slides/iparagraphformat/bullet/) | 返回段落的项目符号格式。<br/>            只读 [`IBulletFormat`](/slides/python-net/zh/aspose.slides/ibulletformat)。 |
| [`depth`](/slides/python-net/zh/aspose.slides/iparagraphformat/depth/) | 返回或设置段落的深度。<br/>            值 0 表示未定义值。<br/>            可读写 **int**。 |
| [`alignment`](/slides/python-net/zh/aspose.slides/iparagraphformat/alignment/) | 返回或设置段落中无继承的文本对齐方式。<br/>            可读写 [`TextAlignment`](/slides/python-net/zh/aspose.slides/textalignment)。 |
| [`space_within`](/slides/python-net/zh/aspose.slides/iparagraphformat/space_within/) | 返回或设置段落中基线之间的间距。正值表示百分比，负值表示点数大小。未应用继承。<br/>            可读写 **float**。 |
| [`space_before`](/slides/python-net/zh/aspose.slides/iparagraphformat/space_before/) | 返回或设置段落中首行之前的间距，且不继承。<br/>            正值指定空白空间应占字体大小的百分比。<br/>            负值指定空白空间的点数大小。<br/>            可读写 **float**。 |
| [`space_after`](/slides/python-net/zh/aspose.slides/iparagraphformat/space_after/) | 返回或设置段落中最后一行之后的间距，且不继承。<br/>            正值指定空白空间应占字体大小的百分比。<br/>            负值指定空白空间的点数大小。<br/>            可读写 **float**。 |
| [`east_asian_line_break`](/slides/python-net/zh/aspose.slides/iparagraphformat/east_asian_line_break/) | 确定段落中是否使用东亚换行。未应用继承。<br/>            可读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`right_to_left`](/slides/python-net/zh/aspose.slides/iparagraphformat/right_to_left/) | 确定段落中是否使用从右到左书写。未应用继承。<br/>            可读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`latin_line_break`](/slides/python-net/zh/aspose.slides/iparagraphformat/latin_line_break/) | 确定段落中是否使用拉丁换行。未应用继承。<br/>            可读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`hanging_punctuation`](/slides/python-net/zh/aspose.slides/iparagraphformat/hanging_punctuation/) | 确定段落中是否使用悬挂标点。未应用继承。<br/>            可读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`margin_left`](/slides/python-net/zh/aspose.slides/iparagraphformat/margin_left/) | 返回或设置段落中左侧边距，且不继承。<br/>            可读写 **float**。 |
| [`margin_right`](/slides/python-net/zh/aspose.slides/iparagraphformat/margin_right/) | 返回或设置段落中右侧边距，且不继承。<br/>            可读写 **float**。 |
| [`indent`](/slides/python-net/zh/aspose.slides/iparagraphformat/indent/) | 返回或设置段落的首行缩进/悬挂缩进，且不继承。悬挂缩进可以使用负值定义。<br/>            可读写 **float**。 |
| [`default_tab_size`](/slides/python-net/zh/aspose.slides/iparagraphformat/default_tab_size/) | 返回或设置默认制表位大小，且不继承。<br/>            可读写 **float**。 |
| [`tabs`](/slides/python-net/zh/aspose.slides/iparagraphformat/tabs/) | 返回段落的制表位。未应用继承。<br/>            只读 [`ITabCollection`](/slides/python-net/zh/aspose.slides/itabcollection)。 |
| [`font_alignment`](/slides/python-net/zh/aspose.slides/iparagraphformat/font_alignment/) | 返回或设置段落中字体对齐方式，且不继承。<br/>            可读写 [`FontAlignment`](/slides/python-net/zh/aspose.slides/fontalignment)。 |
| [`default_portion_format`](/slides/python-net/zh/aspose.slides/iparagraphformat/default_portion_format/) | 返回段落的默认部分格式。未应用继承。<br/>            只读 [`IPortionFormat`](/slides/python-net/zh/aspose.slides/iportionformat)。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/zh/aspose.slides/iparagraphformat/get_effective/#) | 获取应用继承后的有效段落格式数据。 |

### 备注

此类用于返回和操作为特定段落定义的段落格式属性。这意味着在获取值时不应用继承，因此在大多数情况下您将得到表示“未定义”的值。

为了获取包括继承在内的有效格式参数值，您需要使用 [`IParagraphFormat.get_effective`](/slides/python-net/zh/aspose.slides/iparagraphformat/get_effective) 方法，该方法返回一个 [`IParagraphFormatEffectiveData`](/slides/python-net/zh/aspose.slides/iparagraphformateffectivedata) 实例。

### 另请参见
* 类 [`IParagraphFormatEffectiveData`](/slides/python-net/zh/aspose.slides/iparagraphformateffectivedata)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)