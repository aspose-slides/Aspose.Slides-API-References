---
title: MathDelimiter class
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter क्लास

विलग करने वाले ऑब्जेक्ट को निर्दिष्ट करता है, जिसमें खुलने और बंद होने वाले प्रतीक (जैसे कोष्ठक, कर्ली ब्रेसेस, वर्ग कोष्ठक और वर्टिकल बार) शामिल होते हैं, तथा उसके भीतर एक या अधिक गणितीय तत्व होते हैं, जो एक निर्दिष्ट वर्ण द्वारा अलग किए जाते हैं। उदाहरण: (𝑥2); [𝑥2|𝑦2]

**विरासत:**[`MathDelimiter`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)

MathDelimiter प्रकार निम्न सदस्य उजागर करता है:

## कंस्ट्रक्टर्स

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | निर्दिष्ट तत्व के साथ MathDelimiter को एकल बेस तर्क के रूप में प्रारंभ करता है |

## प्रॉपर्टी

| Property | Description |
| :- | :- |
| [`arguments`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/arguments/) | डिलिमिटर वर्णों द्वारा अलग किए गए एक या अधिक गणितीय तत्व |
| [`beginning_character`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character प्रारंभ या खोलने वाले डिलिमिटर वर्ण को निर्दिष्ट करता है। <br/> गणितीय डिलिमिटर वह समावेशी वर्ण होते हैं जैसे कोष्ठक, ब्रैकेट और ब्रेसेस।<br/> डिफॉल्ट: '('. |
| [`separator_character`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character डिलिमिटर ऑब्जेक्ट में तर्कों को अलग करने वाले वर्ण को निर्दिष्ट करता है। <br/> डिफॉल्ट: '\|'. |
| [`ending_character`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character समाप्ति या बंद करने वाले डिलिमिटर वर्ण को निर्दिष्ट करता है। <br/> गणितीय डिलिमिटर वह समावेशी वर्ण होते हैं जैसे कोष्ठक, ब्रैकेट और ब्रेसेस।<br/> डिफॉल्ट: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि को निर्दिष्ट करता है<br/> जब true हो, डिलिमिटर अपने ऑपरेण्ड की ऊँचाई से मेल करने के लिए लंबवत रूप से बढ़ते हैं।<br/> डिफॉल्ट मान true है |
| [`delimiter_shape`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। <br/> जब MathDelimiterShape.Centered है, तो डिलिमिटर गणितीय पाठ की गणितीय अक्ष के चारों ओर केंद्रित होते हैं और उनके सामग्री की पूरी ऊँचाई में फिट होने के लिए समायोजित होते हैं।<br/> जब MathDelimiterShape.Match है, तो उनकी ऊँचाई और आकार को बिल्कुल उनकी सामग्री के अनुरूप बदल दिया जाता है। |

## विधि

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/join/#str) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/divide/#str) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | निर्दिष्ट प्रकार का एक भिन्न इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | निर्दिष्ट प्रकार का एक भिन्न इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/enclose/#) | एक गणितीय तत्व को कोष्ठक में घेरता है |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | एक गणितीय तत्व को निर्दिष्ट वर्णों जैसे कोष्ठक या अन्य वर्णों में फ्रेमिंग के रूप में घेरता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके किसी तर्क का फ़ंक्शन लेता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/function/#str) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके किसी तर्क का फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | इस इंस्टेंस को तर्क के रूप में उपयोग करके और निर्दिष्ट अतिरिक्त तर्क के साथ निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | इस इंस्टेंस को तर्क के रूप में उपयोग करके और निर्दिष्ट अतिरिक्त तर्क के साथ निर्दिष्ट फ़ंक्शन लेता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | उपस्क्रिप्ट बनाता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | उपस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | सुपरस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | दाएँ ओर उपस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | दाएँ ओर उपस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | बाएँ ओर उपस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | बाएँ ओर उपस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | निर्दिष्ट तर्क से दिए गए क्रमांक की गणितीय मूल को निर्दिष्ट करता है। |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/radical/#str) | निर्दिष्ट तर्क से दिए गए क्रमांक की गणितीय मूल को निर्दिष्ट करता है। |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | ऊपरी सीमा लेता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | ऊपरी सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | निचली सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | निचली सीमा लेता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | एक N-ary ऑपरेटर बनाता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | एक N-ary ऑपरेटर बनाता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | समाकल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | समाकल लेता है |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | सीमाओं के बिना समाकल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | समाकल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | समाकल लेता है |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/group/#) | निचले कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | निचले कर्ली ब्रैकेट या अन्य समूह वर्ण का उपयोग करके इस तत्व को एक समूह में रखता है |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | एक लंबवत सरणी में रखता है |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/accent/#char) | एक उच्चारण चिह्न (इस तत्व के ऊपर का वर्ण) सेट करता है |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/overbar/#) | इस तत्व के शीर्ष पर एक बार सेट करता है |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/underbar/#) | इस तत्व के नीचे एक बार सेट करता है |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/to_box/#) | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है <br/> जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है।<br/> एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) संरेखण बिंदु के साथ या बिना ऑपरेटर इम्यूलेटर के रूप में कार्य कर सकता है, <br/> लाइन ब्रेक बिंदु के रूप में काम कर सकता है, या इस प्रकार समूहित किया जा सकता है कि भीतर लाइन ब्रेक की अनुमति न हो। |
| [`delimit(self, separator_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/delimit/#char) | निर्दिष्ट डिलिमिटर वर्ण का उपयोग करके तर्कों को सीमित करता है |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/get_children/#) | संतान तत्व प्राप्त करता है |

### देखें भी
* क्लास [`MathDelimiter`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter)
* क्लास [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)