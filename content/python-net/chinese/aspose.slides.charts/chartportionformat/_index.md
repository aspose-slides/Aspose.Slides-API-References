---
title: ChartPortionFormat class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat 类

此类包含在图表中使用的图表部分格式属性。  
与[`IPortionFormatEffectiveData`](/slides/python-net/zh/aspose.slides/iportionformateffectivedata)不同，此类的所有属性都是可写的。

**继承:**[`ChartPortionFormat`](/slides/python-net/zh/aspose.slides.charts/chartportionformat) → [`BasePortionFormat`](/slides/python-net/zh/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)

ChartPortionFormat 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`line_format`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/line_format/) | 返回文本轮廓的LineFormat属性。未应用继承。<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat)。 |
| [`fill_format`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/fill_format/) | 返回文本的FillFormat属性。未应用继承。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat)。 |
| [`effect_format`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/effect_format/) | 返回文本的EffectFormat属性。未应用继承。<br/>            只读 [`IEffectFormat`](/slides/python-net/zh/aspose.slides/ieffectformat)。 |
| [`highlight_color`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/highlight_color/) | 返回用于突出显示文本的颜色。未应用继承。<br/>            只读 [`IColorFormat`](/slides/python-net/zh/aspose.slides/icolorformat)。 |
| [`underline_line_format`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/underline_line_format/) | 返回用于下划线轮廓的LineFormat属性。未应用继承。<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat)。 |
| [`underline_fill_format`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/underline_fill_format/) | 返回下划线的FillFormat属性。未应用继承。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat)。 |
| [`font_bold`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/font_bold/) | 确定字体是否为粗体。未应用继承。<br/>            可读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`font_italic`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/font_italic/) | 确定字体是否为斜体。未应用继承。<br/>            可读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`kumimoji`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/kumimoji/) | 确定数字是否应忽略文本东亚语言特定的竖排布局。未应用继承。<br/>            可读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`normalise_height`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/normalise_height/) | 确定文本的高度是否应被标准化。未应用继承。<br/>            可读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`proof_disabled`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/proof_disabled/) | 确定文本是否不应进行校对。未应用继承。<br/>            可读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`font_underline`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/font_underline/) | 返回或设置文本下划线类型。未应用继承。<br/>            可读写 [`TextUnderlineType`](/slides/python-net/zh/aspose.slides/textunderlinetype)。 |
| [`text_cap_type`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/text_cap_type/) | 返回或设置文本大小写类型。未应用继承。<br/>            可读写 [`TextCapType`](/slides/python-net/zh/aspose.slides/textcaptype)。 |
| [`strikethrough_type`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/strikethrough_type/) | 返回或设置文本删除线类型。未应用继承。<br/>            可读写 [`TextStrikethroughType`](/slides/python-net/zh/aspose.slides/textstrikethroughtype)。 |
| [`is_hard_underline_line`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/is_hard_underline_line/) | 确定下划线样式是否拥有自己的LineFormat属性，或从文本的LineFormat属性继承。<br/>            可读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`is_hard_underline_fill`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/is_hard_underline_fill/) | 确定下划线样式是否拥有自己的FillFormat属性，或从文本的FillFormat属性继承。<br/>            可读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`font_height`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/font_height/) | 返回或设置部分的字体高度。<br/>            **float.NaN** 表示高度未定义，应从母版继承。<br/>            可读写 **float**。 |
| [`latin_font`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/latin_font/) | 返回或设置拉丁字体信息。<br/>            Null 表示字体未定义，应从母版继承。<br/>            可读写 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata)。 |
| [`east_asian_font`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/east_asian_font/) | 返回或设置东亚字体信息。<br/>            Null 表示字体未定义，应从母版继承。<br/>            可读写 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata)。 |
| [`complex_script_font`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/complex_script_font/) | 返回或设置复杂脚本字体信息。<br/>            Null 表示字体未定义，应从母版继承。<br/>            可读写 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata)。 |
| [`symbol_font`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/symbol_font/) | 返回或设置符号字体信息。<br/>            Null 表示字体未定义，应从母版继承。<br/>            可读写 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata)。 |
| [`escapement`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/escapement/) | 返回或设置上标或下标文本。取值范围 -100%（下标）至 100%（上标）。<br/>            **float.NaN** 表示值未定义，应从母版继承。<br/>            可读写 **float**。 |
| [`kerning_minimal_size`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/kerning_minimal_size/) | 返回或设置最小字体大小，低于此会关闭字距调整。<br/>            **float.NaN** 表示值未定义，应从母版继承。<br/>            可读写 **float**。 |
| [`language_id`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/language_id/) | 返回或设置校对语言的 Id，用于拼写和语法检查。<br/>            可读写 **str**。 |
| [`alternative_language_id`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/alternative_language_id/) | 返回或设置备用语言的 Id。<br/>            可读写 **str**。 |
| [`spacing`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/spacing/) | 返回或设置字符间距增量。<br/>            **float.NaN** 表示值未定义，应从母版继承。<br/>            可读写 **float**。 |
| [`spell_check`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/spell_check/) | 获取或设置指示是否为文本部分启用拼写检查的值。<br/>            将此属性设为 false 时，文本元素的拼写检查将被抑制。<br/>            设为 true 时，允许拼写检查。<br/>            默认值为 `false`。 |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/chartportionformat/presentation/) |  |

### 备注

此类用于返回和操作为特定部分定义的文本部分格式属性。这意味着在获取值时未应用继承，因此在大多数情况下您会得到“未定义”的值。

若要获取包括继承在内的有效格式参数值，需要使用 [`PortionFormat.get_effective`](/slides/python-net/zh/aspose.slides/portionformat/get_effective) 方法，该方法返回一个 [`IPortionFormatEffectiveData`](/slides/python-net/zh/aspose.slides/iportionformateffectivedata) 实例。

### 另请参阅
* 类 [`BasePortionFormat`](/slides/python-net/zh/aspose.slides/baseportionformat)
* 类 [`ChartPortionFormat`](/slides/python-net/zh/aspose.slides.charts/chartportionformat)
* 类 [`IPortionFormatEffectiveData`](/slides/python-net/zh/aspose.slides/iportionformateffectivedata)
* 类 [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)