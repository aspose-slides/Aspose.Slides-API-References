---
title: BasePortionFormat class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/baseportionformat/
---


## BasePortionFormat class

Common text portion formatting properties.

**Inheritance:**[`BasePortionFormat`](/slides/python-net/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/aspose.slides/pviobject)

The BasePortionFormat type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`line_format`](/slides/python-net/aspose.slides/baseportionformat/line_format/) | Returns the LineFormat properties for text outlining. No inheritance applied.<br/>            Read-only [`ILineFormat`](/slides/python-net/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/aspose.slides/baseportionformat/fill_format/) | Returns the text FillFormat properties. No inheritance applied.<br/>            Read-only [`IFillFormat`](/slides/python-net/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/aspose.slides/baseportionformat/effect_format/) | Returns the text EffectFormat properties. No inheritance applied.<br/>            Read-only [`IEffectFormat`](/slides/python-net/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/aspose.slides/baseportionformat/highlight_color/) | Returns the color used to highlight a text. No inheritance applied.<br/>            Read-only [`IColorFormat`](/slides/python-net/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/aspose.slides/baseportionformat/underline_line_format/) | Returns the LineFormat properties used to outline underline line. No inheritance applied.<br/>            Read-only [`ILineFormat`](/slides/python-net/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/aspose.slides/baseportionformat/underline_fill_format/) | Returns the underline line FillFormat properties. No inheritance applied.<br/>            Read-only [`IFillFormat`](/slides/python-net/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/aspose.slides/baseportionformat/font_bold/) | Determines whether the font is bold. No inheritance applied.<br/>            Read/write [`NullableBool`](/slides/python-net/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/aspose.slides/baseportionformat/font_italic/) | Determines whether the font is itallic. No inheritance applied.<br/>            Read/write [`NullableBool`](/slides/python-net/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/aspose.slides/baseportionformat/kumimoji/) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied.<br/>            Read/write [`NullableBool`](/slides/python-net/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/aspose.slides/baseportionformat/normalise_height/) | Determines whether the height of a text should be normalized. No inheritance applied.<br/>            Read/write [`NullableBool`](/slides/python-net/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/aspose.slides/baseportionformat/proof_disabled/) | Determines whether the text shouldn't be proofed. No inheritance applied.<br/>            Read/write [`NullableBool`](/slides/python-net/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/aspose.slides/baseportionformat/font_underline/) | Returns or sets the text underline type. No inheritance applied.<br/>            Read/write [`TextUnderlineType`](/slides/python-net/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/aspose.slides/baseportionformat/text_cap_type/) | Returns or sets the type of text capitalization. No inheritance applied.<br/>            Read/write [`TextCapType`](/slides/python-net/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/aspose.slides/baseportionformat/strikethrough_type/) | Returns or sets the strikethrough type of a text. No inheritance applied.<br/>            Read/write [`TextStrikethroughType`](/slides/python-net/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/aspose.slides/baseportionformat/is_hard_underline_line/) | Determines whether the underline style has own LineFormat properties or inherits it<br/>            from the LineFormat properties of the text.<br/>            Read/write [`NullableBool`](/slides/python-net/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/aspose.slides/baseportionformat/is_hard_underline_fill/) | Determines whether the underline style has own FillFormat properties or inherits it<br/>            from the FillFormat properties of the text.<br/>            Read/write [`NullableBool`](/slides/python-net/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/aspose.slides/baseportionformat/font_height/) | Returns or sets the font height of a portion.<br/>**float.NaN**  means height is undefined and should be inherited from the Master.<br/>            Read/write **float**. |
| [`latin_font`](/slides/python-net/aspose.slides/baseportionformat/latin_font/) | Returns or sets the Latin font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Read/write [`IFontData`](/slides/python-net/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/aspose.slides/baseportionformat/east_asian_font/) | Returns or sets the East Asian font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Read/write [`IFontData`](/slides/python-net/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/aspose.slides/baseportionformat/complex_script_font/) | Returns or sets the complex script font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Read/write [`IFontData`](/slides/python-net/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/aspose.slides/baseportionformat/symbol_font/) | Returns or sets the symbolic font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Read/write [`IFontData`](/slides/python-net/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/aspose.slides/baseportionformat/escapement/) | Returns or sets the superscript or subscript text.<br/>            Value from -100% (subscript) to 100% (superscript).<br/>**float.NaN**  means value is undefined and should be inherited from the Master.<br/>            Read/write **float**. |
| [`kerning_minimal_size`](/slides/python-net/aspose.slides/baseportionformat/kerning_minimal_size/) | Returns or sets the minimal font size, for which kerning should be switched on.<br/>**float.NaN**  means value is undefined and should be inherited from the Master.<br/>            Read/write **float**. |
| [`language_id`](/slides/python-net/aspose.slides/baseportionformat/language_id/) | Returns or sets the Id of a proofing language. Used for checking spelling and grammar.<br/>            Read/write **str**. |
| [`alternative_language_id`](/slides/python-net/aspose.slides/baseportionformat/alternative_language_id/) | Returns or sets the Id of an alternative language.<br/>            Read/write **str**. |
| [`spacing`](/slides/python-net/aspose.slides/baseportionformat/spacing/) | Returns or sets the intercharacter spacing increment.<br/>**float.NaN**  means value is undefined and should be inherited from the Master.<br/>            Read/write **float**. |
| [`slide`](/slides/python-net/aspose.slides/baseportionformat/slide/) |  |
| [`presentation`](/slides/python-net/aspose.slides/baseportionformat/presentation/) |  |


### See Also
* class [`BasePortionFormat`](/slides/python-net/aspose.slides/baseportionformat)
* class [`PVIObject`](/slides/python-net/aspose.slides/pviobject)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

