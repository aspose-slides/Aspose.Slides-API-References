---
title: IBasePortionFormat class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat klass

Denna klass innehåller formateringsegenskaperna för textdelar. Till skillnad från [`IPortionFormatEffectiveData`](/slides/python-net/sv/aspose.slides/iportionformateffectivedata) är alla egenskaper i denna klass skrivbara.

IBasePortionFormat-typen exponerar följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`line_format`](/slides/python-net/sv/aspose.slides/ibaseportionformat/line_format/) | Returns the LineFormat properties for text outlining. No inheritance applied.<br/>            Endast läsning [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides/ibaseportionformat/fill_format/) | Returns the text FillFormat properties. No inheritance applied.<br/>            Endast läsning [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides/ibaseportionformat/effect_format/) | Returns the text EffectFormat properties. No inheritance applied.<br/>            Endast läsning [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/sv/aspose.slides/ibaseportionformat/highlight_color/) | Returns the color used to highlight a text. No inheritance applied.<br/>            Endast läsning [`IColorFormat`](/slides/python-net/sv/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/sv/aspose.slides/ibaseportionformat/underline_line_format/) | Returns the LineFormat properties used to outline underline line. No inheritance applied.<br/>            Endast läsning [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/sv/aspose.slides/ibaseportionformat/underline_fill_format/) | Returns the underline line FillFormat properties. No inheritance applied.<br/>            Endast läsning [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/sv/aspose.slides/ibaseportionformat/font_bold/) | Determines whether the font is bold. No inheritance applied.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/sv/aspose.slides/ibaseportionformat/font_italic/) | Determines whether the font is itallic. No inheritance applied.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/sv/aspose.slides/ibaseportionformat/kumimoji/) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/sv/aspose.slides/ibaseportionformat/normalise_height/) | Determines whether the height of a text should be normalized. No inheritance applied.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/sv/aspose.slides/ibaseportionformat/proof_disabled/) | Determines whether the text shouldn't be proofed. No inheritance applied.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/sv/aspose.slides/ibaseportionformat/font_underline/) | Returns or sets the text underline type. No inheritance applied.<br/>            Läs/skriv [`TextUnderlineType`](/slides/python-net/sv/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/sv/aspose.slides/ibaseportionformat/text_cap_type/) | Returns or sets the type of text capitalization. No inheritance applied.<br/>            Läs/skriv [`TextCapType`](/slides/python-net/sv/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/sv/aspose.slides/ibaseportionformat/strikethrough_type/) | Returns or sets the strikethrough type of a text. No inheritance applied.<br/>            Läs/skriv [`TextStrikethroughType`](/slides/python-net/sv/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/sv/aspose.slides/ibaseportionformat/is_hard_underline_line/) | Determines whether the underline style has own LineFormat properties or inherits it<br/>            from the LineFormat properties of the text.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/sv/aspose.slides/ibaseportionformat/is_hard_underline_fill/) | Determines whether the underline style has own FillFormat properties or inherits it<br/>            from the FillFormat properties of the text.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/sv/aspose.slides/ibaseportionformat/font_height/) | Returns or sets the font height of a portion.<br/>            **float.NaN**  means height is undefined and should be inherited from the Master.<br/>            Läs/skriv **float**. |
| [`latin_font`](/slides/python-net/sv/aspose.slides/ibaseportionformat/latin_font/) | Returns or sets the Latin font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Läs/skriv [`IFontData`](/slides/python-net/sv/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/sv/aspose.slides/ibaseportionformat/east_asian_font/) | Returns or sets the East Asian font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Läs/skriv [`IFontData`](/slides/python-net/sv/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/sv/aspose.slides/ibaseportionformat/complex_script_font/) | Returns or sets the complex script font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Läs/skriv [`IFontData`](/slides/python-net/sv/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/sv/aspose.slides/ibaseportionformat/symbol_font/) | Returns or sets the symbolic font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Läs/skriv [`IFontData`](/slides/python-net/sv/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/sv/aspose.slides/ibaseportionformat/escapement/) | Returns or sets the superscript or subscript text.<br/>            Value from -100% (subscript) to 100% (superscript).<br/>            **float.NaN**  means value is undefined and should be inherited from the Master.<br/>            Läs/skriv **float**. |
| [`kerning_minimal_size`](/slides/python-net/sv/aspose.slides/ibaseportionformat/kerning_minimal_size/) | Returns or sets the minimal font size, for which kerning should be switched on.<br/>            **float.NaN**  means value is undefined and should be inherited from the Master.<br/>            Läs/skriv **float**. |
| [`language_id`](/slides/python-net/sv/aspose.slides/ibaseportionformat/language_id/) | Returns or sets the Id of a proofing language. Used for checking spelling and grammar.<br/>            Läs/skriv **str**. |
| [`alternative_language_id`](/slides/python-net/sv/aspose.slides/ibaseportionformat/alternative_language_id/) | Returns or sets the Id of an alternative language.<br/>            Läs/skriv **str**. |
| [`spacing`](/slides/python-net/sv/aspose.slides/ibaseportionformat/spacing/) | Returns or sets the intercharacter spacing increment.<br/>            **float.NaN**  means value is undefined and should be inherited from the Master.<br/>            Läs/skriv **float**. |
| [`spell_check`](/slides/python-net/sv/aspose.slides/ibaseportionformat/spell_check/) | Gets or sets a value indicating whether spell checking is enabled for the text portion.<br/>            When this property is set to false, spelling checks for text elements are suppressed.<br/>            When set to true, spell checking is allowed.<br/>            Default value is `false`. |

### Anmärkningar

Denna klass används för att hämta och manipulera formateringsegenskaper för textdelar som definierats för den specifika delen. Detta innebär att
            ingen arv tillämpas vid hämtning av värden, så i de flesta fall får du värden som betyder "odefinierad".

För att få de effektiva formateringsparametervärdena inklusive ärvda måste du använda [`IPortionFormat.get_effective`](/slides/python-net/sv/aspose.slides/iportionformat/get_effective) metod 
            som returnerar en [`IPortionFormatEffectiveData`](/slides/python-net/sv/aspose.slides/iportionformateffectivedata) instans.

### Se även
* klass [`IPortionFormatEffectiveData`](/slides/python-net/sv/aspose.slides/iportionformateffectivedata)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)