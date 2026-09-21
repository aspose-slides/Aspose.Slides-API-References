---
title: IMathDelimiter class
second_title: Aspose.Slides for Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/imathdelimiter/
---
## IMathDelimiter वर्ग

Specifies the delimiter object, consisting of opening and closing characters (such as parentheses, 
            braces, brackets, and vertical bars), and one or more mathematical elements inside, separated by a specified character.
            Examples: (𝑥2); [𝑥2|𝑦2]

The IMathDelimiter type exposes the following members:

## गुण

| गुण | विवरण |
| :- | :- |
| [`arguments`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/arguments/) | एक या अधिक गणितीय तत्व जो डिलिमिटर अक्षरों से अलग किए गए हैं |
| [`beginning_character`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/beginning_character/) | Delimiter Beginning Character निर्दिष्ट करता है प्रारंभ, या खुलने वाला, डिलिमिटर अक्षर। <br/>            गणितीय डिलिमिटर वे बाउंडिंग अक्षर हैं जैसे कोष्ठक, ब्रेस, और ब्रैकेट।<br/>            डिफ़ॉल्ट मान: '(' |
| [`separator_character`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/separator_character/) | Delimiter Separator Character उस अक्षर को निर्दिष्ट करता है जो डिलिमिटर ऑब्जेक्ट में तर्कों को अलग करता है। <br/>            डिफ़ॉल्ट: '\|'. |
| [`ending_character`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/ending_character/) | Delimiter Ending Character निर्दिष्ट करता है अंत, या बंद, डिलिमिटर अक्षर। <br/>            गणितीय डिलिमिटर वे बाउंडिंग अक्षर हैं जैसे कोष्ठक, ब्रेस, और ब्रैकेट।<br/>            डिफ़ॉल्ट: ')' |
| [`grow_to_match_operand_height`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/grow_to_match_operand_height/) | BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि को निर्दिष्ट करता है<br/>            जब true हो, तो डिलिमिटर अपने ऑपरेन्ड की ऊँचाई से मेल खाने के लिए लंबवत बढ़ते हैं।<br/>            डिफ़ॉल्ट मान true है |
| [`delimiter_shape`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/delimiter_shape/) | डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। <br/>            जब MathDelimiterShape.Centered है, तो डिलिमिटर गणितीय पाठ के गणितीय अक्ष के चारों ओर केंद्रित होते हैं <br/>            और उनकी सामग्री की पूरी ऊँचाई में फिट हो सकते हैं।<br/>            जब MathDelimiterShape.Match है, तो उनकी ऊँचाई और आकार को उनकी सामग्री के साथ बिल्कुल मेल खाने के लिए बदल दिया जाता है। |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`delimit(self, separator_character)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/delimit/#char) | निर्दिष्ट डिलिमिटर अक्षर का उपयोग करके तर्कों को सीमित करता है |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter/to_box/#) |  |

### देखें
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)