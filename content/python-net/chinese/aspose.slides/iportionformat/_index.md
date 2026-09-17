---
title: IPortionFormat class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iportionformat/
---
## IPortionFormat 类

此类包含文本部分的格式属性。与 [`IPortionFormatEffectiveData`](/slides/python-net/zh/aspose.slides/iportionformateffectivedata) 不同，此类的所有属性都是可写的。

IPortionFormat 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`bookmark_id`](/slides/python-net/zh/aspose.slides/iportionformat/bookmark_id/) | 返回或设置书签标识符。<br/>            读/写 **str**. |
| [`smart_tag_clean`](/slides/python-net/zh/aspose.slides/iportionformat/smart_tag_clean/) | 确定是否应清除智能标签。不应用继承。<br/>            读/写 **bool**. |
| [`line_format`](/slides/python-net/zh/aspose.slides/iportionformat/line_format/) |  |
| [`fill_format`](/slides/python-net/zh/aspose.slides/iportionformat/fill_format/) |  |
| [`effect_format`](/slides/python-net/zh/aspose.slides/iportionformat/effect_format/) |  |
| [`highlight_color`](/slides/python-net/zh/aspose.slides/iportionformat/highlight_color/) |  |
| [`underline_line_format`](/slides/python-net/zh/aspose.slides/iportionformat/underline_line_format/) |  |
| [`underline_fill_format`](/slides/python-net/zh/aspose.slides/iportionformat/underline_fill_format/) |  |
| [`font_bold`](/slides/python-net/zh/aspose.slides/iportionformat/font_bold/) |  |
| [`font_italic`](/slides/python-net/zh/aspose.slides/iportionformat/font_italic/) |  |
| [`kumimoji`](/slides/python-net/zh/aspose.slides/iportionformat/kumimoji/) |  |
| [`normalise_height`](/slides/python-net/zh/aspose.slides/iportionformat/normalise_height/) |  |
| [`proof_disabled`](/slides/python-net/zh/aspose.slides/iportionformat/proof_disabled/) |  |
| [`font_underline`](/slides/python-net/zh/aspose.slides/iportionformat/font_underline/) |  |
| [`text_cap_type`](/slides/python-net/zh/aspose.slides/iportionformat/text_cap_type/) |  |
| [`strikethrough_type`](/slides/python-net/zh/aspose.slides/iportionformat/strikethrough_type/) |  |
| [`is_hard_underline_line`](/slides/python-net/zh/aspose.slides/iportionformat/is_hard_underline_line/) |  |
| [`is_hard_underline_fill`](/slides/python-net/zh/aspose.slides/iportionformat/is_hard_underline_fill/) |  |
| [`font_height`](/slides/python-net/zh/aspose.slides/iportionformat/font_height/) |  |
| [`latin_font`](/slides/python-net/zh/aspose.slides/iportionformat/latin_font/) |  |
| [`east_asian_font`](/slides/python-net/zh/aspose.slides/iportionformat/east_asian_font/) |  |
| [`complex_script_font`](/slides/python-net/zh/aspose.slides/iportionformat/complex_script_font/) |  |
| [`symbol_font`](/slides/python-net/zh/aspose.slides/iportionformat/symbol_font/) |  |
| [`escapement`](/slides/python-net/zh/aspose.slides/iportionformat/escapement/) |  |
| [`kerning_minimal_size`](/slides/python-net/zh/aspose.slides/iportionformat/kerning_minimal_size/) |  |
| [`language_id`](/slides/python-net/zh/aspose.slides/iportionformat/language_id/) |  |
| [`alternative_language_id`](/slides/python-net/zh/aspose.slides/iportionformat/alternative_language_id/) |  |
| [`spacing`](/slides/python-net/zh/aspose.slides/iportionformat/spacing/) |  |
| [`spell_check`](/slides/python-net/zh/aspose.slides/iportionformat/spell_check/) |  |
| [`hyperlink_click`](/slides/python-net/zh/aspose.slides/iportionformat/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/zh/aspose.slides/iportionformat/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/zh/aspose.slides/iportionformat/hyperlink_manager/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/zh/aspose.slides/iportionformat/get_effective/#) | 获取在应用继承后的有效部分格式化数据。 |

### 备注

此类用于返回和操作为特定部分定义的文本部分格式化属性。这意味着在获取值时不应用继承，因此在大多数情况下您将得到表示“未定义”的值。

为了获取包括继承在内的有效格式化参数值，您需要使用 [`IPortionFormat.get_effective`](/slides/python-net/zh/aspose.slides/iportionformat/get_effective) 方法，该方法返回一个 [`IPortionFormatEffectiveData`](/slides/python-net/zh/aspose.slides/iportionformateffectivedata) 实例。

### 另见
* 类 [`IPortionFormatEffectiveData`](/slides/python-net/zh/aspose.slides/iportionformateffectivedata)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)