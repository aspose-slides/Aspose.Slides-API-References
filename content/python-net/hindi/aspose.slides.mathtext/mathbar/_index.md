---
title: MathBar class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathbar/
---
## MathBar क्लास

बार फ़ंक्शन को निर्दिष्ट करता है, जो एक बेस आर्ग्युमेंट और ऊपर की बार या नीचे की बार से बना होता है

**विरासत:**[`MathBar`](/slides/python-net/hi/aspose.slides.mathtext/mathbar) → [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)

MathBar प्रकार निम्न सदस्य प्रकट करता है:

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/__init__/#imathelement) | MathBar को ओवरबार (ऊपरी स्थिति) के साथ आरंभ करता है |
| [`__init__(self, element, position)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/__init__/#imathelement-mathtopbotpositions) | MathBar को निर्दिष्ट स्थिति के साथ आरंभ करता है |

## गुण

| गुण | विवरण |
| :- | :- |
| [`base`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/base/) | बेस आर्ग्युमेंट |
| [`position`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/position/) | बार रेखा की स्थिति। <br/>            डिफ़ॉल्ट: शीर्ष |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/join/#imathelement) | गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/join/#str) | गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/divide/#imathelement) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/divide/#str) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/divide/#imathelement-mathfractiontypes) | निर्दिष्ट प्रकार का भिन्न इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/divide/#str-mathfractiontypes) | निर्दिष्ट प्रकार का भिन्न इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/enclose/#) | गणितीय तत्व को कोष्ठक में घेरता है |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/enclose/#char-char) | गणितीय तत्व को निर्दिष्ट वर्णों, जैसे कोष्ठक या अन्य वर्ण, में फ्रेमिंग के रूप में घेरता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/function/#imathelement) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/function/#str) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/as_argument_of_function/#imathelement) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में उपयोग करके लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/as_argument_of_function/#str) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में उपयोग करके लेता है |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsofoneargument) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में उपयोग करके लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में उपयोग करके लेता है और निर्दिष्ट अतिरिक्त तर्क लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-str) | निर्धारित फ़ंक्शन को इस उदाहरण को तर्क के रूप में उपयोग करके लेता है और निर्दिष्ट अतिरिक्त तर्क लेता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/set_subscript/#imathelement) | सबस्क्रिप्ट बनाता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/set_subscript/#str) | सबस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/set_superscript/#imathelement) | सुपरस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/set_superscript/#str) | सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#imathelement-imathelement) | दाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#str-str) | दाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#imathelement-imathelement) | बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#str-str) | बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/radical/#imathelement) | निर्दिष्ट तर्क से दिए गए डिग्री का गणितीय मूल निर्दिष्ट करता है। |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/radical/#str) | निर्दिष्ट तर्क से दिए गए डिग्री का गणितीय मूल निर्दिष्ट करता है। |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/set_upper_limit/#imathelement) | ऊपरी सीमा लेता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/set_upper_limit/#str) | ऊपरी सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/set_lower_limit/#imathelement) | निचली सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/set_lower_limit/#str) | निचली सीमा लेता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-ary ऑपरेटर बनाता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-str-str) | N-ary ऑपरेटर बनाता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | समाकल लें |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement) | समाकल लें |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes) | सीमा के बिना समाकल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str-mathlimitlocations) | समाकल लें |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str) | समाकल लें |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/group/#) | नीचे की कर्ली ब्रैकेट का उपयोग करके इस तत्व को समूह में रखता है |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/group/#char-mathtopbotpositions-mathtopbotpositions) | नीचे की कर्ली ब्रैकेट या अन्य समूहित वर्ण का उपयोग करके इस तत्व को समूह में रखता है |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/to_border_box/#) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/to_math_array/#) | वर्टिकल एरे में रखता है |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/accent/#char) | एक एक्सेंट मार्क सेट करता है (इस तत्व के शीर्ष पर एक वर्ण) |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/overbar/#) | इस तत्व के शीर्ष पर एक बार सेट करता है |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/underbar/#) | इस तत्व के नीचे एक बार सेट करता है |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/to_box/#) | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है <br/>            जिसका उपयोग समीकरण के घटकों या अन्य गणितीय पाठ के उदाहरणों को समूहित करने के लिए किया जाता है।<br/>            एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर इम्यूलेटर के रूप में काम कर सकता है, संरेखण बिंदु के साथ या बिना, <br/>            लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस तरह समूहित किया जा सकता है कि उसके भीतर लाइन ब्रेक की अनुमति न हो। |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathbar/get_children/#) | संतान तत्व प्राप्त करें |

### देखें
* क्लास [`MathBar`](/slides/python-net/hi/aspose.slides.mathtext/mathbar)
* क्लास [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)