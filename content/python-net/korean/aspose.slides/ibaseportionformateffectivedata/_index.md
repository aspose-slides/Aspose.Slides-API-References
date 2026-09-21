---
title: IBasePortionFormatEffectiveData class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData 클래스

효과적인 텍스트 부분 서식 속성을 포함하는 불변 객체를 위한 기본 인터페이스입니다.

## 속성

| Property | Description |
| :- | :- |
| [`line_format`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/line_format/) | Returns the LineFormat properties for text outlining.<br/>            Read-only [`ILineFormatEffectiveData`](/slides/python-net/ko/aspose.slides/ilineformateffectivedata). |
| [`fill_format`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/fill_format/) | Returns the text FillFormat properties.<br/>            Read-only [`IFillFormatEffectiveData`](/slides/python-net/ko/aspose.slides/ifillformateffectivedata). |
| [`effect_format`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/effect_format/) | Returns the text EffectFormat properties.<br/>            Read-only [`IEffectFormatEffectiveData`](/slides/python-net/ko/aspose.slides/ieffectformateffectivedata). |
| [`highlight_color`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/highlight_color/) | Returns the color used to highlight a text.<br/>            Read-only **aspose.slides.Color**. |
| [`underline_line_format`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/underline_line_format/) | Returns the LineFormat properties used to outline underline line.<br/>            Read-only [`ILineFormatEffectiveData`](/slides/python-net/ko/aspose.slides/ilineformateffectivedata). |
| [`underline_fill_format`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/underline_fill_format/) | Returns the underline line FillFormat properties.<br/>            Read-only [`IFillFormatEffectiveData`](/slides/python-net/ko/aspose.slides/ifillformateffectivedata). |
| [`font_bold`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/font_bold/) | Determines whether the font is bold.<br/>            Read-only **bool**. |
| [`font_italic`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/font_italic/) | Determines whether the font is itallic.<br/>            Read-only **bool**. |
| [`kumimoji`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/kumimoji/) | Determines whether the numbers should ignore text eastern language-specific vertical text layout.<br/>            Read-only **bool**. |
| [`normalise_height`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/normalise_height/) | Determines whether the height of a text should be normalized.<br/>            Read-only **bool**. |
| [`proof_disabled`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/proof_disabled/) | Determines whether the text shouldn't be proofed.<br/>            Read-only **bool**. |
| [`font_underline`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/font_underline/) | Returns the text underline type.<br/>            Read-only [`TextUnderlineType`](/slides/python-net/ko/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/text_cap_type/) | Returns the type of text capitalization.<br/>            Read-only [`TextCapType`](/slides/python-net/ko/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/strikethrough_type/) | Returns the strikethrough type of a text.<br/>            Read-only [`TextStrikethroughType`](/slides/python-net/ko/aspose.slides/textstrikethroughtype). |
| [`smart_tag_clean`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/smart_tag_clean/) | Determines whether the smart tag should be cleaned.<br/>            Read-only **bool**. |
| [`is_hard_underline_line`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/is_hard_underline_line/) | Determines whether the underline style has own LineFormat properties or inherits it<br/>            from the LineFormat properties of the text.<br/>            Read-only **bool**. |
| [`is_hard_underline_fill`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/is_hard_underline_fill/) | Determines whether the underline style has own FillFormat properties or inherits it<br/>            from the FillFormat properties of the text.<br/>            Read-only **bool**. |
| [`font_height`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/font_height/) | Returns the font height of the text portion, in points.<br/>            Read-only **float**. |
| [`latin_font`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/latin_font/) | Returns the Latin font info.<br/>            Read-only [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/east_asian_font/) | Returns the East Asian font info.<br/>            Read-only [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/complex_script_font/) | Returns the complex script font info.<br/>            Read-only [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/symbol_font/) | Returns the symbolic font info.<br/>            Read-only [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/escapement/) | Returns the superscript or subscript text.<br/>            Value from -100% (subscript) to 100% (superscript).<br/>            Read-only **float**. |
| [`kerning_minimal_size`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/kerning_minimal_size/) | Returns the minimal font size, for which kerning should be switched on.<br/>            Read-only **float**. |
| [`language_id`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/language_id/) | Returns the Id of a language.<br/>            Read-only **str**. |
| [`alternative_language_id`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/alternative_language_id/) | Returns the Id of an alternative language.<br/>            Read-only **str**. |
| [`spacing`](/slides/python-net/ko/aspose.slides/ibaseportionformateffectivedata/spacing/) | Returns the intercharacter spacing increment, in points.<br/>            Read-only **float**. |

### 참고
* module [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)