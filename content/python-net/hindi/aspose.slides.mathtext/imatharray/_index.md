---
title: IMathArray class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/imatharray/
---
## IMathArray क्लास

ऐरे के समीकरणों या किसी भी गणितीय वस्तु का एक लंबवत समूह निर्दिष्ट करता है

The IMathArray type exposes the following members:

## गुण

| संपत्ति | विवरण |
| :- | :- |
| [`arguments`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/arguments/) | ऐरे के आइटमों का सेट |
| [`base_justification`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/base_justification/) | ऐरे की आसपास के टेक्स्ट के सापेक्ष संरेखण निर्दिष्ट करता है<br/>            ऐरे के बाहर का टेक्स्ट ऐरे ऑब्जेक्ट के नीचे, ऊपर, या केन्द्र के साथ संरेखित किया जा सकता है।<br/>            डिफ़ॉल्ट मान: केन्द्र |
| [`maximum_distribution`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/maximum_distribution/) | अधिकतम वितरण<br/>            जब सत्य हो, तो ऐरे को-containing तत्व (पृष्ठ, कॉलम, सेल, आदि) की अधिकतम चौड़ाई तक फैलाया जाता है। |
| [`object_distribution`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/object_distribution/) | ऑब्जेक्ट वितरण<br/>            जब सत्य हो, तो ऐरे की सामग्री को ऐरे ऑब्जेक्ट की अधिकतम चौड़ाई तक फैलाया जाता है। |
| [`row_spacing_rule`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/row_spacing_rule/) | ऐरे तत्वों के बीच ऊर्ध्वाधर स्पेसिंग का प्रकार |
| [`row_spacing`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/row_spacing/) | ऐरे की पंक्तियों के बीच दूरी<br/>            यह केवल तभी उपयोग किया जाता है जब RowSpacingRule को 3 Exactly पर सेट किया गया हो, जिसमें माप की इकाई पॉइंट्स होती है <br/>            या Multiple में, जिसमें माप की इकाई आधी पंक्तियाँ होती है।<br/>            डिफ़ॉल्ट: 0 |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/imatharray/to_box/#) |  |

### देखें भी
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)