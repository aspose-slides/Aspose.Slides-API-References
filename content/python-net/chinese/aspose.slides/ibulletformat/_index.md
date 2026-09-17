---
title: IBulletFormat class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ibulletformat/
---
## IBulletFormat 类

表示段落项目符号格式属性。

IBulletFormat 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`type`](/slides/python-net/zh/aspose.slides/ibulletformat/type/) | 返回或设置没有继承的段落的项目符号类型。<br/>            读/写 [`BulletType`](/slides/python-net/zh/aspose.slides/bullettype)。 |
| [`char`](/slides/python-net/zh/aspose.slides/ibulletformat/char/) | 返回或设置没有继承的段落的项目符号字符。<br/>            读/写 **System.Char**。 |
| [`font`](/slides/python-net/zh/aspose.slides/ibulletformat/font/) | 返回或设置没有继承的段落的项目符号字体。<br/>            读/写 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata)。 |
| [`height`](/slides/python-net/zh/aspose.slides/ibulletformat/height/) | 返回或设置没有继承的段落的项目符号高度。<br/>            当值为 float.NaN 时表示项目符号从段落的第一部分继承高度。<br/>            读/写 **float**。 |
| [`color`](/slides/python-net/zh/aspose.slides/ibulletformat/color/) | 返回没有继承的段落的项目符号的颜色格式。<br/>            只读 [`IColorFormat`](/slides/python-net/zh/aspose.slides/icolorformat)。 |
| [`picture`](/slides/python-net/zh/aspose.slides/ibulletformat/picture/) | 返回没有继承的段落中用作项目符号的图片。<br/>            只读 [`ISlidesPicture`](/slides/python-net/zh/aspose.slides/islidespicture)。 |
| [`numbered_bullet_start_with`](/slides/python-net/zh/aspose.slides/ibulletformat/numbered_bullet_start_with/) | 返回或设置没有继承的编号项目符号组使用的首个数字。<br/>            读/写 **int**。 |
| [`numbered_bullet_style`](/slides/python-net/zh/aspose.slides/ibulletformat/numbered_bullet_style/) | 返回或设置没有继承的编号项目符号的样式。<br/>            读/写 [`IBulletFormat.numbered_bullet_style`](/slides/python-net/zh/aspose.slides/ibulletformat/numbered_bullet_style)。 |
| [`is_bullet_hard_color`](/slides/python-net/zh/aspose.slides/ibulletformat/is_bullet_hard_color/) | 确定项目符号是否具有自己的颜色，或从段落的第一部分继承颜色。<br/>            **NullableBool.True** 表示项目符号具有自己的颜色，**NullableBool.False** 表示项目符号从段落的第一部分继承颜色。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`is_bullet_hard_font`](/slides/python-net/zh/aspose.slides/ibulletformat/is_bullet_hard_font/) | 确定项目符号是否具有自己的字体，或从段落的第一部分继承字体。<br/>            **NullableBool.True** 表示项目符号具有自己的字体，**NullableBool.False** 表示项目符号从段落的第一部分继承字体。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/zh/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | 设置在启用项目符号时对有效段落 Indent 和 MarginLeft 的默认非零偏移（类似 PowerPoint 在启用段落项目符号/编号时的行为）。如果禁用项目符号，则仅重置段落的 Indent 和 MarginLeft（类似 PowerPoint 在禁用段落项目符号/编号时的行为）。缩进偏移相对于当前项目符号上下文 - IBulletFormat.Type、.NumberedBulletStyle 和第一部分的 FontHeight。非零缩进偏移将应用于当前段落的有效 Indent 和 MarginLeft（使结果值成为局部值）。 |
| [`get_effective(self)`](/slides/python-net/zh/aspose.slides/ibulletformat/get_effective/#) | 获取应用继承后的有效项目符号格式数据。 |

### 另请参阅
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)