---
title: MathLimit class
second_title: Aspose.Slides पाइथन के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathlimit/
---
## MathLimit क्लास

बेसलाइन पर पाठ और उसके ठीक ऊपर या नीचे छोटे आकार के पाठ के साथ Limit ऑब्जेक्ट को निर्दिष्ट करता है।

**विरासत:**[`MathLimit`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit) → [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)

MathLimit प्रकार निम्नलिखित सदस्यों को प्रदर्शित करता है:

## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [`__init__(self, base_arg, limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement-bool) | MathLimit क्लास का नया उदाहरण आरंभ करता है। |
| [`__init__(self, base_arg, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement) | निचली सीमा के साथ MathLimit क्लास का नया उदाहरण आरंभ करता है। |

## गुण

| गुण | विवरण |
| :- | :- |
| [`base`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/base/) | आधार तर्क |
| [`limit`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/limit/) | सीमा तर्क |
| [`upper_limit`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/upper_limit/) | ऊपरी या निचली सीमा निर्दिष्ट करता है |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/join/#imathelement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/join/#str) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/divide/#imathelement) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/divide/#str) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/divide/#imathelement-mathfractiontypes) | निर्दिष्ट प्रकार का एक भिन्न इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/divide/#str-mathfractiontypes) | निर्दिष्ट प्रकार का एक भिन्न इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/enclose/#) | एक गणितीय तत्व को कोष्ठक में घेरता है |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/enclose/#char-char) | एक गणितीय तत्व को निर्दिष्ट अक्षरों में घेरता है, जैसे कोष्ठक या अन्य अक्षर फ्रेम के रूप में |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/function/#imathelement) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/function/#str) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/as_argument_of_function/#imathelement) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में उपयोग करके लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/as_argument_of_function/#str) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में उपयोग करके लेता है |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsofoneargument) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में उपयोग करके लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में और अतिरिक्त निर्दिष्ट तर्क के साथ लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-str) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में और अतिरिक्त निर्दिष्ट तर्क के साथ लेता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/set_subscript/#imathelement) | सबस्क्रिप्ट बनाता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/set_subscript/#str) | सबस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/set_superscript/#imathelement) | सुपरस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/set_superscript/#str) | सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#imathelement-imathelement) | दाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#str-str) | दाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#imathelement-imathelement) | बाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#str-str) | बाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/radical/#imathelement) | निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल को निर्दिष्ट करता है। |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/radical/#str) | निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल को निर्दिष्ट करता है। |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/set_upper_limit/#imathelement) | ऊपरी सीमा लेता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/set_upper_limit/#str) | ऊपरी सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/set_lower_limit/#imathelement) | निचली सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/set_lower_limit/#str) | निचली सीमा लेता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-imathelement-imathelement) | एक N-ary ऑपरेटर बनाता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-str-str) | एक N-ary ऑपरेटर बनाता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement) | इंटीग्रल लेता है |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes) | सीमाओं के बिना इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str-mathlimitlocations) | इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str) | इंटीग्रल लेता है |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/group/#) | निचले कर्ली ब्रैकेट का उपयोग करके इस तत्व को समूह में रखता है |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/group/#char-mathtopbotpositions-mathtopbotpositions) | निचले कर्ली ब्रैकेट या अन्य किसी समूह अक्षर का उपयोग करके इस तत्व को समूह में रखता है |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/to_border_box/#) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/to_math_array/#) | एक लंबवत सरणी में रखता है |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/accent/#char) | एक एक्सेंट चिह्न सेट करता है (इस तत्व के ऊपर एक अक्षर) |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/overbar/#) | इस तत्व के ऊपर एक बार सेट करता है |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/underbar/#) | इस तत्व के नीचे एक बार सेट करता है |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/to_box/#) | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है <br/>            जिससे समीकरण के घटकों या गणितीय पाठ के अन्य उदाहरणों को समूहित किया जाता है।<br/>            एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) संरेखण बिंदु के साथ या बिना ऑपरेटर इम्यूलेटर के रूप में सेवा दे सकता है, <br/>            लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस प्रकार समूहित किया जा सकता है कि भीतर लाइन ब्रेक की अनुमति न हो। |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit/get_children/#) | संतान तत्व प्राप्त करें |

### संबंधित देखें
* क्लास [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)
* क्लास [`MathLimit`](/slides/python-net/hi/aspose.slides.mathtext/mathlimit)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)