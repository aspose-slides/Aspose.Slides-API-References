---
title: IPortionFormat class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/iportionformat/
---
## IPortionFormat 類別

此類別包含文字段落格式屬性。與 [`IPortionFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/iportionformateffectivedata) 不同，此類別的所有屬性皆可寫入。

IPortionFormat 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`bookmark_id`](/slides/python-net/zh-hant/aspose.slides/iportionformat/bookmark_id/) | 取得或設定書籤識別碼。<br/>            Read/write **str**. |
| [`smart_tag_clean`](/slides/python-net/zh-hant/aspose.slides/iportionformat/smart_tag_clean/) | 決定是否應清除智慧標記。未套用繼承。<br/>            Read/write **bool**. |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/iportionformat/line_format/) |  |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/iportionformat/fill_format/) |  |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/iportionformat/effect_format/) |  |
| [`highlight_color`](/slides/python-net/zh-hant/aspose.slides/iportionformat/highlight_color/) |  |
| [`underline_line_format`](/slides/python-net/zh-hant/aspose.slides/iportionformat/underline_line_format/) |  |
| [`underline_fill_format`](/slides/python-net/zh-hant/aspose.slides/iportionformat/underline_fill_format/) |  |
| [`font_bold`](/slides/python-net/zh-hant/aspose.slides/iportionformat/font_bold/) |  |
| [`font_italic`](/slides/python-net/zh-hant/aspose.slides/iportionformat/font_italic/) |  |
| [`kumimoji`](/slides/python-net/zh-hant/aspose.slides/iportionformat/kumimoji/) |  |
| [`normalise_height`](/slides/python-net/zh-hant/aspose.slides/iportionformat/normalise_height/) |  |
| [`proof_disabled`](/slides/python-net/zh-hant/aspose.slides/iportionformat/proof_disabled/) |  |
| [`font_underline`](/slides/python-net/zh-hant/aspose.slides/iportionformat/font_underline/) |  |
| [`text_cap_type`](/slides/python-net/zh-hant/aspose.slides/iportionformat/text_cap_type/) |  |
| [`strikethrough_type`](/slides/python-net/zh-hant/aspose.slides/iportionformat/strikethrough_type/) |  |
| [`is_hard_underline_line`](/slides/python-net/zh-hant/aspose.slides/iportionformat/is_hard_underline_line/) |  |
| [`is_hard_underline_fill`](/slides/python-net/zh-hant/aspose.slides/iportionformat/is_hard_underline_fill/) |  |
| [`font_height`](/slides/python-net/zh-hant/aspose.slides/iportionformat/font_height/) |  |
| [`latin_font`](/slides/python-net/zh-hant/aspose.slides/iportionformat/latin_font/) |  |
| [`east_asian_font`](/slides/python-net/zh-hant/aspose.slides/iportionformat/east_asian_font/) |  |
| [`complex_script_font`](/slides/python-net/zh-hant/aspose.slides/iportionformat/complex_script_font/) |  |
| [`symbol_font`](/slides/python-net/zh-hant/aspose.slides/iportionformat/symbol_font/) |  |
| [`escapement`](/slides/python-net/zh-hant/aspose.slides/iportionformat/escapement/) |  |
| [`kerning_minimal_size`](/slides/python-net/zh-hant/aspose.slides/iportionformat/kerning_minimal_size/) |  |
| [`language_id`](/slides/python-net/zh-hant/aspose.slides/iportionformat/language_id/) |  |
| [`alternative_language_id`](/slides/python-net/zh-hant/aspose.slides/iportionformat/alternative_language_id/) |  |
| [`spacing`](/slides/python-net/zh-hant/aspose.slides/iportionformat/spacing/) |  |
| [`spell_check`](/slides/python-net/zh-hant/aspose.slides/iportionformat/spell_check/) |  |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/iportionformat/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/iportionformat/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/iportionformat/hyperlink_manager/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/zh-hant/aspose.slides/iportionformat/get_effective/#) | 取得套用繼承的有效段落格式化資料。 |

### 備註

此類別用於返回與操作針對特定段落定義的文字段落格式屬性。這表示在取得值時不會套用繼承，因此在大多數情況下您會得到意義為「未定義」的值。

為了取得包括繼承在內的有效格式參數值，您需要使用 [`IPortionFormat.get_effective`](/slides/python-net/zh-hant/aspose.slides/iportionformat/get_effective) 方法，該方法會返回一個 [`IPortionFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/iportionformateffectivedata) 實例。

### 另請參閱
* 類別 [`IPortionFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/iportionformateffectivedata)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)