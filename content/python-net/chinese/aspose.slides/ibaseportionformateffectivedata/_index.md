---
title: IBasePortionFormatEffectiveData class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData 类

用于包含有效文本段落格式属性的不可变对象的基接口。

IBasePortionFormatEffectiveData 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`line_format`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/line_format/) | 返回文本轮廓的 LineFormat 属性。<br/>            只读 [`ILineFormatEffectiveData`](/slides/python-net/zh/aspose.slides/ilineformateffectivedata). |
| [`fill_format`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/fill_format/) | 返回文本的 FillFormat 属性。<br/>            只读 [`IFillFormatEffectiveData`](/slides/python-net/zh/aspose.slides/ifillformateffectivedata). |
| [`effect_format`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/effect_format/) | 返回文本的 EffectFormat 属性。<br/>            只读 [`IEffectFormatEffectiveData`](/slides/python-net/zh/aspose.slides/ieffectformateffectivedata). |
| [`highlight_color`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/highlight_color/) | 返回用于突出显示文本的颜色。<br/>            只读 [`Color`](/slides/python-net/zh/aspose.slides/color). |
| [`underline_line_format`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/underline_line_format/) | 返回用于描边下划线的 LineFormat 属性。<br/>            只读 [`ILineFormatEffectiveData`](/slides/python-net/zh/aspose.slides/ilineformateffectivedata). |
| [`underline_fill_format`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/underline_fill_format/) | 返回下划线的 FillFormat 属性。<br/>            只读 [`IFillFormatEffectiveData`](/slides/python-net/zh/aspose.slides/ifillformateffectivedata). |
| [`font_bold`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/font_bold/) | 确定字体是否加粗。<br/>            只读 **bool**. |
| [`font_italic`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/font_italic/) | 确定字体是否斜体。<br/>            只读 **bool**. |
| [`kumimoji`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/kumimoji/) | 确定数字是否应忽略文本东亚语言特定的垂直文本布局。<br/>            只读 **bool**. |
| [`normalise_height`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/normalise_height/) | 确定文本高度是否应标准化。<br/>            只读 **bool**. |
| [`proof_disabled`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/proof_disabled/) | 确定文本是否不进行校对。<br/>            只读 **bool**. |
| [`font_underline`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/font_underline/) | 返回文本下划线类型。<br/>            只读 [`TextUnderlineType`](/slides/python-net/zh/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/text_cap_type/) | 返回文本的大小写类型。<br/>            只读 [`TextCapType`](/slides/python-net/zh/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/strikethrough_type/) | 返回文本的删除线类型。<br/>            只读 [`TextStrikethroughType`](/slides/python-net/zh/aspose.slides/textstrikethroughtype). |
| [`smart_tag_clean`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/smart_tag_clean/) | 确定是否应清除智能标签。<br/>            只读 **bool**. |
| [`is_hard_underline_line`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/is_hard_underline_line/) | 确定下划线样式是否拥有自己的 LineFormat 属性，或从文本的 LineFormat 属性继承。<br/>            只读 **bool**. |
| [`is_hard_underline_fill`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/is_hard_underline_fill/) | 确定下划线样式是否拥有自己的 FillFormat 属性，或从文本的 FillFormat 属性继承。<br/>            只读 **bool**. |
| [`font_height`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/font_height/) | 返回文本段落的字体高度，单位为磅。<br/>            只读 **float**. |
| [`latin_font`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/latin_font/) | 返回拉丁字体信息。<br/>            只读 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/east_asian_font/) | 返回东亚字体信息。<br/>            只读 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/complex_script_font/) | 返回复杂脚本字体信息。<br/>            只读 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/symbol_font/) | 返回符号字体信息。<br/>            只读 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/escapement/) | 返回上标或下标文本。值范围从 -100%（下标）到 100%（上标）。<br/>            只读 **float**. |
| [`kerning_minimal_size`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/kerning_minimal_size/) | 返回应开启字距调整的最小字体大小。<br/>            只读 **float**. |
| [`language_id`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/language_id/) | 返回语言的 Id。<br/>            只读 **str**. |
| [`alternative_language_id`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/alternative_language_id/) | 返回备用语言的 Id。<br/>            只读 **str**. |
| [`spacing`](/slides/python-net/zh/aspose.slides/ibaseportionformateffectivedata/spacing/) | 返回字符间距增量，单位为磅。<br/>            只读 **float**. |

### 另请参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)