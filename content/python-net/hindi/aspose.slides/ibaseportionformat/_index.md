---
title: IBasePortionFormat class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat क्लास

यह क्लास टेक्स्ट पोर्शन फ़ॉर्मेटिंग प्रॉपर्टीज़ को सम्मिलित करती है। [`IPortionFormatEffectiveData`](/slides/python-net/hi/aspose.slides/iportionformateffectivedata) के विपरीत, इस क्लास की सभी प्रॉपर्टीज़ लिखने योग्य हैं।

IBasePortionFormat टाइप निम्नलिखित सदस्यों को उजागर करता है:

## Properties

| Property | Description |
| :- | :- |
| [`line_format`](/slides/python-net/hi/aspose.slides/ibaseportionformat/line_format/) | Returns the LineFormat properties for text outlining. No inheritance applied.<br/>            केवल पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/hi/aspose.slides/ibaseportionformat/fill_format/) | Returns the text FillFormat properties. No inheritance applied.<br/>            केवल पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/hi/aspose.slides/ibaseportionformat/effect_format/) | Returns the text EffectFormat properties. No inheritance applied.<br/>            केवल पढ़ने योग्य [`IEffectFormat`](/slides/python-net/hi/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/hi/aspose.slides/ibaseportionformat/highlight_color/) | Returns the color used to highlight a text. No inheritance applied.<br/>            केवल पढ़ने योग्य [`IColorFormat`](/slides/python-net/hi/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/hi/aspose.slides/ibaseportionformat/underline_line_format/) | Returns the LineFormat properties used to outline underline line. No inheritance applied.<br/>            केवल पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/hi/aspose.slides/ibaseportionformat/underline_fill_format/) | Returns the underline line FillFormat properties. No inheritance applied.<br/>            केवल पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/hi/aspose.slides/ibaseportionformat/font_bold/) | Determines whether the font is bold. No inheritance applied.<br/>            पढ़ने/लिखने योग्य [`NullableBool`](/slides/python-net/hi/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/hi/aspose.slides/ibaseportionformat/font_italic/) | Determines whether the font is itallic. No inheritance applied.<br/>            पढ़ने/लिखने योग्य [`NullableBool`](/slides/python-net/hi/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/hi/aspose.slides/ibaseportionformat/kumimoji/) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied.<br/>            पढ़ने/लिखने योग्य [`NullableBool`](/slides/python-net/hi/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/hi/aspose.slides/ibaseportionformat/normalise_height/) | Determines whether the height of a text should be normalized. No inheritance applied.<br/>            पढ़ने/लिखने योग्य [`NullableBool`](/slides/python-net/hi/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/hi/aspose.slides/ibaseportionformat/proof_disabled/) | Determines whether the text shouldn't be proofed. No inheritance applied.<br/>            पढ़ने/लिखने योग्य [`NullableBool`](/slides/python-net/hi/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/hi/aspose.slides/ibaseportionformat/font_underline/) | Returns or sets the text underline type. No inheritance applied.<br/>            पढ़ने/लिखने योग्य [`TextUnderlineType`](/slides/python-net/hi/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/hi/aspose.slides/ibaseportionformat/text_cap_type/) | Returns or sets the type of text capitalization. No inheritance applied.<br/>            पढ़ने/लिखने योग्य [`TextCapType`](/slides/python-net/hi/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/hi/aspose.slides/ibaseportionformat/strikethrough_type/) | Returns or sets the strikethrough type of a text. No inheritance applied.<br/>            पढ़ने/लिखने योग्य [`TextStrikethroughType`](/slides/python-net/hi/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/hi/aspose.slides/ibaseportionformat/is_hard_underline_line/) | Determines whether the underline style has own LineFormat properties or inherits it<br/>            from the LineFormat properties of the text.<br/>            पढ़ने/लिखने योग्य [`NullableBool`](/slides/python-net/hi/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/hi/aspose.slides/ibaseportionformat/is_hard_underline_fill/) | Determines whether the underline style has own FillFormat properties or inherits it<br/>            from the FillFormat properties of the text.<br/>            पढ़ने/लिखने योग्य [`NullableBool`](/slides/python-net/hi/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/hi/aspose.slides/ibaseportionformat/font_height/) | Returns or sets the font height of a portion.<br/>            **float.NaN**  means height is undefined and should be inherited from the Master.<br/>            पढ़ने/लिखने योग्य **float**. |
| [`latin_font`](/slides/python-net/hi/aspose.slides/ibaseportionformat/latin_font/) | Returns or sets the Latin font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            पढ़ने/लिखने योग्य [`IFontData`](/slides/python-net/hi/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/hi/aspose.slides/ibaseportionformat/east_asian_font/) | Returns or sets the East Asian font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            पढ़ने/लिखने योग्य [`IFontData`](/slides/python-net/hi/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/hi/aspose.slides/ibaseportionformat/complex_script_font/) | Returns or sets the complex script font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            पढ़ने/लिखने योग्य [`IFontData`](/slides/python-net/hi/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/hi/aspose.slides/ibaseportionformat/symbol_font/) | Returns or sets the symbolic font info.<br/>            Null means font is undefined and should be inherited from the Master.<br/>            पढ़ने/लिखने योग्य [`IFontData`](/slides/python-net/hi/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/hi/aspose.slides/ibaseportionformat/escapement/) | Returns or sets the superscript or subscript text.<br/>            Value from -100% (subscript) to 100% (superscript).<br/>            **float.NaN**  means value is undefined and should be inherited from the Master.<br/>            पढ़ने/लिखने योग्य **float**. |
| [`kerning_minimal_size`](/slides/python-net/hi/aspose.slides/ibaseportionformat/kerning_minimal_size/) | Returns or sets the minimal font size, for which kerning should be switched on.<br/>            **float.NaN**  means value is undefined and should be inherited from the Master.<br/>            पढ़ने/लिखने योग्य **float**. |
| [`language_id`](/slides/python-net/hi/aspose.slides/ibaseportionformat/language_id/) | Returns or sets the Id of a proofing language. Used for checking spelling and grammar.<br/>            पढ़ने/लिखने योग्य **str**. |
| [`alternative_language_id`](/slides/python-net/hi/aspose.slides/ibaseportionformat/alternative_language_id/) | Returns or sets the Id of an alternative language.<br/>            पढ़ने/लिखने योग्य **str**. |
| [`spacing`](/slides/python-net/hi/aspose.slides/ibaseportionformat/spacing/) | Returns or sets the intercharacter spacing increment.<br/>            **float.NaN**  means value is undefined and should be inherited from the Master.<br/>            पढ़ने/लिखने योग्य **float**. |
| [`spell_check`](/slides/python-net/hi/aspose.slides/ibaseportionformat/spell_check/) | Gets or sets a value indicating whether spell checking is enabled for the text portion.<br/>            When this property is set to false, spelling checks for text elements are suppressed.<br/>            When set to true, spell checking is allowed.<br/>            डिफ़ॉल्ट मान `false`. |


### टिप्पणी

यह क्लास विशेष भाग के लिए परिभाषित टेक्स्ट पोर्शन फ़ॉर्मेटिंग प्रॉपर्टीज़ को लौटाने और बदलने के लिए उपयोग की जाती है। इसका अर्थ है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको मिलते मान "अपरिभाषित" के अर्थ में होंगे।

विरासत सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [`IPortionFormat.get_effective`](/slides/python-net/hi/aspose.slides/iportionformat/get_effective) मेथड का उपयोग करना होगा जो एक [`IPortionFormatEffectiveData`](/slides/python-net/hi/aspose.slides/iportionformateffectivedata) इंस्टेंस लौटाता है।

### देखें
* क्लास [`IPortionFormatEffectiveData`](/slides/python-net/hi/aspose.slides/iportionformateffectivedata)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)