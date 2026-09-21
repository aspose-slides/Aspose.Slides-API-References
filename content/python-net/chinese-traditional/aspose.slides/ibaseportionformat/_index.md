---
title: IBasePortionFormat class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat 類別

此類別包含文字片段格式屬性。與 [`IPortionFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/iportionformateffectivedata) 不同，此類別的所有屬性皆為可寫入。

IBasePortionFormat 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/line_format/) | 回傳文字輪廓的 LineFormat 屬性。未套用繼承。<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat)。 |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/fill_format/) | 回傳文字的 FillFormat 屬性。未套用繼承。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat)。 |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/effect_format/) | 回傳文字的 EffectFormat 屬性。未套用繼承。<br/>            唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat)。 |
| [`highlight_color`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/highlight_color/) | 回傳用於突顯文字的顏色。未套用繼承。<br/>            唯讀 [`IColorFormat`](/slides/python-net/zh-hant/aspose.slides/icolorformat)。 |
| [`underline_line_format`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/underline_line_format/) | 回傳用於勾勒底線的 LineFormat 屬性。未套用繼承。<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat)。 |
| [`underline_fill_format`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/underline_fill_format/) | 回傳底線的 FillFormat 屬性。未套用繼承。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat)。 |
| [`font_bold`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/font_bold/) | 判斷字型是否為粗體。未套用繼承。<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`font_italic`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/font_italic/) | 判斷字型是否為斜體。未套用繼承。<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`kumimoji`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/kumimoji/) | 判斷數字是否應忽略文字東亞語系特定的垂直文字佈局。未套用繼承。<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`normalise_height`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/normalise_height/) | 判斷文字的高度是否應正規化。未套用繼承。<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`proof_disabled`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/proof_disabled/) | 判斷文字是否不進行校對。未套用繼承。<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`font_underline`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/font_underline/) | 回傳或設定文字底線類型。未套用繼承。<br/>            可讀寫 [`TextUnderlineType`](/slides/python-net/zh-hant/aspose.slides/textunderlinetype)。 |
| [`text_cap_type`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/text_cap_type/) | 回傳或設定文字大小寫類型。未套用繼承。<br/>            可讀寫 [`TextCapType`](/slides/python-net/zh-hant/aspose.slides/textcaptype)。 |
| [`strikethrough_type`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/strikethrough_type/) | 回傳或設定文字刪除線類型。未套用繼承。<br/>            可讀寫 [`TextStrikethroughType`](/slides/python-net/zh-hant/aspose.slides/textstrikethroughtype)。 |
| [`is_hard_underline_line`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/is_hard_underline_line/) | 判斷底線樣式是否具有自己的 LineFormat 屬性或繼承自文字的 LineFormat 屬性。<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`is_hard_underline_fill`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/is_hard_underline_fill/) | 判斷底線樣式是否具有自己的 FillFormat 屬性或繼承自文字的 FillFormat 屬性。<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`font_height`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/font_height/) | 回傳或設定片段的字型高度。<br/>            **float.NaN** 表示高度未定義，應從母版繼承。<br/>            可讀寫 **float**。 |
| [`latin_font`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/latin_font/) | 回傳或設定拉丁字型資訊。<br/>            Null 表示字型未定義，應從母版繼承。<br/>            可讀寫 [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata)。 |
| [`east_asian_font`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/east_asian_font/) | 回傳或設定東亞字型資訊。<br/>            Null 表示字型未定義，應從母版繼承。<br/>            可讀寫 [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata)。 |
| [`complex_script_font`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/complex_script_font/) | 回傳或設定複雜文字腳本字型資訊。<br/>            Null 表示字型未定義，應從母版繼承。<br/>            可讀寫 [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata)。 |
| [`symbol_font`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/symbol_font/) | 回傳或設定符號字型資訊。<br/>            Null 表示字型未定義，應從母版繼承。<br/>            可讀寫 [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata)。 |
| [`escapement`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/escapement/) | 回傳或設定上標或下標文字。<br/>            值範圍為 -100%（下標）至 100%（上標）。<br/>            **float.NaN** 表示值未定義，應從母版繼承。<br/>            可讀寫 **float**。 |
| [`kerning_minimal_size`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/kerning_minimal_size/) | 回傳或設定最小字型大小，低於此大小將啟用字距微調。<br/>            **float.NaN** 表示值未定義，應從母版繼承。<br/>            可讀寫 **float**。 |
| [`language_id`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/language_id/) | 回傳或設定校對語言的 Id。用於拼寫與文法檢查。<br/>            可讀寫 **str**。 |
| [`alternative_language_id`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/alternative_language_id/) | 回傳或設定替代語言的 Id。<br/>            可讀寫 **str**。 |
| [`spacing`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/spacing/) | 回傳或設定字元間距增量。<br/>            **float.NaN** 表示值未定義，應從母版繼承。<br/>            可讀寫 **float**。 |
| [`spell_check`](/slides/python-net/zh-hant/aspose.slides/ibaseportionformat/spell_check/) | 取得或設定是否為文字片段啟用拼寫檢查。<br/>            設為 false 時，會抑制對文字元素的拼寫檢查。<br/>            設為 true 時，允許拼寫檢查。<br/>            預設值為 `false`。 |

### 備註

此類別用於返回和操作針對特定片段定義的文字片段格式屬性。這表示在取得值時不會套用繼承，因此在大多數情況下您會取得意指「未定義」的值。

為了取得包括繼承在內的實際格式參數值，您需要使用 [`IPortionFormat.get_effective`](/slides/python-net/zh-hant/aspose.slides/iportionformat/get_effective) 方法
            其返回一個 [`IPortionFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/iportionformateffectivedata) 實例。

### 另見
* 類別 [`IPortionFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/iportionformateffectivedata)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)