---
title: MathNaryOperator class
second_title: Aspose.Slides Python के लिए .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator क्लास

एक N-ary गणितीय वस्तु को निर्दिष्ट करता है, जैसे Summation और Integral।  
यह एक ऑपरेटर, एक बेस (या ऑपरेण्ड), तथा वैकल्पिक ऊपरी और निचली सीमाओं से बना है।  
N-ary ऑपरेटरों के उदाहरण हैं: Summation, Union, Intersection, Integral  

**Inheritance:**[`MathNaryOperator`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)

The MathNaryOperator type exposes the following members:

## कन्स्ट्रक्टर्स

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | MathNaryOperator क्लास का नया उदाहरण प्रारम्भ करता है। |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | MathNaryOperator क्लास का नया उदाहरण प्रारम्भ करता है। |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | MathNaryOperator क्लास का नया उदाहरण प्रारम्भ करता है। |

## गुण

| गुण | विवरण |
| :- | :- |
| [`base`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/base/) | बेस तर्क |
| [`subscript`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/subscript/) | एक सबस्क्रिप्ट तर्क को निर्दिष्ट करता है जो, उदाहरण के लिए, इंटेग्रल के मामले में, निचली सीमा निर्धारित करता है |
| [`superscript`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/superscript/) | एक सुपरसस्क्रिप्ट तर्क को निर्दिष्ट करता है जो, उदाहरण के लिए, इंटेग्रल के मामले में, ऊपरी सीमा निर्धारित करता है |
| [`operator`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/operator/) | Nary ऑपरेटर अक्षर<br/>            उदाहरण: '∑', '∫' |
| [`limit_location`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/limit_location/) | सीमाओं (सबस्क्रिप्ट और सुपरसस्क्रिप्ट) का स्थान |
| [`grow_to_match_operand_height`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | ऑपरेटर अक्षर अपने ऑपरेण्ड की ऊँचाई के अनुरूप लंबवत रूप से बढ़ता है |
| [`hide_subscript`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | सबस्क्रिप्ट छुपाएँ |
| [`hide_superscript`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | सुपरसस्क्रिप्ट छुपाएँ |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/join/#str) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/divide/#str) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | निर्दिष्ट प्रकार की एक भिन्न बनाता है इस अंशांक और निर्दिष्ट हर के साथ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | निर्दिष्ट प्रकार की एक भिन्न बनाता है इस अंशांक और निर्दिष्ट हर के साथ |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/enclose/#) | एक गणितीय तत्व को कोष्ठक में रखता है |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | एक गणितीय तत्व को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षर फ्रेमिंग के रूप में रखता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/function/#str) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में उपयोग करते हुए लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में उपयोग करते हुए लेता है |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में उपयोग करते हुए लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में और अतिरिक्त निर्दिष्ट तर्क के साथ लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में और अतिरिक्त निर्दिष्ट तर्क के साथ लेता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | सबस्क्रिप्ट बनाता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | सबस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | सुपरसस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | सुपरसस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | दाएँ ओर सबस्क्रिप्ट और सुपरसस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | दाएँ ओर सबस्क्रिप्ट और सुपरसस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | बाएँ ओर सबस्क्रिप्ट और सुपरसस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | बाएँ ओर सबस्क्रिप्ट और सुपरसस्क्रिप्ट बनाता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | निर्दिष्ट तर्क से दिए गए घातांक की गणितीय मूल को निर्दिष्ट करता है। |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/radical/#str) | निर्दिष्ट तर्क से दिए गए घातांक की गणितीय मूल को निर्दिष्ट करता है। |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | ऊपरी सीमा लेता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | ऊपरी सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | निचली सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | निचली सीमा लेता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | एक N-ary ऑपरेटर बनाता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | एक N-ary ऑपरेटर बनाता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | इंटेग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | इंटेग्रल लेता है |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | सीमाओं के बिना इंटेग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | इंटेग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | इंटेग्रल लेता है |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/group/#) | निचले कर्ली ब्रेस का उपयोग करके इस तत्व को समूह में रखता है |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | कर्ली ब्रेस या अन्य ग्रुपिंग अक्षर का उपयोग करके इस तत्व को समूह में रखता है |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | इस तत्व को बॉर्डर-डिब्बे में रखता है |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | इस तत्व को बॉर्डर-डिब्बे में रखता है |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | एक लंबवत array में रखता है |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/accent/#char) | एक एक्सेंट चिह्न सेट करता है (इस तत्व के शीर्ष पर एक अक्षर) |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/overbar/#) | इस तत्व के शीर्ष पर एक बार सेट करता है |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/underbar/#) | इस तत्व के नीचे एक बार सेट करता है |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/to_box/#) | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है <br/>            जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है।<br/>            एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) संरेखण बिंदु के साथ या बिना एक ऑपरेटर अनुकरणकर्ता के रूप में कार्य कर सकता है, <br/>            लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस तरह समूहित किया जा सकता है कि भीतर लाइन ब्रेक न हो। |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator/get_children/#) | चाइल्ड तत्व प्राप्त करें |

### देखें
* क्लास [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)
* क्लास [`MathNaryOperator`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)