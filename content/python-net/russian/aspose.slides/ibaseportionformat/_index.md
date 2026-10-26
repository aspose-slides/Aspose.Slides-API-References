---
title: IBasePortionFormat class
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat класс

Этот класс содержит свойства форматирования части текста. В отличие от [`IPortionFormatEffectiveData`](/slides/python-net/ru/aspose.slides/iportionformateffectivedata), все свойства этого класса доступны для записи.

Тип IBasePortionFormat раскрывает следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`line_format`](/slides/python-net/ru/aspose.slides/ibaseportionformat/line_format/) | Returns the LineFormat properties for text outlining. No inheritance applied.<br/>            Только для чтения [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides/ibaseportionformat/fill_format/) | Returns the text FillFormat properties. No inheritance applied.<br/>            Только для чтения [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides/ibaseportionformat/effect_format/) | Returns the text EffectFormat properties. No inheritance applied.<br/>            Только для чтения [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/ru/aspose.slides/ibaseportionformat/highlight_color/) | Returns the color used to highlight a text. No inheritance applied.<br/>            Только для чтения [`IColorFormat`](/slides/python-net/ru/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/ru/aspose.slides/ibaseportionformat/underline_line_format/) | Returns the LineFormat properties used to outline underline line. No inheritance applied.<br/>            Только для чтения [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/ru/aspose.slides/ibaseportionformat/underline_fill_format/) | Returns the underline line FillFormat properties. No inheritance applied.<br/>            Только для чтения [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/ru/aspose.slides/ibaseportionformat/font_bold/) | Determines whether the font is bold. No inheritance applied.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/ru/aspose.slides/ibaseportionformat/font_italic/) | Determines whether the font is itallic. No inheritance applied.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/ru/aspose.slides/ibaseportionformat/kumimoji/) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/ru/aspose.slides/ibaseportionformat/normalise_height/) | Determines whether the height of a text should be normalized. No inheritance applied.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/ru/aspose.slides/ibaseportionformat/proof_disabled/) | Determines whether the text shouldn't be proofed. No inheritance applied.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/ru/aspose.slides/ibaseportionformat/font_underline/) | Returns or sets the text underline type. No inheritance applied.<br/>            Чтение/запись [`TextUnderlineType`](/slides/python-net/ru/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/ru/aspose.slides/ibaseportionformat/text_cap_type/) | Returns or sets the type of text capitalization. No inheritance applied.<br/>            Чтение/запись [`TextCapType`](/slides/python-net/ru/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/ru/aspose.slides/ibaseportionformat/strikethrough_type/) | Returns or sets the strikethrough type of a text. No inheritance applied.<br/>            Чтение/запись [`TextStrikethroughType`](/slides/python-net/ru/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/ru/aspose.slides/ibaseportionformat/is_hard_underline_line/) | Determines whether the underline style has own LineFormat properties or inherits it<br/>            from the LineFormat properties of the text.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/ru/aspose.slides/ibaseportionformat/is_hard_underline_fill/) | Determines whether the underline style has own FillFormat properties or inherits it<br/>            from the FillFormat properties of the text.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/ru/aspose.slides/ibaseportionformat/font_height/) | Returns or sets the font height of a portion.<br/>            **float.NaN**  means height is undefined and should be inherited from the Master.<br/>            Чтение/запись **float**. |
| [`latin_font`](/slides/python-net/ru/aspose.slides/ibaseportionformat/latin_font/) | Returns or sets the Latin font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Чтение/запись [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/ru/aspose.slides/ibaseportionformat/east_asian_font/) | Returns or sets the East Asian font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Чтение/запись [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/ru/aspose.slides/ibaseportionformat/complex_script_font/) | Returns or sets the complex script font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Чтение/запись [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/ru/aspose.slides/ibaseportionformat/symbol_font/) | Returns or sets the symbolic font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            Чтение/запись [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/ru/aspose.slides/ibaseportionformat/escapement/) | Returns or sets the superscript or subscript text.<br/>            Value from -100% (subscript) to 100% (superscript).<br/>            **float.NaN**  means value is undefined and should be inherited from the Master.<br/>            Чтение/запись **float**. |
| [`kerning_minimal_size`](/slides/python-net/ru/aspose.slides/ibaseportionformat/kerning_minimal_size/) | Returns or sets the minimal font size, for which kerning should be switched on.<br/>            **float.NaN**  means value is undefined and should be inherited from the Master.<br/>            Чтение/запись **float**. |
| [`language_id`](/slides/python-net/ru/aspose.slides/ibaseportionformat/language_id/) | Returns or sets the Id of a proofing language. Used for checking spelling and grammar.<br/>            Чтение/запись **str**. |
| [`alternative_language_id`](/slides/python-net/ru/aspose.slides/ibaseportionformat/alternative_language_id/) | Returns or sets the Id of an alternative language.<br/>            Чтение/запись **str**. |
| [`spacing`](/slides/python-net/ru/aspose.slides/ibaseportionformat/spacing/) | Returns or sets the intercharacter spacing increment.<br/>            **float.NaN**  means value is undefined and should be inherited from the Master.<br/>            Чтение/запись **float**. |
| [`spell_check`](/slides/python-net/ru/aspose.slides/ibaseportionformat/spell_check/) | Gets or sets a value indicating whether spell checking is enabled for the text portion.<br/>            When this property is set to false, spelling checks for text elements are suppressed.<br/>            When set to true, spell checking is allowed.<br/>            Default value is `false`. |

### Примечания

Этот класс используется для получения и изменения свойств форматирования текстовой части, определенных для конкретной части. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие «undefined».

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, необходимо использовать метод [`IPortionFormat.get_effective`](/slides/python-net/ru/aspose.slides/iportionformat/get_effective), который возвращает экземпляр [`IPortionFormatEffectiveData`](/slides/python-net/ru/aspose.slides/iportionformateffectivedata).

### Смотрите также
* класс [`IPortionFormatEffectiveData`](/slides/python-net/ru/aspose.slides/iportionformateffectivedata)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)