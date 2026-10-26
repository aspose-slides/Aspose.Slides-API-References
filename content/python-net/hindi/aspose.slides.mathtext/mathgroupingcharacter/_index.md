---
title: MathGroupingCharacter class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter क्लास

एक अभिव्यक्ति के ऊपर या नीचे समूह चिह्न निर्दिष्ट करता है, आमतौर पर तत्वों के बीच संबंध को उजागर करने के लिए

**विरासत:**[`MathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)

MathGroupingCharacter प्रकार निम्न सदस्य उजागर करता है:

## निर्माणकर्ता

| कन्स्ट्रक्टर | विवरण |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | MathGroupingCharacter क्लास का एक नया उदाहरण प्रारंभ करता है <br/>            डिफ़ॉल्ट समूह चिह्न U+23DF (निचला कर्ली ब्रैकेट) के साथ |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | MathGroupingCharacter क्लास का एक नया उदाहरण प्रारंभ करता है। |

## प्रॉपर्टी

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`base`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/base/) | बेस तर्क |
| [`character`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/character/) | समूह चिह्न<br/>            डिफ़ॉल्ट मान: U+23DF (निचला कर्ली ब्रैकेट) |
| [`position`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/position/) | समूह चिह्न की स्थिति।<br/>            डिफ़ॉल्ट: नीचे |
| [`vertical_justification`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | समूह चिह्न का लंबवत संरेखण।<br/>            बेसलाइन के सापेक्ष वस्तु के संरेखण को निर्दिष्ट करता है।<br/>            उदाहरण के लिए, जब समूह चिह्न वस्तु के ऊपर हो, <br/>            Top का VerticalJustification दर्शाता है कि वस्तु का शीर्ष बेसलाइन पर गिरता है;<br/>            जब VerticalJustification को Bottom पर सेट किया जाता है, वस्तु का नीचे बेसलाइन पर होता है<br/>            डिफ़ॉल्ट: Position=Top के लिए Bottom, और Position=Bottom के लिए Top |

## विधि

| विधि | विवरण |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | निर्दिष्ट प्रकार की एक भिन्न बनाता है इस अंशांक और निर्दिष्ट हर के साथ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | निर्दिष्ट प्रकार की एक भिन्न बनाता है इस अंशांक और निर्दिष्ट हर के साथ |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | गणितीय तत्व को कोष्ठकों में लपेटता है |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | गणितीय तत्व को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षरों में फ्रेमिंग के रूप में लपेटता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर लेता है |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर और अतिरिक्त तर्क के साथ लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर और अतिरिक्त तर्क के साथ लेता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | उपसूचक बनाता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | उपसूचक बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | अतिसूचक बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | अतिसूचक बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | दाईं ओर उपसूचक और अतिसूचक बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | दाईं ओर उपसूचक और अतिसूचक बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | बाईं ओर उपसूचक और अतिसूचक बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | बाईं ओर उपसूचक और अतिसूचक बनाता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल निर्धारित करता है। |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल निर्धारित करता है। |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | ऊपरी सीमा लेता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | ऊपरी सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | निचली सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | निचली सीमा लेता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | एक N-ary ऑपरेटर बनाता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | एक N-ary ऑपरेटर बनाता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | समाकल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | समाकल लेता है |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | सीमाओं के बिना समाकल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | समाकल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | समाकल लेता है |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/group/#) | इस तत्व को निचले कर्ली ब्रैकेट का उपयोग करके समूह में रखता है |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | इस तत्व को समूह चिह्न जैसे निचला कर्ली ब्रैकेट या अन्य का उपयोग करके समूह में रखता है |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | एक लंबवत सरणी में रखता है |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | एक एक्सेंट चिह्न सेट करता है (इस तत्व के शीर्ष पर एक अक्षर) |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | इस तत्व के शीर्ष पर एक बार सेट करता है |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | इस तत्व के नीचे एक बार सेट करता है |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है <br/>            जिसका उपयोग समीकरण के घटकों या अन्य गणितीय पाठ के उदाहरण को समूहित करने के लिए किया जाता है।<br/>            एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) संरेखण बिंदु के साथ या बिना एक ऑपरेटर एम्यूलेटर के रूप में कार्य कर सकता है, <br/>            एक लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस तरह समूहित किया जा सकता है कि भीतर लाइन ब्रेक की अनुमति न हो। |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | बच्चों के तत्व प्राप्त करें |

### संबंधित देखें
* क्लास [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)
* क्लास [`MathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/mathgroupingcharacter)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)