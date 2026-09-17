---
title: IBasePortionFormat class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat 类

此类包含文本段落的格式属性。与 [`IPortionFormatEffectiveData`](/slides/python-net/zh/aspose.slides/iportionformateffectivedata) 不同，本类的所有属性均可写。

IBasePortionFormat 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`line_format`](/slides/python-net/zh/aspose.slides/ibaseportionformat/line_format/) | 返回用于文本轮廓的 LineFormat 属性。未应用继承。<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/zh/aspose.slides/ibaseportionformat/fill_format/) | 返回文本 FillFormat 属性。未应用继承。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/zh/aspose.slides/ibaseportionformat/effect_format/) | 返回文本 EffectFormat 属性。未应用继承。<br/>            只读 [`IEffectFormat`](/slides/python-net/zh/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/zh/aspose.slides/ibaseportionformat/highlight_color/) | 返回用于突出显示文本的颜色。未应用继承。<br/>            只读 [`IColorFormat`](/slides/python-net/zh/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/zh/aspose.slides/ibaseportionformat/underline_line_format/) | 返回用于下划线轮廓的 LineFormat 属性。未应用继承。<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/zh/aspose.slides/ibaseportionformat/underline_fill_format/) | 返回下划线填充的 FillFormat 属性。未应用继承。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/zh/aspose.slides/ibaseportionformat/font_bold/) | 确定字体是否加粗。未应用继承。<br/>            读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/zh/aspose.slides/ibaseportionformat/font_italic/) | 确定字体是否斜体。未应用继承。<br/>            读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/zh/aspose.slides/ibaseportionformat/kumimoji/) | 确定数字是否应忽略文本的东亚语言特定垂直布局。未应用继承。<br/>            读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/zh/aspose.slides/ibaseportionformat/normalise_height/) | 确定文本的高度是否应归一化。未应用继承。<br/>            读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/zh/aspose.slides/ibaseportionformat/proof_disabled/) | 确定文本是否不进行校对。未应用继承。<br/>            读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/zh/aspose.slides/ibaseportionformat/font_underline/) | 返回或设置文本下划线类型。未应用继承。<br/>            读写 [`TextUnderlineType`](/slides/python-net/zh/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/zh/aspose.slides/ibaseportionformat/text_cap_type/) | 返回或设置文本大小写类型。未应用继承。<br/>            读写 [`TextCapType`](/slides/python-net/zh/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/zh/aspose.slides/ibaseportionformat/strikethrough_type/) | 返回或设置文本删除线类型。未应用继承。<br/>            读写 [`TextStrikethroughType`](/slides/python-net/zh/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/zh/aspose.slides/ibaseportionformat/is_hard_underline_line/) | 确定下划线样式是否拥有自己的 LineFormat 属性，或继承自文本的 LineFormat 属性。<br/>            读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/zh/aspose.slides/ibaseportionformat/is_hard_underline_fill/) | 确定下划线样式是否拥有自己的 FillFormat 属性，或继承自文本的 FillFormat 属性。<br/>            读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/zh/aspose.slides/ibaseportionformat/font_height/) | 返回或设置段落的字体高度。<br/>            **float.NaN** 表示高度未定义，应从母版继承。<br/>            读写 **float**. |
| [`latin_font`](/slides/python-net/zh/aspose.slides/ibaseportionformat/latin_font/) | 返回或设置拉丁文字体信息。<br/>            空值表示字体未定义，应从母版继承。<br/>            读写 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/zh/aspose.slides/ibaseportionformat/east_asian_font/) | 返回或设置东亚文字体信息。<br/>            空值表示字体未定义，应从母版继承。<br/>            读写 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/zh/aspose.slides/ibaseportionformat/complex_script_font/) | 返回或设置复杂脚本文字体信息。<br/>            空值表示字体未定义，应从母版继承。<br/>            读写 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/zh/aspose.slides/ibaseportionformat/symbol_font/) | 返回或设置符号文字体信息。<br/>            空值表示字体未定义，应从母版继承。<br/>            读写 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/zh/aspose.slides/ibaseportionformat/escapement/) | 返回或设置上标或下标文本。<br/>            值范围为 -100%（下标）至 100%（上标）。<br/>            **float.NaN** 表示值未定义，应从母版继承。<br/>            读写 **float**. |
| [`kerning_minimal_size`](/slides/python-net/zh/aspose.slides/ibaseportionformat/kerning_minimal_size/) | 返回或设置在开启字距调整时的最小字体大小。<br/>            **float.NaN** 表示值未定义，应从母版继承。<br/>            读写 **float**. |
| [`language_id`](/slides/python-net/zh/aspose.slides/ibaseportionformat/language_id/) | 返回或设置校对语言的 Id，用于拼写和语法检查。<br/>            读写 **str**. |
| [`alternative_language_id`](/slides/python-net/zh/aspose.slides/ibaseportionformat/alternative_language_id/) | 返回或设置备用语言的 Id。<br/>            读写 **str**. |
| [`spacing`](/slides/python-net/zh/aspose.slides/ibaseportionformat/spacing/) | 返回或设置字符间距增量。<br/>            **float.NaN** 表示值未定义，应从母版继承。<br/>            读写 **float**. |
| [`spell_check`](/slides/python-net/zh/aspose.slides/ibaseportionformat/spell_check/) | 获取或设置指示是否为文本段落启用拼写检查的值。<br/>            当此属性设为 false 时，文本元素的拼写检查被抑制。<br/>            当设为 true 时，允许拼写检查。<br/>            默认值为 `false`. |

### 备注

该类用于返回和操作为特定段落定义的文本段落格式属性。这意味着在获取值时不应用继承，因此在大多数情况下您将得到表示 “未定义” 的值。

若要获取包括继承在内的有效格式参数值，需要使用 [`IPortionFormat.get_effective`](/slides/python-net/zh/aspose.slides/iportionformat/get_effective) 方法，该方法返回一个 [`IPortionFormatEffectiveData`](/slides/python-net/zh/aspose.slides/iportionformateffectivedata) 实例。

### 另请参见
* 类 [`IPortionFormatEffectiveData`](/slides/python-net/zh/aspose.slides/iportionformateffectivedata)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)