---
title: IPortionFormat class
second_title: Aspose.Slides Python के लिए .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides/iportionformat/
---
## IPortionFormat क्लास

यह क्लास टेक्स्ट भाग फ़ॉर्मेटिंग गुणों को शामिल करती है। [`IPortionFormatEffectiveData`](/slides/python-net/hi/aspose.slides/iportionformateffectivedata) के विपरीत, इस क्लास की सभी गुण लिखने योग्य हैं।

IPortionFormat प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`bookmark_id`](/slides/python-net/hi/aspose.slides/iportionformat/bookmark_id/) | बुकमार्क पहचानकर्ता को प्राप्त करता है या सेट करता है।<br/>            पढ़ें/लिखें **str**. |
| [`smart_tag_clean`](/slides/python-net/hi/aspose.slides/iportionformat/smart_tag_clean/) | निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं हुई।<br/>            पढ़ें/लिखें **bool**. |
| [`line_format`](/slides/python-net/hi/aspose.slides/iportionformat/line_format/) |  |
| [`fill_format`](/slides/python-net/hi/aspose.slides/iportionformat/fill_format/) |  |
| [`effect_format`](/slides/python-net/hi/aspose.slides/iportionformat/effect_format/) |  |
| [`highlight_color`](/slides/python-net/hi/aspose.slides/iportionformat/highlight_color/) |  |
| [`underline_line_format`](/slides/python-net/hi/aspose.slides/iportionformat/underline_line_format/) |  |
| [`underline_fill_format`](/slides/python-net/hi/aspose.slides/iportionformat/underline_fill_format/) |  |
| [`font_bold`](/slides/python-net/hi/aspose.slides/iportionformat/font_bold/) |  |
| [`font_italic`](/slides/python-net/hi/aspose.slides/iportionformat/font_italic/) |  |
| [`kumimoji`](/slides/python-net/hi/aspose.slides/iportionformat/kumimoji/) |  |
| [`normalise_height`](/slides/python-net/hi/aspose.slides/iportionformat/normalise_height/) |  |
| [`proof_disabled`](/slides/python-net/hi/aspose.slides/iportionformat/proof_disabled/) |  |
| [`font_underline`](/slides/python-net/hi/aspose.slides/iportionformat/font_underline/) |  |
| [`text_cap_type`](/slides/python-net/hi/aspose.slides/iportionformat/text_cap_type/) |  |
| [`strikethrough_type`](/slides/python-net/hi/aspose.slides/iportionformat/strikethrough_type/) |  |
| [`is_hard_underline_line`](/slides/python-net/hi/aspose.slides/iportionformat/is_hard_underline_line/) |  |
| [`is_hard_underline_fill`](/slides/python-net/hi/aspose.slides/iportionformat/is_hard_underline_fill/) |  |
| [`font_height`](/slides/python-net/hi/aspose.slides/iportionformat/font_height/) |  |
| [`latin_font`](/slides/python-net/hi/aspose.slides/iportionformat/latin_font/) |  |
| [`east_asian_font`](/slides/python-net/hi/aspose.slides/iportionformat/east_asian_font/) |  |
| [`complex_script_font`](/slides/python-net/hi/aspose.slides/iportionformat/complex_script_font/) |  |
| [`symbol_font`](/slides/python-net/hi/aspose.slides/iportionformat/symbol_font/) |  |
| [`escapement`](/slides/python-net/hi/aspose.slides/iportionformat/escapement/) |  |
| [`kerning_minimal_size`](/slides/python-net/hi/aspose.slides/iportionformat/kerning_minimal_size/) |  |
| [`language_id`](/slides/python-net/hi/aspose.slides/iportionformat/language_id/) |  |
| [`alternative_language_id`](/slides/python-net/hi/aspose.slides/iportionformat/alternative_language_id/) |  |
| [`spacing`](/slides/python-net/hi/aspose.slides/iportionformat/spacing/) |  |
| [`spell_check`](/slides/python-net/hi/aspose.slides/iportionformat/spell_check/) |  |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides/iportionformat/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides/iportionformat/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides/iportionformat/hyperlink_manager/) |  |

## विधियां

| विधि | विवरण |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/hi/aspose.slides/iportionformat/get_effective/#) | विरासत लागू होने पर प्रभावी भाग फ़ॉर्मेटिंग डेटा प्राप्त करता है। |

### टिप्पणी

यह क्लास विशेष भाग के लिए परिभाषित टेक्स्ट भाग फ़ॉर्मेटिंग गुणों को लौटाने और संशोधित करने के लिए उपयोग की जाती है। इसका अर्थ है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको "undefined" अर्थ वाले मान प्राप्त होंगे।

विरासत सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [`IPortionFormat.get_effective`](/slides/python-net/hi/aspose.slides/iportionformat/get_effective) विधि का उपयोग करना होगा जो एक [`IPortionFormatEffectiveData`](/slides/python-net/hi/aspose.slides/iportionformateffectivedata) इंस्टेंस लौटाता है।

### संबंधित देखें
* क्लास [`IPortionFormatEffectiveData`](/slides/python-net/hi/aspose.slides/iportionformateffectivedata)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)