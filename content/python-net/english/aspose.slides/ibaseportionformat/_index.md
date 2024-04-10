---
title: IBasePortionFormat
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ibaseportionformat/
---


IBasePortionFormat class

This class contains the text portion formatting properties. Unlike :py:class:`aspose.slides.IPortionFormatEffectiveData`, all properties of this class are writeable.

The IBasePortionFormat type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [line_format](/slides/python-net/aspose.slides/ibaseportionformat/line_format/) | Returns the LineFormat properties for text outlining. No inheritance applied.<br/>            Read-only :py:class:`aspose.slides.ILineFormat`. |
| [fill_format](/slides/python-net/aspose.slides/ibaseportionformat/fill_format/) | Returns the text FillFormat properties. No inheritance applied.<br/>            Read-only :py:class:`aspose.slides.IFillFormat`. |
| [effect_format](/slides/python-net/aspose.slides/ibaseportionformat/effect_format/) | Returns the text EffectFormat properties. No inheritance applied.<br/>            Read-only :py:class:`aspose.slides.IEffectFormat`. |
| [highlight_color](/slides/python-net/aspose.slides/ibaseportionformat/highlight_color/) | Returns the color used to highlight a text. No inheritance applied.<br/>            Read-only :py:class:`aspose.slides.IColorFormat`. |
| [underline_line_format](/slides/python-net/aspose.slides/ibaseportionformat/underline_line_format/) | Returns the LineFormat properties used to outline underline line. No inheritance applied.<br/>            Read-only :py:class:`aspose.slides.ILineFormat`. |
| [underline_fill_format](/slides/python-net/aspose.slides/ibaseportionformat/underline_fill_format/) | Returns the underline line FillFormat properties. No inheritance applied.<br/>            Read-only :py:class:`aspose.slides.IFillFormat`. |
| [font_bold](/slides/python-net/aspose.slides/ibaseportionformat/font_bold/) | Determines whether the font is bold. No inheritance applied.<br/>            Read/write :py:enum:`aspose.slides.NullableBool`. |
| [font_italic](/slides/python-net/aspose.slides/ibaseportionformat/font_italic/) | Determines whether the font is itallic. No inheritance applied.<br/>            Read/write :py:enum:`aspose.slides.NullableBool`. |
| [kumimoji](/slides/python-net/aspose.slides/ibaseportionformat/kumimoji/) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied.<br/>            Read/write :py:enum:`aspose.slides.NullableBool`. |
| [normalise_height](/slides/python-net/aspose.slides/ibaseportionformat/normalise_height/) | Determines whether the height of a text should be normalized. No inheritance applied.<br/>            Read/write :py:enum:`aspose.slides.NullableBool`. |
| [proof_disabled](/slides/python-net/aspose.slides/ibaseportionformat/proof_disabled/) | Determines whether the text shouldn't be proofed. No inheritance applied.<br/>            Read/write :py:enum:`aspose.slides.NullableBool`. |
| [font_underline](/slides/python-net/aspose.slides/ibaseportionformat/font_underline/) | Returns or sets the text underline type. No inheritance applied.<br/>            Read/write :py:enum:`aspose.slides.TextUnderlineType`. |
| [text_cap_type](/slides/python-net/aspose.slides/ibaseportionformat/text_cap_type/) | Returns or sets the type of text capitalization. No inheritance applied.<br/>            Read/write :py:enum:`aspose.slides.TextCapType`. |
| [strikethrough_type](/slides/python-net/aspose.slides/ibaseportionformat/strikethrough_type/) | Returns or sets the strikethrough type of a text. No inheritance applied.<br/>            Read/write :py:enum:`aspose.slides.TextStrikethroughType`. |
| [is_hard_underline_line](/slides/python-net/aspose.slides/ibaseportionformat/is_hard_underline_line/) | Determines whether the underline style has own LineFormat properties or inherits it<br/>            from the LineFormat properties of the text.<br/>            Read/write :py:enum:`aspose.slides.NullableBool`. |
| [is_hard_underline_fill](/slides/python-net/aspose.slides/ibaseportionformat/is_hard_underline_fill/) | Determines whether the underline style has own FillFormat properties or inherits it<br/>            from the FillFormat properties of the text.<br/>            Read/write :py:enum:`aspose.slides.NullableBool`. |
| [font_height](/slides/python-net/aspose.slides/ibaseportionformat/font_height/) | Returns or sets the font height of a portion.<br/>            **float.NaN** means height is undefined and should be inherited from the Master.<br/>            Read/write :py:class:`float`. |
| [latin_font](/slides/python-net/aspose.slides/ibaseportionformat/latin_font/) | Returns or sets the Latin font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Read/write :py:class:`aspose.slides.IFontData`. |
| [east_asian_font](/slides/python-net/aspose.slides/ibaseportionformat/east_asian_font/) | Returns or sets the East Asian font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Read/write :py:class:`aspose.slides.IFontData`. |
| [complex_script_font](/slides/python-net/aspose.slides/ibaseportionformat/complex_script_font/) | Returns or sets the complex script font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Read/write :py:class:`aspose.slides.IFontData`. |
| [symbol_font](/slides/python-net/aspose.slides/ibaseportionformat/symbol_font/) | Returns or sets the symbolic font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Read/write :py:class:`aspose.slides.IFontData`. |
| [escapement](/slides/python-net/aspose.slides/ibaseportionformat/escapement/) | Returns or sets the superscript or subscript text.<br/>            Value from -100% (subscript) to 100% (superscript).<br/>            **float.NaN** means value is undefined and should be inherited from the Master.<br/>            Read/write :py:class:`float`. |
| [kerning_minimal_size](/slides/python-net/aspose.slides/ibaseportionformat/kerning_minimal_size/) | Returns or sets the minimal font size, for which kerning should be switched on.<br/>            **float.NaN** means value is undefined and should be inherited from the Master.<br/>            Read/write :py:class:`float`. |
| [language_id](/slides/python-net/aspose.slides/ibaseportionformat/language_id/) | Returns or sets the Id of a proofing language. Used for checking spelling and grammar.<br/>            Read/write :py:class:`System.String`. |
| [alternative_language_id](/slides/python-net/aspose.slides/ibaseportionformat/alternative_language_id/) | Returns or sets the Id of an alternative language.<br/>            Read/write :py:class:`System.String`. |
| [spacing](/slides/python-net/aspose.slides/ibaseportionformat/spacing/) | Returns or sets the intercharacter spacing increment.<br/>            **float.NaN** means value is undefined and should be inherited from the Master.<br/>            Read/write :py:class:`float`. |


### Remarks


This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that
            no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".


In order to get the effective formatting parameter values including inherited you need to use 
 method 
            which returns a 
 instance.



