---
title: BulletFormat class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/bulletformat/
---
## BulletFormat 类

表示段落项目符号格式属性。

**Inheritance:**[`BulletFormat`](/slides/python-net/zh/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)

BulletFormat 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/zh/aspose.slides/bulletformat/type/) | 返回或设置段落的项目符号类型（无继承）。<br/>            读写 [`BulletType`](/slides/python-net/zh/aspose.slides/bullettype)。 |
| [`char`](/slides/python-net/zh/aspose.slides/bulletformat/char/) | 返回或设置段落的项目符号字符（无继承）。<br/>            读写 **System.Char**。 |
| [`font`](/slides/python-net/zh/aspose.slides/bulletformat/font/) | 返回或设置段落的项目符号字体（无继承）。<br/>            读写 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata)。 |
| [`height`](/slides/python-net/zh/aspose.slides/bulletformat/height/) | 返回或设置段落的项目符号高度（无继承）。<br/>            值 float.NaN 表示项目符号从段落的第一部分继承高度。<br/>            读写 **float**。 |
| [`color`](/slides/python-net/zh/aspose.slides/bulletformat/color/) | 返回段落的项目符号的颜色格式（无继承）。<br/>            只读 [`IColorFormat`](/slides/python-net/zh/aspose.slides/icolorformat)。 |
| [`numbered_bullet_start_with`](/slides/python-net/zh/aspose.slides/bulletformat/numbered_bullet_start_with/) | 返回或设置编号项目符号组使用的起始编号（无继承）。<br/>            读写 **int**。 |
| [`numbered_bullet_style`](/slides/python-net/zh/aspose.slides/bulletformat/numbered_bullet_style/) | 返回或设置编号项目符号的样式（无继承）。<br/>            读写 [`NumberedBulletStyle`](/slides/python-net/zh/aspose.slides/numberedbulletstyle)。 |
| [`is_bullet_hard_color`](/slides/python-net/zh/aspose.slides/bulletformat/is_bullet_hard_color/) | 确定项目符号是否拥有自定义颜色，或从段落的第一部分继承颜色。<br/>            **NullableBool.True** 表示项目符号拥有自定义颜色，**NullableBool.False** 表示项目符号从段落的第一部分继承颜色。<br/>            读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`is_bullet_hard_font`](/slides/python-net/zh/aspose.slides/bulletformat/is_bullet_hard_font/) | 确定项目符号是否拥有自定义字体，或从段落的第一部分继承字体。<br/>            **NullableBool.True** 表示项目符号拥有自定义字体，**NullableBool.False** 表示项目符号从段落的第一部分继承字体。<br/>            读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`picture`](/slides/python-net/zh/aspose.slides/bulletformat/picture/) | 返回段落中用作项目符号的图片（无继承）。<br/>            只读 [`ISlidesPicture`](/slides/python-net/zh/aspose.slides/islidespicture)。 |
| [`slide`](/slides/python-net/zh/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/bulletformat/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/zh/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | 在启用项目符号时，为有效段落的缩进（Indent）和左边距（MarginLeft）设置默认的非零偏移（类似 PowerPoint 在启用段落项目符号/编号时的行为）。如果禁用项目符号，则仅重置段落的缩进和左边距（类似 PowerPoint 在禁用段落项目符号/编号时的行为）。缩进偏移根据当前项目符号上下文（IBulletFormat.Type、.NumberedBulletStyle 和第一部分的 FontHeight）进行应用。非零的缩进偏移会应用到当前段落的有效缩进和左边距（使结果值成为局部值）。 |
| [`get_effective(self)`](/slides/python-net/zh/aspose.slides/bulletformat/get_effective/#) | 获取应用继承后的有效项目符号格式数据。 |


### 另请参见
* 类 [`BulletFormat`](/slides/python-net/zh/aspose.slides/bulletformat)
* 类 [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)