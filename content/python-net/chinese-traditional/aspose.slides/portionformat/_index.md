---
title: PortionFormat class
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/portionformat/
---
## PortionFormat 類別

This class contains the text portion formatting properties. Unlike [`IPortionFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/iportionformateffectivedata), all properties of this class are writeable.

**Inheritance:**[`PortionFormat`](/slides/python-net/zh-hant/aspose.slides/portionformat) → [`BasePortionFormat`](/slides/python-net/zh-hant/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/zh-hant/aspose.slides/pviobject)

The PortionFormat type exposes the following members:

## 建構子

| 建構式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides/portionformat/__init__/#) | Initializes a new instance of [`PortionFormat`](/slides/python-net/zh-hant/aspose.slides/portionformat) class. |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/portionformat/line_format/) | Returns the LineFormat properties for text outlining. No inheritance applied.<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/portionformat/fill_format/) | Returns the text FillFormat properties. No inheritance applied.<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/portionformat/effect_format/) | Returns the text EffectFormat properties. No inheritance applied.<br/>            唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/zh-hant/aspose.slides/portionformat/highlight_color/) | Returns the color used to highlight a text. No inheritance applied.<br/>            唯讀 [`IColorFormat`](/slides/python-net/zh-hant/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/zh-hant/aspose.slides/portionformat/underline_line_format/) | Returns the LineFormat properties used to outline underline line. No inheritance applied.<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/zh-hant/aspose.slides/portionformat/underline_fill_format/) | Returns the underline line FillFormat properties. No inheritance applied.<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/zh-hant/aspose.slides/portionformat/font_bold/) | Determines whether the font is bold. No inheritance applied.<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/zh-hant/aspose.slides/portionformat/font_italic/) | Determines whether the font is itallic. No inheritance applied.<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/zh-hant/aspose.slides/portionformat/kumimoji/) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied.<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/zh-hant/aspose.slides/portionformat/normalise_height/) | Determines whether the height of a text should be normalized. No inheritance applied.<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/zh-hant/aspose.slides/portionformat/proof_disabled/) | Determines whether the text shouldn't be proofed. No inheritance applied.<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/zh-hant/aspose.slides/portionformat/font_underline/) | Returns or sets the text underline type. No inheritance applied.<br/>            可讀寫 [`TextUnderlineType`](/slides/python-net/zh-hant/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/zh-hant/aspose.slides/portionformat/text_cap_type/) | Returns or sets the type of text capitalization. No inheritance applied.<br/>            可讀寫 [`TextCapType`](/slides/python-net/zh-hant/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/zh-hant/aspose.slides/portionformat/strikethrough_type/) | Returns or sets the strikethrough type of a text. No inheritance applied.<br/>            可讀寫 [`TextStrikethroughType`](/slides/python-net/zh-hant/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/zh-hant/aspose.slides/portionformat/is_hard_underline_line/) | Determines whether the underline style has own LineFormat properties or inherits it<br/>            from the LineFormat properties of the text.<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/zh-hant/aspose.slides/portionformat/is_hard_underline_fill/) | Determines whether the underline style has own FillFormat properties or inherits it<br/>            from the FillFormat properties of the text.<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/zh-hant/aspose.slides/portionformat/font_height/) | Returns or sets the font height of a portion.<br/>            **float.NaN**  means height is undefined and should be inherited from the Master.<br/>            可讀寫 **float**. |
| [`latin_font`](/slides/python-net/zh-hant/aspose.slides/portionformat/latin_font/) | Returns or sets the Latin font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            可讀寫 [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/zh-hant/aspose.slides/portionformat/east_asian_font/) | Returns or sets the East Asian font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            可讀寫 [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/zh-hant/aspose.slides/portionformat/complex_script_font/) | Returns or sets the complex script font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            可讀寫 [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/zh-hant/aspose.slides/portionformat/symbol_font/) | Returns or sets the symbolic font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            可讀寫 [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/zh-hant/aspose.slides/portionformat/escapement/) | Returns or sets the superscript or subscript text.<br/>            Value from -100% (subscript) to 100% (superscript).<br/>            **float.NaN**  means value is undefined and should be inherited from the Master.<br/>            可讀寫 **float**. |
| [`kerning_minimal_size`](/slides/python-net/zh-hant/aspose.slides/portionformat/kerning_minimal_size/) | Returns or sets the minimal font size, for which kerning should be switched on.<br/>            **float.NaN**  means value is undefined and should be inherited from the Master.<br/>            可讀寫 **float**. |
| [`language_id`](/slides/python-net/zh-hant/aspose.slides/portionformat/language_id/) | Returns or sets the Id of a proofing language. Used for checking spelling and grammar.<br/>            可讀寫 **str**. |
| [`alternative_language_id`](/slides/python-net/zh-hant/aspose.slides/portionformat/alternative_language_id/) | Returns or sets the Id of an alternative language.<br/>            可讀寫 **str**. |
| [`spacing`](/slides/python-net/zh-hant/aspose.slides/portionformat/spacing/) | Returns or sets the intercharacter spacing increment.<br/>            **float.NaN**  means value is undefined and should be inherited from the Master.<br/>            可讀寫 **float**. |
| [`spell_check`](/slides/python-net/zh-hant/aspose.slides/portionformat/spell_check/) | Gets or sets a value indicating whether spell checking is enabled for the text portion.<br/>            When this property is set to false, spelling checks for text elements are suppressed.<br/>            When set to true, spell checking is allowed.<br/>            Default value is `false`. |
| [`bookmark_id`](/slides/python-net/zh-hant/aspose.slides/portionformat/bookmark_id/) | Returns or sets bookmark identifier.<br/>            可讀寫 **str**. |
| [`smart_tag_clean`](/slides/python-net/zh-hant/aspose.slides/portionformat/smart_tag_clean/) | Determines whether the smart tag should be cleaned. No inheritance applied.<br/>            可讀寫 **bool**. |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/portionformat/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/portionformat/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/portionformat/hyperlink_manager/) | Hyperlinks manager.<br/>            唯讀 [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/portionformat/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/portionformat/presentation/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/zh-hant/aspose.slides/portionformat/get_effective/#) | Gets effective portion formatting data with the inheritance applied. |

### 備註

此類別用於傳回與操作針對特定部分定義的文字部分格式化屬性。這表示取得值時不會套用繼承，因此在大多數情況下您會取得表示「未定義」的值。

為了取得包括繼承在內的有效格式參數值，您需要使用 [`PortionFormat.get_effective`](/slides/python-net/zh-hant/aspose.slides/portionformat/get_effective) 方法，該方法會傳回一個 [`IPortionFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/iportionformateffectivedata) 實例。

### 另請參閱
* 類別 [`BasePortionFormat`](/slides/python-net/zh-hant/aspose.slides/baseportionformat)
* 類別 [`IPortionFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/iportionformateffectivedata)
* 類別 [`PortionFormat`](/slides/python-net/zh-hant/aspose.slides/portionformat)
* 類別 [`PVIObject`](/slides/python-net/zh-hant/aspose.slides/pviobject)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)