---
title: MathArray class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/matharray/
---
## MathArray क्लास

किसी समीकरण या किसी भी गणितीय वस्तु की लंबवत सरणी को निर्दिष्ट करता है

**विरासत:**[`MathArray`](/slides/python-net/hi/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)

MathArray प्रकार निम्नलिखित सदस्य उजागर करता है:

## निर्माणकर्ता

| निर्माणकर्ता | विवरण |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/__init__/#imathelement) | Creates a mathematical array and places the specified element in it |
| [`__init__(self, elements)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## प्रॉपर्टी

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`arguments`](/slides/python-net/hi/aspose.slides.mathtext/matharray/arguments/) | सरणी के आइटमों का सेट |
| [`base_justification`](/slides/python-net/hi/aspose.slides.mathtext/matharray/base_justification/) | सरणी की समानता को आसपास के पाठ के सापेक्ष निर्दिष्ट करता है<br/>            सरणी के बाहर का पाठ सरणी वस्तु के निचले, शीर्ष या केंद्र के साथ संरेखित किया जा सकता है।<br/>            Default value: Center |
| [`maximum_distribution`](/slides/python-net/hi/aspose.slides.mathtext/matharray/maximum_distribution/) | अधिकतम वितरण<br/>            जब true हो, तो सरणी को सम्मिलित तत्व (पृष्ठ, कॉलम, सेल, आदि) की अधिकतम चौड़ाई तक फैलाया जाता है। |
| [`object_distribution`](/slides/python-net/hi/aspose.slides.mathtext/matharray/object_distribution/) | ऑब्जेक्ट वितरण<br/>            जब true हो, तो सरणी की सामग्री को सरणी वस्तु की अधिकतम चौड़ाई तक फैलाया जाता है। |
| [`row_spacing_rule`](/slides/python-net/hi/aspose.slides.mathtext/matharray/row_spacing_rule/) | सरणी तत्वों के बीच ऊर्ध्वाधर अंतराल का प्रकार<br/>            Default: SingleLineGap |
| [`row_spacing`](/slides/python-net/hi/aspose.slides.mathtext/matharray/row_spacing/) | सरणी की पंक्तियों के बीच अंतराल<br/>            यह केवल तब उपयोग किया जाता है जब RowSpacingRule को 3 Exactly पर सेट किया गया हो, इस स्थिति में माप इकाई पॉइंट्स होती है <br/>            या Multiple पर, इस स्थिति में माप इकाई आधी पंक्तियाँ होती है।<br/>            Default: 0 |

## मेथड

| मेथड | विवरण |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/join/#imathelement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/join/#str) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/divide/#imathelement) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/divide/#str) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | निर्दिष्ट प्रकार का एक भिन्न इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | निर्दिष्ट प्रकार का एक भिन्न इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/enclose/#) | गणितीय तत्व को कोष्ठकों में घेरता है |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/enclose/#char-char) | गणितीय तत्व को निर्दिष्ट वर्णों, जैसे कोष्ठक या अन्य वर्णों, में फ्रेमिंग के रूप में घेरता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/function/#imathelement) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके किसी तर्क का फ़ंक्शन लेता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/function/#str) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके किसी तर्क का फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर लेता है |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क के साथ लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क के साथ लेता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | सबस्क्रिप्ट बनाता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/set_subscript/#str) | सबस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | सुपरसक्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/set_superscript/#str) | सुपरसक्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | दाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | दाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | बाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | बाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/radical/#imathelement) | निर्दिष्ट तर्क से दिए गए घातांक की गणितीय मूल को निर्दिष्ट करता है। |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/radical/#str) | निर्दिष्ट तर्क से दिए गए घातांक की गणितीय मूल को निर्दिष्ट करता है। |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | ऊपर की सीमा लेता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/set_upper_limit/#str) | ऊपर की सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | नीचे की सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/set_lower_limit/#str) | नीचे की सीमा लेता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | एक N-ary ऑपरेटर बनाता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | एक N-ary ऑपरेटर बनाता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | समाकलन लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | समाकलन लेता है |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | सीमाओं के बिना समाकलन लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | समाकलन लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | समाकलन लेता है |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/group/#) | नीचे की कर्ली ब्रैकेट का उपयोग करके इस तत्व को समूह में रखता है |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | नीचे की कर्ली ब्रैकेट या अन्य समूहित वर्ण का उपयोग करके इस तत्व को समूह में रखता है |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/to_border_box/#) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/to_math_array/#) | एक लंबवत सरणी में रखता है |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/accent/#char) | एक एक्सेंट चिन्ह सेट करता है (इस तत्व के ऊपर एक वर्ण) |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/overbar/#) | इस तत्व के ऊपर एक बार सेट करता है |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/underbar/#) | इस तत्व के नीचे एक बार सेट करता है |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/to_box/#) | इस तत्व को गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है, जो समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए उपयोग किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) संरेखण बिंदु के साथ या बिना ऑपरेटर एम्यूलेटर के रूप में कार्य कर सकता है, लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या ऐसा समूहित किया जा सकता है कि उसके भीतर लाइन ब्रेक की अनुमति न हो। |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/matharray/get_children/#) | संतान तत्व प्राप्त करें |

### संबंधित
* क्लास [`MathArray`](/slides/python-net/hi/aspose.slides.mathtext/matharray)
* क्लास [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)