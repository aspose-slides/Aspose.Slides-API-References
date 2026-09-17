---
title: BasePortionFormat class
second_title: Aspose.Slides 用于 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/baseportionformat/
---
## BasePortionFormat 类

通用文本片段格式属性。

**继承:**[`BasePortionFormat`](/slides/python-net/zh/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)

BasePortionFormat 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`line_format`](/slides/python-net/zh/aspose.slides/baseportionformat/line_format/) | 返回用于文本轮廓的 LineFormat 属性。未应用继承。<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat)。 |
| [`fill_format`](/slides/python-net/zh/aspose.slides/baseportionformat/fill_format/) | 返回文本 FillFormat 属性。未应用继承。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat)。 |
| [`effect_format`](/slides/python-net/zh/aspose.slides/baseportionformat/effect_format/) | 返回文本 EffectFormat 属性。未应用继承。<br/>            只读 [`IEffectFormat`](/slides/python-net/zh/aspose.slides/ieffectformat)。 |
| [`highlight_color`](/slides/python-net/zh/aspose.slides/baseportionformat/highlight_color/) | 返回用于突出显示文本的颜色。未应用继承。<br/>            只读 [`IColorFormat`](/slides/python-net/zh/aspose.slides/icolorformat)。 |
| [`underline_line_format`](/slides/python-net/zh/aspose.slides/baseportionformat/underline_line_format/) | 返回用于描绘下划线线的 LineFormat 属性。未应用继承。<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat)。 |
| [`underline_fill_format`](/slides/python-net/zh/aspose.slides/baseportionformat/underline_fill_format/) | 返回下划线线的 FillFormat 属性。未应用继承。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat)。 |
| [`font_bold`](/slides/python-net/zh/aspose.slides/baseportionformat/font_bold/) | 确定字体是否加粗。未应用继承。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`font_italic`](/slides/python-net/zh/aspose.slides/baseportionformat/font_italic/) | 确定字体是否斜体。未应用继承。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`kumimoji`](/slides/python-net/zh/aspose.slides/baseportionformat/kumimoji/) | 确定数字是否应忽略文本的东亚语言特定垂直布局。未应用继承。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`normalise_height`](/slides/python-net/zh/aspose.slides/baseportionformat/normalise_height/) | 确定文本的高度是否应标准化。未应用继承。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`proof_disabled`](/slides/python-net/zh/aspose.slides/baseportionformat/proof_disabled/) | 确定文本是否不进行校对。未应用继承。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`font_underline`](/slides/python-net/zh/aspose.slides/baseportionformat/font_underline/) | 返回或设置文本下划线类型。未应用继承。<br/>            读/写 [`TextUnderlineType`](/slides/python-net/zh/aspose.slides/textunderlinetype)。 |
| [`text_cap_type`](/slides/python-net/zh/aspose.slides/baseportionformat/text_cap_type/) | 返回或设置文本大小写类型。未应用继承。<br/>            读/写 [`TextCapType`](/slides/python-net/zh/aspose.slides/textcaptype)。 |
| [`strikethrough_type`](/slides/python-net/zh/aspose.slides/baseportionformat/strikethrough_type/) | 返回或设置文本的删除线类型。未应用继承。<br/>            读/写 [`TextStrikethroughType`](/slides/python-net/zh/aspose.slides/textstrikethroughtype)。 |
| [`is_hard_underline_line`](/slides/python-net/zh/aspose.slides/baseportionformat/is_hard_underline_line/) | 确定下划线样式是否拥有自己的 LineFormat 属性，或从文本的 LineFormat 属性继承。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`is_hard_underline_fill`](/slides/python-net/zh/aspose.slides/baseportionformat/is_hard_underline_fill/) | 确定下划线样式是否拥有自己的 FillFormat 属性，或从文本的 FillFormat 属性继承。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`font_height`](/slides/python-net/zh/aspose.slides/baseportionformat/font_height/) | 返回或设置部分的字体高度。<br/>            **float.NaN** 表示高度未定义，应从母版继承。<br/>            读/写 **float**。 |
| [`latin_font`](/slides/python-net/zh/aspose.slides/baseportionformat/latin_font/) | 返回或设置拉丁字体信息。<br/>            Null 表示字体未定义，应从母版继承。<br/>            读/写 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata)。 |
| [`east_asian_font`](/slides/python-net/zh/aspose.slides/baseportionformat/east_asian_font/) | 返回或设置东亚字体信息。<br/>            Null 表示字体未定义，应从母版继承。<br/>            读/写 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata)。 |
| [`complex_script_font`](/slides/python-net/zh/aspose.slides/baseportionformat/complex_script_font/) | 返回或设置复杂脚本字体信息。<br/>            Null 表示字体未定义，应从母版继承。<br/>            读/写 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata)。 |
| [`symbol_font`](/slides/python-net/zh/aspose.slides/baseportionformat/symbol_font/) | 返回或设置符号字体信息。<br/>            Null 表示字体未定义，应从母版继承。<br/>            读/写 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata)。 |
| [`escapement`](/slides/python-net/zh/aspose.slides/baseportionformat/escapement/) | 返回或设置上标或下标文本。<br/>            值范围为 -100%（下标）到 100%（上标）。<br/>            **float.NaN** 表示值未定义，应从母版继承。<br/>            读/写 **float**。 |
| [`kerning_minimal_size`](/slides/python-net/zh/aspose.slides/baseportionformat/kerning_minimal_size/) | 返回或设置应开启字距调整的最小字体大小。<br/>            **float.NaN** 表示值未定义，应从母版继承。<br/>            读/写 **float**。 |
| [`language_id`](/slides/python-net/zh/aspose.slides/baseportionformat/language_id/) | 返回或设置校对语言的 Id。用于拼写和语法检查。<br/>            读/写 **str**。 |
| [`alternative_language_id`](/slides/python-net/zh/aspose.slides/baseportionformat/alternative_language_id/) | 返回或设置备用语言的 Id。<br/>            读/写 **str**。 |
| [`spacing`](/slides/python-net/zh/aspose.slides/baseportionformat/spacing/) | 返回或设置字符间距增量。<br/>            **float.NaN** 表示值未定义，应从母版继承。<br/>            读/写 **float**。 |
| [`spell_check`](/slides/python-net/zh/aspose.slides/baseportionformat/spell_check/) | 获取或设置一个值，指示是否为文本片段启用拼写检查。<br/>            当此属性设置为 false 时，文本元素的拼写检查被抑制。<br/>            设置为 true 时，允许拼写检查。<br/>            默认值为 `false`。 |
| [`slide`](/slides/python-net/zh/aspose.slides/baseportionformat/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/baseportionformat/presentation/) |  |

### 另请参见
* 类 [`BasePortionFormat`](/slides/python-net/zh/aspose.slides/baseportionformat)
* 类 [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)