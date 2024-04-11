---
title: IBasePortionFormat
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ibaseportionformat/
---


IBasePortionFormat class

This class contains the text portion formatting properties. Unlike 
[`IPortionFormatEffectiveData`](/slides/python-net/aspose.slides/iportionformateffectivedata)
, all properties of this class are writeable.

The IBasePortionFormat type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [line_format](/slides/python-net/aspose.slides/ibaseportionformat/line_format/) | Returns the LineFormat properties for text outlining. No inheritance applied.<br/>            Read-only <br/>[`ILineFormat`](/slides/python-net/aspose.slides/ilineformat)<br/>. |
| [fill_format](/slides/python-net/aspose.slides/ibaseportionformat/fill_format/) | Returns the text FillFormat properties. No inheritance applied.<br/>            Read-only <br/>[`IFillFormat`](/slides/python-net/aspose.slides/ifillformat)<br/>. |
| [effect_format](/slides/python-net/aspose.slides/ibaseportionformat/effect_format/) | Returns the text EffectFormat properties. No inheritance applied.<br/>            Read-only <br/>[`IEffectFormat`](/slides/python-net/aspose.slides/ieffectformat)<br/>. |
| [highlight_color](/slides/python-net/aspose.slides/ibaseportionformat/highlight_color/) | Returns the color used to highlight a text. No inheritance applied.<br/>            Read-only <br/>[`IColorFormat`](/slides/python-net/aspose.slides/icolorformat)<br/>. |
| [underline_line_format](/slides/python-net/aspose.slides/ibaseportionformat/underline_line_format/) | Returns the LineFormat properties used to outline underline line. No inheritance applied.<br/>            Read-only <br/>[`ILineFormat`](/slides/python-net/aspose.slides/ilineformat)<br/>. |
| [underline_fill_format](/slides/python-net/aspose.slides/ibaseportionformat/underline_fill_format/) | Returns the underline line FillFormat properties. No inheritance applied.<br/>            Read-only <br/>[`IFillFormat`](/slides/python-net/aspose.slides/ifillformat)<br/>. |
| [font_bold](/slides/python-net/aspose.slides/ibaseportionformat/font_bold/) | Determines whether the font is bold. No inheritance applied.<br/>            Read/write <br/>[`NullableBool`](/slides/python-net/aspose.slides/nullablebool)<br/>. |
| [font_italic](/slides/python-net/aspose.slides/ibaseportionformat/font_italic/) | Determines whether the font is itallic. No inheritance applied.<br/>            Read/write <br/>[`NullableBool`](/slides/python-net/aspose.slides/nullablebool)<br/>. |
| [kumimoji](/slides/python-net/aspose.slides/ibaseportionformat/kumimoji/) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied.<br/>            Read/write <br/>[`NullableBool`](/slides/python-net/aspose.slides/nullablebool)<br/>. |
| [normalise_height](/slides/python-net/aspose.slides/ibaseportionformat/normalise_height/) | Determines whether the height of a text should be normalized. No inheritance applied.<br/>            Read/write <br/>[`NullableBool`](/slides/python-net/aspose.slides/nullablebool)<br/>. |
| [proof_disabled](/slides/python-net/aspose.slides/ibaseportionformat/proof_disabled/) | Determines whether the text shouldn't be proofed. No inheritance applied.<br/>            Read/write <br/>[`NullableBool`](/slides/python-net/aspose.slides/nullablebool)<br/>. |
| [font_underline](/slides/python-net/aspose.slides/ibaseportionformat/font_underline/) | Returns or sets the text underline type. No inheritance applied.<br/>            Read/write <br/>[`TextUnderlineType`](/slides/python-net/aspose.slides/textunderlinetype)<br/>. |
| [text_cap_type](/slides/python-net/aspose.slides/ibaseportionformat/text_cap_type/) | Returns or sets the type of text capitalization. No inheritance applied.<br/>            Read/write <br/>[`TextCapType`](/slides/python-net/aspose.slides/textcaptype)<br/>. |
| [strikethrough_type](/slides/python-net/aspose.slides/ibaseportionformat/strikethrough_type/) | Returns or sets the strikethrough type of a text. No inheritance applied.<br/>            Read/write <br/>[`TextStrikethroughType`](/slides/python-net/aspose.slides/textstrikethroughtype)<br/>. |
| [is_hard_underline_line](/slides/python-net/aspose.slides/ibaseportionformat/is_hard_underline_line/) | Determines whether the underline style has own LineFormat properties or inherits it<br/>            from the LineFormat properties of the text.<br/>            Read/write <br/>[`NullableBool`](/slides/python-net/aspose.slides/nullablebool)<br/>. |
| [is_hard_underline_fill](/slides/python-net/aspose.slides/ibaseportionformat/is_hard_underline_fill/) | Determines whether the underline style has own FillFormat properties or inherits it<br/>            from the FillFormat properties of the text.<br/>            Read/write <br/>[`NullableBool`](/slides/python-net/aspose.slides/nullablebool)<br/>. |
| [font_height](/slides/python-net/aspose.slides/ibaseportionformat/font_height/) | Returns or sets the font height of a portion.<br/>            <br/>**<br/>float.NaN<br/>** <br/> means height is undefined and should be inherited from the Master.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [latin_font](/slides/python-net/aspose.slides/ibaseportionformat/latin_font/) | Returns or sets the Latin font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Read/write <br/>[`IFontData`](/slides/python-net/aspose.slides/ifontdata)<br/>. |
| [east_asian_font](/slides/python-net/aspose.slides/ibaseportionformat/east_asian_font/) | Returns or sets the East Asian font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Read/write <br/>[`IFontData`](/slides/python-net/aspose.slides/ifontdata)<br/>. |
| [complex_script_font](/slides/python-net/aspose.slides/ibaseportionformat/complex_script_font/) | Returns or sets the complex script font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Read/write <br/>[`IFontData`](/slides/python-net/aspose.slides/ifontdata)<br/>. |
| [symbol_font](/slides/python-net/aspose.slides/ibaseportionformat/symbol_font/) | Returns or sets the symbolic font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Read/write <br/>[`IFontData`](/slides/python-net/aspose.slides/ifontdata)<br/>. |
| [escapement](/slides/python-net/aspose.slides/ibaseportionformat/escapement/) | Returns or sets the superscript or subscript text.<br/>            Value from -100% (subscript) to 100% (superscript).<br/>            <br/>**<br/>float.NaN<br/>** <br/> means value is undefined and should be inherited from the Master.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [kerning_minimal_size](/slides/python-net/aspose.slides/ibaseportionformat/kerning_minimal_size/) | Returns or sets the minimal font size, for which kerning should be switched on.<br/>            <br/>**<br/>float.NaN<br/>** <br/> means value is undefined and should be inherited from the Master.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [language_id](/slides/python-net/aspose.slides/ibaseportionformat/language_id/) | Returns or sets the Id of a proofing language. Used for checking spelling and grammar.<br/>            Read/write <br/>.NET type System.String<br/>. |
| [alternative_language_id](/slides/python-net/aspose.slides/ibaseportionformat/alternative_language_id/) | Returns or sets the Id of an alternative language.<br/>            Read/write <br/>.NET type System.String<br/>. |
| [spacing](/slides/python-net/aspose.slides/ibaseportionformat/spacing/) | Returns or sets the intercharacter spacing increment.<br/>            <br/>**<br/>float.NaN<br/>** <br/> means value is undefined and should be inherited from the Master.<br/>            Read/write <br/>.NET type System.Single<br/>. |


### Remarks

This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that
            no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".


In order to get the effective formatting parameter values including inherited you need to use 
[`IPortionFormat.get_effective`](/slides/python-net/aspose.slides/iportionformat/get_effective)
 method 
            which returns a 
[`IPortionFormatEffectiveData`](/slides/python-net/aspose.slides/iportionformateffectivedata)
 instance.

