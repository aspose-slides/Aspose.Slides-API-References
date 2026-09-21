---
title: MathFunction class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathfunction/
---
## MathFunction वर्ग

एक तर्क का फ़ंक्शन निर्दिष्ट करता है।

**विरासत:**[`MathFunction`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction) → [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)

MathFunction प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self, func_name, base_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/__init__/#imathelement-imathelement) | MathFunction वर्ग का एक नया उदाहरण प्रारंभ करता है। |
| [`__init__(self, func_name, base_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/__init__/#str-imathelement) | MathFunction वर्ग का एक नया उदाहरण प्रारंभ करता है। |

## Properties

| Property | Description |
| :- | :- |
| [`name`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/name/) | फ़ंक्शन नाम<br/>            उदाहरण के लिए, फ़ंक्शन नाम sin और cos हैं |
| [`base`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/base/) | फ़ंक्शन तर्क |

## Methods

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/join/#imathelement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/join/#str) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/divide/#imathelement) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/divide/#str) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/divide/#imathelement-mathfractiontypes) | इस अंशांक और निर्दिष्ट हर के साथ निर्दिष्ट प्रकार का एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/divide/#str-mathfractiontypes) | इस अंशांक और निर्दिष्ट हर के साथ निर्दिष्ट प्रकार का एक भिन्न बनाता है |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/enclose/#) | एक गणितीय तत्व को कोष्ठकों में घेरता है |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/enclose/#char-char) | एक गणितीय तत्व को निर्दिष्ट वर्णों में घेरता है, जैसे कोष्ठक या अन्य वर्ण फ्रेमिंग के रूप में |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/function/#imathelement) | इस उदाहरण का उपयोग फ़ंक्शन नाम के रूप में करके तर्क का फ़ंक्शन लेता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/function/#str) | इस उदाहरण का उपयोग फ़ंक्शन नाम के रूप में करके तर्क का फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/as_argument_of_function/#imathelement) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/as_argument_of_function/#str) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsofoneargument) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | इस उदाहरण को तर्क के रूप में और अतिरिक्त निर्दिष्ट तर्क का उपयोग करके फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | इस उदाहरण को तर्क के रूप में और अतिरिक्त निर्दिष्ट तर्क का उपयोग करके फ़ंक्शन लेता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/set_subscript/#imathelement) | सबस्क्रिप्ट बनाता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/set_subscript/#str) | सबस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/set_superscript/#imathelement) | सुपरस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/set_superscript/#str) | सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_right/#imathelement-imathelement) | दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_right/#str-str) | दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_left/#imathelement-imathelement) | बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_left/#str-str) | बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/radical/#imathelement) | निर्दिष्ट तर्क से दिए गए घातांक की गणितीय मूल को निर्दिष्ट करता है। |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/radical/#str) | निर्दिष्ट तर्क से दिए गए घातांक की गणितीय मूल को निर्दिष्ट करता है। |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/set_upper_limit/#imathelement) | ऊपरी सीमा लेता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/set_upper_limit/#str) | ऊपरी सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/set_lower_limit/#imathelement) | निचली सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/set_lower_limit/#str) | निचली सीमा लेता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/nary/#mathnaryoperatortypes-imathelement-imathelement) | एक N-आर्य ऑपरेटर बनाता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/nary/#mathnaryoperatortypes-str-str) | एक N-आर्य ऑपरेटर बनाता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-imathelement-imathelement) | इंटीग्रल लेता है |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes) | सीमाओं के बिना इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-str-str-mathlimitlocations) | इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-str-str) | इंटीग्रल लेता है |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/group/#) | निचले कर्ली ब्रेकेट का उपयोग करके इस तत्व को समूह में रखता है |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/group/#char-mathtopbotpositions-mathtopbotpositions) | निचले कर्ली ब्रेकेट या अन्य समूह वर्ण का उपयोग करके इस तत्व को समूह में रखता है |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/to_border_box/#) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/to_math_array/#) | एक लंबवत सरणी में रखता है |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/accent/#char) | एक उच्चारण चिह्न (इस तत्व के ऊपर का वर्ण) सेट करता है |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/overbar/#) | इस तत्व के शीर्ष पर एक रेखा सेट करता है |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/underbar/#) | इस तत्व के नीचे एक रेखा सेट करता है |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/to_box/#) | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है <br/>            जिसका उपयोग समीकरण के घटकों या अन्य गणितीय पाठ के भागों को समूहित करने के लिए किया जाता है।<br/>            एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) संरेखण बिंदु के साथ या बिना ऑपरेटर एमुलेटर के रूप में कार्य कर सकता है, <br/>            लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस तरह समूहित किया जा सकता है कि उसके भीतर लाइन ब्रेक की अनुमति न हो। |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction/get_children/#) | संतान तत्व प्राप्त करें |


### संबंधित देखें
* वर्ग [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)
* वर्ग [`MathFunction`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)