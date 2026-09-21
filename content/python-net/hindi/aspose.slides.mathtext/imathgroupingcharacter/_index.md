---
title: IMathGroupingCharacter class
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/imathgroupingcharacter/
---
## IMathGroupingCharacter क्लास

एक अभिव्यक्ति के ऊपर या नीचे एक समूह चिन्ह निर्दिष्ट करता है, आमतौर पर तत्वों के बीच संबंध को उजागर करने के लिए

IMathGroupingCharacter प्रकार निम्नलिखित सदस्यों को प्रकट करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`base`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/base/) | आधार तर्क |
| [`character`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/character/) | समूह चिन्ह<br/>            डिफ़ॉल्ट मान: U+23DF (BOTTOM CURLY BRACKET) |
| [`position`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/position/) | समूह चिन्ह की स्थिति।<br/>            डिफ़ॉल्ट: Bottom |
| [`vertical_justification`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/vertical_justification/) | समूह चिन्ह का ऊर्ध्वाधर संरेखण।<br/>            ऑब्जेक्ट के बेसलाइन के संबंध में संरेखण को निर्दिष्ट करता है।<br/>            उदाहरण के लिए, जब समूह चिन्ह ऑब्जेक्ट के ऊपर होता है, <br/>            VerticalJustification of Top संकेत करता है कि ऑब्जेक्ट का शीर्ष बेसलाइन पर गिरता है;<br/>            जब VerticalJustification को Bottom पर सेट किया जाता है, तो ऑब्जेक्ट का नीचे बेसलाइन पर होता है<br/>            डिफ़ॉल्ट: Position=Top के लिए Bottom, और Position=Bottom के लिए Top |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter/to_box/#) |  |

### संबंधित देखें
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्ररी [`Aspose.Slides`](/slides/python-net)