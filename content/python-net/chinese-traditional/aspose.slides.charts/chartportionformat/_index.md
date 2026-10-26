---
title: ChartPortionFormat class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat 類別

此類別包含在圖表中使用的圖表區段格式屬性。 與 [`IPortionFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/iportionformateffectivedata) 不同，此類別的所有屬性皆可寫入。

**Inheritance:**[`ChartPortionFormat`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat) → [`BasePortionFormat`](/slides/python-net/zh-hant/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/zh-hant/aspose.slides/pviobject)

ChartPortionFormat 類型公開以下成員：

## 屬性

| Property | 說明 |
| :- | :- |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/line_format/) | 傳回文字外框的 LineFormat 屬性。未套用繼承。<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat)。 |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/fill_format/) | 傳回文字的 FillFormat 屬性。未套用繼承。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat)。 |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/effect_format/) | 傳回文字的 EffectFormat 屬性。未套用繼承。<br/>            唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat)。 |
| [`highlight_color`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/highlight_color/) | 傳回用於突顯文字的顏色。未套用繼承。<br/>            唯讀 [`IColorFormat`](/slides/python-net/zh-hant/aspose.slides/icolorformat)。 |
| [`underline_line_format`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/underline_line_format/) | 傳回用於描繪底線的 LineFormat 屬性。未套用繼承。<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat)。 |
| [`underline_fill_format`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/underline_fill_format/) | 傳回底線的 FillFormat 屬性。未套用繼承。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat)。 |
| [`font_bold`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/font_bold/) | 決定字型是否為粗體。未套用繼承。<br/>            讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`font_italic`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/font_italic/) | 決定字型是否為斜體。未套用繼承。<br/>            讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`kumimoji`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/kumimoji/) | 決定數字是否應忽略文字東亞語系特有的垂直文字佈局。未套用繼承。<br/>            讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`normalise_height`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/normalise_height/) | 決定文字的高度是否應正規化。未套用繼承。<br/>            讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`proof_disabled`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/proof_disabled/) | 決定文字是否不進行校對。未套用繼承。<br/>            讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`font_underline`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/font_underline/) | 傳回或設定文字底線類型。未套用繼承。<br/>            讀寫 [`TextUnderlineType`](/slides/python-net/zh-hant/aspose.slides/textunderlinetype)。 |
| [`text_cap_type`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/text_cap_type/) | 傳回或設定文字大小寫類型。未套用繼承。<br/>            讀寫 [`TextCapType`](/slides/python-net/zh-hant/aspose.slides/textcaptype)。 |
| [`strikethrough_type`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/strikethrough_type/) | 傳回或設定文字刪除線類型。未套用繼承。<br/>            讀寫 [`TextStrikethroughType`](/slides/python-net/zh-hant/aspose.slides/textstrikethroughtype)。 |
| [`is_hard_underline_line`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/is_hard_underline_line/) | 決定底線樣式是否具有自己的 LineFormat 屬性，或繼承自文字的 LineFormat 屬性。<br/>            讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`is_hard_underline_fill`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/is_hard_underline_fill/) | 決定底線樣式是否具有自己的 FillFormat 屬性，或繼承自文字的 FillFormat 屬性。<br/>            讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`font_height`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/font_height/) | 傳回或設定區段的字型高度。<br/>            **float.NaN** 表示高度未定義，應從母片繼承。<br/>            讀寫 **float**。 |
| [`latin_font`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/latin_font/) | 傳回或設定 Latin 字型資訊。<br/>            Null 表示字型未定義，應從母片繼承。<br/>            讀寫 [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata)。 |
| [`east_asian_font`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/east_asian_font/) | 傳回或設定東亞字型資訊。<br/>            Null 表示字型未定義，應從母片繼承。<br/>            讀寫 [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata)。 |
| [`complex_script_font`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/complex_script_font/) | 傳回或設定複雜文字腳本字型資訊。<br/>            Null 表示字型未定義，應從母片繼承。<br/>            讀寫 [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata)。 |
| [`symbol_font`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/symbol_font/) | 傳回或設定符號字型資訊。<br/>            Null 表示字型未定義，應從母片繼承。<br/>            讀寫 [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata)。 |
| [`escapement`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/escapement/) | 傳回或設定上標或下標文字。<br/>            值範圍為 -100%（下標）至 100%（上標）。<br/>            **float.NaN** 表示值未定義，應從母片繼承。<br/>            讀寫 **float**。 |
| [`kerning_minimal_size`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/kerning_minimal_size/) | 傳回或設定應啟用字距微調的最小字型大小。<br/>            **float.NaN** 表示值未定義，應從母片繼承。<br/>            讀寫 **float**。 |
| [`language_id`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/language_id/) | 傳回或設定校對語言的 Id。用於拼寫與文法檢查。<br/>            讀寫 **str**。 |
| [`alternative_language_id`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/alternative_language_id/) | 傳回或設定替代語言的 Id。<br/>            讀寫 **str**。 |
| [`spacing`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/spacing/) | 傳回或設定字元間距增量。<br/>            **float.NaN** 表示值未定義，應從母片繼承。<br/>            讀寫 **float**。 |
| [`spell_check`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/spell_check/) | 取得或設定指示是否對文字區段啟用拼寫檢查的值。<br/>            當此屬性設為 false 時，會抑制對文字元素的拼寫檢查。<br/>            設為 true 時，允許拼寫檢查。<br/>            預設值為 `false`。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat/presentation/) |  |

### 備註

此類別用於傳回與操作針對特定區段定義的文字區段格式屬性。這表示在取得值時不會套用繼承；因此在大多數情況下，您會取得表示「未定義」的值。

若要取得包含繼承的有效格式參數值，必須使用 [`PortionFormat.get_effective`](/slides/python-net/zh-hant/aspose.slides/portionformat/get_effective) 方法，該方法傳回一個 [`IPortionFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/iportionformateffectivedata) 實例。

### 另請參閱
* 類別 [`BasePortionFormat`](/slides/python-net/zh-hant/aspose.slides/baseportionformat)
* 類別 [`ChartPortionFormat`](/slides/python-net/zh-hant/aspose.slides.charts/chartportionformat)
* 類別 [`IPortionFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/iportionformateffectivedata)
* 類別 [`PVIObject`](/slides/python-net/zh-hant/aspose.slides/pviobject)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 程式庫 [`Aspose.Slides`](/slides/python-net)