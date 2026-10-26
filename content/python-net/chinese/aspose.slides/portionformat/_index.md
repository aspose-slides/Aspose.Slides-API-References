---
title: PortionFormat class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/portionformat/
---
## PortionFormat 类

此类包含文本段落格式属性。与 [`IPortionFormatEffectiveData`](/slides/python-net/zh/aspose.slides/iportionformateffectivedata) 不同，此类的所有属性均可写。

**继承:**[`PortionFormat`](/slides/python-net/zh/aspose.slides/portionformat) → [`BasePortionFormat`](/slides/python-net/zh/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)

PortionFormat 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides/portionformat/__init__/#) | 初始化 [`PortionFormat`](/slides/python-net/zh/aspose.slides/portionformat) 类的新实例。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`line_format`](/slides/python-net/zh/aspose.slides/portionformat/line_format/) | 返回文本轮廓的 LineFormat 属性。未应用继承。<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat)。 |
| [`fill_format`](/slides/python-net/zh/aspose.slides/portionformat/fill_format/) | 返回文本 FillFormat 属性。未应用继承。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat)。 |
| [`effect_format`](/slides/python-net/zh/aspose.slides/portionformat/effect_format/) | 返回文本 EffectFormat 属性。未应用继承。<br/>            只读 [`IEffectFormat`](/slides/python-net/zh/aspose.slides/ieffectformat)。 |
| [`highlight_color`](/slides/python-net/zh/aspose.slides/portionformat/highlight_color/) | 返回用于突出显示文本的颜色。未应用继承。<br/>            只读 [`IColorFormat`](/slides/python-net/zh/aspose.slides/icolorformat)。 |
| [`underline_line_format`](/slides/python-net/zh/aspose.slides/portionformat/underline_line_format/) | 返回用于描绘下划线的 LineFormat 属性。未应用继承。<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat)。 |
| [`underline_fill_format`](/slides/python-net/zh/aspose.slides/portionformat/underline_fill_format/) | 返回下划线的 FillFormat 属性。未应用继承。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat)。 |
| [`font_bold`](/slides/python-net/zh/aspose.slides/portionformat/font_bold/) | 确定字体是否为粗体。未应用继承。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`font_italic`](/slides/python-net/zh/aspose.slides/portionformat/font_italic/) | 确定字体是否为斜体。未应用继承。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`kumimoji`](/slides/python-net/zh/aspose.slides/portionformat/kumimoji/) | 确定数字是否应忽略文本东亚语言特定的垂直布局。未应用继承。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`normalise_height`](/slides/python-net/zh/aspose.slides/portionformat/normalise_height/) | 确定文本的高度是否应标准化。未应用继承。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`proof_disabled`](/slides/python-net/zh/aspose.slides/portionformat/proof_disabled/) | 确定文本是否不进行校对。未应用继承。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`font_underline`](/slides/python-net/zh/aspose.slides/portionformat/font_underline/) | 返回或设置文本下划线类型。未应用继承。<br/>            读/写 [`TextUnderlineType`](/slides/python-net/zh/aspose.slides/textunderlinetype)。 |
| [`text_cap_type`](/slides/python-net/zh/aspose.slides/portionformat/text_cap_type/) | 返回或设置文本大小写类型。未应用继承。<br/>            读/写 [`TextCapType`](/slides/python-net/zh/aspose.slides/textcaptype)。 |
| [`strikethrough_type`](/slides/python-net/zh/aspose.slides/portionformat/strikethrough_type/) | 返回或设置文本删除线类型。未应用继承。<br/>            读/写 [`TextStrikethroughType`](/slides/python-net/zh/aspose.slides/textstrikethroughtype)。 |
| [`is_hard_underline_line`](/slides/python-net/zh/aspose.slides/portionformat/is_hard_underline_line/) | 确定下划线样式是否拥有自己的 LineFormat 属性或从文本的 LineFormat 属性继承。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`is_hard_underline_fill`](/slides/python-net/zh/aspose.slides/portionformat/is_hard_underline_fill/) | 确定下划线样式是否拥有自己的 FillFormat 属性或从文本的 FillFormat 属性继承。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`font_height`](/slides/python-net/zh/aspose.slides/portionformat/font_height/) | 返回或设置段落的字体高度。<br/>            **float.NaN** 表示高度未定义，应从母版继承。<br/>            读/写 **float**。 |
| [`latin_font`](/slides/python-net/zh/aspose.slides/portionformat/latin_font/) | 返回或设置拉丁字体信息。<br/>            Null 表示字体未定义，应从母版继承。<br/>            读/写 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata)。 |
| [`east_asian_font`](/slides/python-net/zh/aspose.slides/portionformat/east_asian_font/) | 返回或设置东亚字体信息。<br/>            Null 表示字体未定义，应从母版继承。<br/>            读/写 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata)。 |
| [`complex_script_font`](/slides/python-net/zh/aspose.slides/portionformat/complex_script_font/) | 返回或设置复杂脚本字体信息。<br/>            Null 表示字体未定义，应从母版继承。<br/>            读/写 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata)。 |
| [`symbol_font`](/slides/python-net/zh/aspose.slides/portionformat/symbol_font/) | 返回或设置符号字体信息。<br/>            Null 表示字体未定义，应从母版继承。<br/>            读/写 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata)。 |
| [`escapement`](/slides/python-net/zh/aspose.slides/portionformat/escapement/) | 返回或设置上标或下标文本。<br/>            值范围为 -100%（下标）到 100%（上标）。<br/>            **float.NaN** 表示值未定义，应从母版继承。<br/>            读/写 **float**。 |
| [`kerning_minimal_size`](/slides/python-net/zh/aspose.slides/portionformat/kerning_minimal_size/) | 返回或设置开启字距调整的最小字体大小。<br/>            **float.NaN** 表示值未定义，应从母版继承。<br/>            读/写 **float**。 |
| [`language_id`](/slides/python-net/zh/aspose.slides/portionformat/language_id/) | 返回或设置校对语言的 Id。用于拼写和语法检查。<br/>            读/写 **str**。 |
| [`alternative_language_id`](/slides/python-net/zh/aspose.slides/portionformat/alternative_language_id/) | 返回或设置替代语言的 Id。<br/>            读/写 **str**。 |
| [`spacing`](/slides/python-net/zh/aspose.slides/portionformat/spacing/) | 返回或设置字符间距增量。<br/>            **float.NaN** 表示值未定义，应从母版继承。<br/>            读/写 **float**。 |
| [`spell_check`](/slides/python-net/zh/aspose.slides/portionformat/spell_check/) | 获取或设置一个值，指示是否为文本段落启用拼写检查。<br/>            当此属性设置为 false 时，文本元素的拼写检查被抑制。<br/>            当设置为 true 时，允许拼写检查。<br/>            默认值为 `false`。 |
| [`bookmark_id`](/slides/python-net/zh/aspose.slides/portionformat/bookmark_id/) | 返回或设置书签标识符。<br/>            读/写 **str**。 |
| [`smart_tag_clean`](/slides/python-net/zh/aspose.slides/portionformat/smart_tag_clean/) | 确定是否应清除智能标签。未应用继承。<br/>            读/写 **bool**。 |
| [`hyperlink_click`](/slides/python-net/zh/aspose.slides/portionformat/hyperlink_click/) | 返回或设置鼠标点击时定义的超链接。<br/>            读/写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/zh/aspose.slides/portionformat/hyperlink_mouse_over/) | 返回或设置鼠标悬停时定义的超链接。<br/>            读/写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/zh/aspose.slides/portionformat/hyperlink_manager/) | 超链接管理器。<br/>            只读 [`IHyperlinkManager`](/slides/python-net/zh/aspose.slides/ihyperlinkmanager)。 |
| [`slide`](/slides/python-net/zh/aspose.slides/portionformat/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/portionformat/presentation/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/zh/aspose.slides/portionformat/get_effective/#) | 获取在应用继承后的有效段落格式数据。 |

### 备注

此类用于返回和操作为特定段落定义的文本段落格式属性。这意味着在获取值时不应用继承，因此在大多数情况下您将得到表示“未定义”的值。

为了获取包括继承在内的有效格式参数值，您需要使用 [`PortionFormat.get_effective`](/slides/python-net/zh/aspose.slides/portionformat/get_effective) 方法，该方法返回一个 [`IPortionFormatEffectiveData`](/slides/python-net/zh/aspose.slides/iportionformateffectivedata) 实例。

### 另请参见
* 类 [`BasePortionFormat`](/slides/python-net/zh/aspose.slides/baseportionformat)
* 类 [`IPortionFormatEffectiveData`](/slides/python-net/zh/aspose.slides/iportionformateffectivedata)
* 类 [`PortionFormat`](/slides/python-net/zh/aspose.slides/portionformat)
* 类 [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)