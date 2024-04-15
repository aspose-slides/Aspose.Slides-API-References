---
title: PortionFormat class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/portionformat/
---


## PortionFormat class

This class contains the text portion formatting properties. Unlike [`IPortionFormatEffectiveData`](/slides/python-net/aspose.slides/iportionformateffectivedata), all properties of this class are writeable.

**Inheritance:**[`PortionFormat`](/slides/python-net/aspose.slides/portionformat) → [`BasePortionFormat`](/slides/python-net/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/aspose.slides/pviobject)

The PortionFormat type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides/portionformat/__init__/#) | Initializes a new instance of [`PortionFormat`](/slides/python-net/aspose.slides/portionformat) class. |

## Properties

| Property | Description |
| :- | :- |
| [`as_i_presentation_component`](/slides/python-net/aspose.slides/portionformat/as_i_presentation_component/) | Allows to get base IPresentationComponent interface.<br/>            Read-only [`IPresentationComponent`](/slides/python-net/aspose.slides/ipresentationcomponent). |
| [`line_format`](/slides/python-net/aspose.slides/portionformat/line_format/) | Returns the LineFormat properties for text outlining. No inheritance applied.<br/>            Read-only [`ILineFormat`](/slides/python-net/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/aspose.slides/portionformat/fill_format/) | Returns the text FillFormat properties. No inheritance applied.<br/>            Read-only [`IFillFormat`](/slides/python-net/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/aspose.slides/portionformat/effect_format/) | Returns the text EffectFormat properties. No inheritance applied.<br/>            Read-only [`IEffectFormat`](/slides/python-net/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/aspose.slides/portionformat/highlight_color/) | Returns the color used to highlight a text. No inheritance applied.<br/>            Read-only [`IColorFormat`](/slides/python-net/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/aspose.slides/portionformat/underline_line_format/) | Returns the LineFormat properties used to outline underline line. No inheritance applied.<br/>            Read-only [`ILineFormat`](/slides/python-net/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/aspose.slides/portionformat/underline_fill_format/) | Returns the underline line FillFormat properties. No inheritance applied.<br/>            Read-only [`IFillFormat`](/slides/python-net/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/aspose.slides/portionformat/font_bold/) | Determines whether the font is bold. No inheritance applied.<br/>            Read/write [`NullableBool`](/slides/python-net/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/aspose.slides/portionformat/font_italic/) | Determines whether the font is itallic. No inheritance applied.<br/>            Read/write [`NullableBool`](/slides/python-net/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/aspose.slides/portionformat/kumimoji/) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied.<br/>            Read/write [`NullableBool`](/slides/python-net/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/aspose.slides/portionformat/normalise_height/) | Determines whether the height of a text should be normalized. No inheritance applied.<br/>            Read/write [`NullableBool`](/slides/python-net/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/aspose.slides/portionformat/proof_disabled/) | Determines whether the text shouldn't be proofed. No inheritance applied.<br/>            Read/write [`NullableBool`](/slides/python-net/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/aspose.slides/portionformat/font_underline/) | Returns or sets the text underline type. No inheritance applied.<br/>            Read/write [`TextUnderlineType`](/slides/python-net/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/aspose.slides/portionformat/text_cap_type/) | Returns or sets the type of text capitalization. No inheritance applied.<br/>            Read/write [`TextCapType`](/slides/python-net/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/aspose.slides/portionformat/strikethrough_type/) | Returns or sets the strikethrough type of a text. No inheritance applied.<br/>            Read/write [`TextStrikethroughType`](/slides/python-net/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/aspose.slides/portionformat/is_hard_underline_line/) | Determines whether the underline style has own LineFormat properties or inherits it<br/>            from the LineFormat properties of the text.<br/>            Read/write [`NullableBool`](/slides/python-net/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/aspose.slides/portionformat/is_hard_underline_fill/) | Determines whether the underline style has own FillFormat properties or inherits it<br/>            from the FillFormat properties of the text.<br/>            Read/write [`NullableBool`](/slides/python-net/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/aspose.slides/portionformat/font_height/) | Returns or sets the font height of a portion.<br/>            **float.NaN**  means height is undefined and should be inherited from the Master.<br/>            Read/write **float**. |
| [`latin_font`](/slides/python-net/aspose.slides/portionformat/latin_font/) | Returns or sets the Latin font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Read/write [`IFontData`](/slides/python-net/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/aspose.slides/portionformat/east_asian_font/) | Returns or sets the East Asian font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Read/write [`IFontData`](/slides/python-net/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/aspose.slides/portionformat/complex_script_font/) | Returns or sets the complex script font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Read/write [`IFontData`](/slides/python-net/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/aspose.slides/portionformat/symbol_font/) | Returns or sets the symbolic font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Read/write [`IFontData`](/slides/python-net/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/aspose.slides/portionformat/escapement/) | Returns or sets the superscript or subscript text.<br/>            Value from -100% (subscript) to 100% (superscript).<br/>            **float.NaN**  means value is undefined and should be inherited from the Master.<br/>            Read/write **float**. |
| [`kerning_minimal_size`](/slides/python-net/aspose.slides/portionformat/kerning_minimal_size/) | Returns or sets the minimal font size, for which kerning should be switched on.<br/>            **float.NaN**  means value is undefined and should be inherited from the Master.<br/>            Read/write **float**. |
| [`language_id`](/slides/python-net/aspose.slides/portionformat/language_id/) | Returns or sets the Id of a proofing language. Used for checking spelling and grammar.<br/>            Read/write **string**. |
| [`alternative_language_id`](/slides/python-net/aspose.slides/portionformat/alternative_language_id/) | Returns or sets the Id of an alternative language.<br/>            Read/write **string**. |
| [`spacing`](/slides/python-net/aspose.slides/portionformat/spacing/) | Returns or sets the intercharacter spacing increment.<br/>            **float.NaN**  means value is undefined and should be inherited from the Master.<br/>            Read/write **float**. |
| [`bookmark_id`](/slides/python-net/aspose.slides/portionformat/bookmark_id/) | Returns or sets bookmark identifier.<br/>            Read/write **string**. |
| [`smart_tag_clean`](/slides/python-net/aspose.slides/portionformat/smart_tag_clean/) | Determines whether the smart tag should be cleaned. No inheritance applied.<br/>            Read/write **bool**. |
| [`hyperlink_click`](/slides/python-net/aspose.slides/portionformat/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Read/write [`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/aspose.slides/portionformat/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Read/write [`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/aspose.slides/portionformat/hyperlink_manager/) | Hyperlinks manager.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/aspose.slides/ihyperlinkmanager). |
| [`slide`](/slides/python-net/aspose.slides/portionformat/slide/) |  |
| [`presentation`](/slides/python-net/aspose.slides/portionformat/presentation/) |  |
| [`as_i_base_portion_format`](/slides/python-net/aspose.slides/portionformat/as_i_base_portion_format/) |  |
| [`as_i_hyperlink_container`](/slides/python-net/aspose.slides/portionformat/as_i_hyperlink_container/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`get_effective`](/slides/python-net/aspose.slides/portionformat/get_effective/#) | Gets effective portion formatting data with the inheritance applied. |


### Remarks

This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that
            no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".


In order to get the effective formatting parameter values including inherited you need to use [`PortionFormat.get_effective`](/slides/python-net/aspose.slides/portionformat/get_effective) method 
            which returns a [`IPortionFormatEffectiveData`](/slides/python-net/aspose.slides/iportionformateffectivedata) instance.

### See Also
* class [`BasePortionFormat`](/slides/python-net/aspose.slides/baseportionformat)
* class [`IPortionFormatEffectiveData`](/slides/python-net/aspose.slides/iportionformateffectivedata)
* class [`PortionFormat`](/slides/python-net/aspose.slides/portionformat)
* class [`PVIObject`](/slides/python-net/aspose.slides/pviobject)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
