---
title: MathFraction class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathfraction/
---
## MathFraction वर्ग

एक अंक्षांक और हर द्वारा विभाजित अंश बार के साथ अंश वस्तु को निर्दिष्ट करता है, जिसमें अंक्षांक और हर शामिल होते हैं।  
अंश बार क्षैतिज या विकर्ण हो सकता है, अंश गुणों के आधार पर।  
अंश वस्तु का उपयोग स्टैक फ़ंक्शन को दर्शाने के लिए भी किया जाता है, जो एक तत्व को दूसरे के ऊपर रखता है, बिना अंश बार के।

**Inheritance:**[`MathFraction`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction) → [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)

MathFraction प्रकार निम्नलिखित सदस्य प्रस्तुत करता है:

## निर्माता

| Constructor | Description |
| :- | :- |
| [`__init__(self, numerator, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement-mathfractiontypes) | निर्दिष्ट अंक्षांक, हर और प्रकार के साथ MathFraction को आरंभ करता है |
| [`__init__(self, numerator, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement) | निर्दिष्ट अंक्षांक और हर के साथ 'Bar' प्रकार का MathFraction आरंभ करता है |

## गुण

| Property | Description |
| :- | :- |
| [`fraction_type`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/fraction_type/) | Fraction type<br/>            डिफ़ॉल्ट: Bar |
| [`numerator`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/numerator/) | अंक्षांक |
| [`denominator`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/denominator/) | हर |

## विधियाँ

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/join/#imathelement) | गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/join/#str) | गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/divide/#imathelement) | इस अंक्षांक और निर्दिष्ट हर के साथ एक अंश बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/divide/#str) | इस अंक्षांक और निर्दिष्ट हर के साथ एक अंश बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/divide/#imathelement-mathfractiontypes) | निर्दिष्ट प्रकार का अंश इस अंक्षांक और निर्दिष्ट हर के साथ बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/divide/#str-mathfractiontypes) | निर्दिष्ट प्रकार का अंश इस अंक्षांक और निर्दिष्ट हर के साथ बनाता है |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/enclose/#) | गणितीय तत्व को कोष्ठकों में बंद करता है |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/enclose/#char-char) | गणितीय तत्व को कोष्ठक या अन्य वर्णों जैसे निर्दिष्ट वर्णों में फ्रेमिंग के रूप में बंद करता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/function/#imathelement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/function/#str) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/as_argument_of_function/#imathelement) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/as_argument_of_function/#str) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsofoneargument) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और अतिरिक्त निर्दिष्ट तर्क भी लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और अतिरिक्त निर्दिष्ट तर्क भी लेता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/set_subscript/#imathelement) | सबस्क्रिप्ट बनाता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/set_subscript/#str) | सबस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/set_superscript/#imathelement) | सुपर्सक्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/set_superscript/#str) | सुपर्सक्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#imathelement-imathelement) | दाएँ पक्ष पर सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#str-str) | दाएँ पक्ष पर सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#imathelement-imathelement) | बाएँ पक्ष पर सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#str-str) | बाएँ पक्ष पर सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/radical/#imathelement) | निर्दिष्ट तर्क से दी गई डिग्री की गणितीय मूल को निर्दिष्ट करता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/radical/#str) | निर्दिष्ट तर्क से दी गई डिग्री की गणितीय मूल को निर्दिष्ट करता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/set_upper_limit/#imathelement) | ऊपरी सीमा लेता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/set_upper_limit/#str) | ऊपरी सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/set_lower_limit/#imathelement) | निचली सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/set_lower_limit/#str) | निचली सीमा लेता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-ary ऑपरेटर बनाता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-str-str) | N-ary ऑपरेटर बनाता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | समाकलन लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement) | समाकलन लेता है |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes) | सीमाओं के बिना समाकलन लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str-mathlimitlocations) | समाकलन लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str) | समाकलन लेता है |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/group/#) | निचले कर्ली ब्रैकेट का उपयोग करके इस तत्व को समूह में रखता है |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/group/#char-mathtopbotpositions-mathtopbotpositions) | निचले कर्ली ब्रैकेट या अन्य समूहित वर्ण का उपयोग करके इस तत्व को समूह में रखता है |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/to_border_box/#) | इस तत्व को बॉर्डर बॉक्स में रखता है |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | इस तत्व को बॉर्डर बॉक्स में रखता है |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/to_math_array/#) | एक लंबवत क्रम में रखता है |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/accent/#char) | एक एक्सेंट चिह्न सेट करता है (इस तत्व के शीर्ष पर एक अक्षर) |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/overbar/#) | इस तत्व के शीर्ष पर एक बार सेट करता है |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/underbar/#) | इस तत्व के निचले भाग पर एक बार सेट करता है |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/to_box/#) | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है <br/>            जिसका उपयोग समीकरण के घटकों या अन्य गणितीय पाठ के उदाहरणों को समूहित करने के लिए किया जाता है।<br/>            एक बॉक्स किया गया वस्तु (उदाहरण के लिए) एक ऑपरेटर एमुलेटर के रूप में कार्य कर सकता है, संरेखण बिंदु के साथ या बिना, <br/>            रेखा मध्यस्थ बिंदु के रूप में, या इस तरह समूहित किया जा सकता है कि भीतर रेखा तोड़ने की अनुमति न हो। |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction/get_children/#) | संतान तत्व प्राप्त करें |

### देखें भी
* वर्ग [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)
* वर्ग [`MathFraction`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)