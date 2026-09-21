---
title: MathematicalText class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathematicaltext/
---
## MathematicalText क्लास

गणितीय पाठ

**विरासत:**[`MathematicalText`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext) → [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)

MathematicalText प्रकार निम्नलिखित सदस्य उजागर करता है:

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/__init__/#) | डिफ़ॉल्ट कन्स्ट्रक्टर (String.Empty मान बनाता है) |
| [`__init__(self, math_symbol)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/__init__/#char) | एकल प्रतीक के साथ MathText बनाता है |
| [`__init__(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/__init__/#str) | पाठ से MathematicalText बनाता है |
| [`__init__(self, math_text, portion_format)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/__init__/#str-iportionformat) | पाठ और स्वरूप सेटिंग्स से MathematicalText बनाता है |

## गुण

| गुण | विवरण |
| :- | :- |
| [`value`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/value/) | पाठ मान |
| [`format`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/format/) | पाठ स्वरूपण गुण |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/join/#imathelement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/join/#str) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/divide/#imathelement) | इस हर और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/divide/#str) | इस हर और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/divide/#imathelement-mathfractiontypes) | निर्दिष्ट प्रकार के साथ इस हर और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/divide/#str-mathfractiontypes) | निर्दिष्ट प्रकार के साथ इस हर और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/enclose/#) | एक गणितीय तत्व को कोष्ठकों में घेरता है |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/enclose/#char-char) | एक गणितीय तत्व को निर्दिष्ट अक्षरों में घेरता है जैसे कोष्ठक या अन्य अक्षर फ्रेमिंग के रूप में |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/function/#imathelement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके किसी तर्क का फ़ंक्शन लेता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/function/#str) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके किसी तर्क का फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#imathelement) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#str) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsofoneargument) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और अतिरिक्त तर्क लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-str) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और अतिरिक्त तर्क लेता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/set_subscript/#imathelement) | उपस्क्रिप्ट बनाता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/set_subscript/#str) | उपस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/set_superscript/#imathelement) | सुपरस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/set_superscript/#str) | सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#imathelement-imathelement) | दाएँ ओर उपस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#str-str) | दाएँ ओर उपस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#imathelement-imathelement) | बाएँ ओर उपस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#str-str) | बाएँ ओर उपस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/radical/#imathelement) | निर्दिष्ट तर्क से दी गई डिग्री का गणितीय मूल निर्धारित करता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/radical/#str) | निर्दिष्ट तर्क से दी गई डिग्री का गणितीय मूल निर्धारित करता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#imathelement) | ऊपरी सीमा लेता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#str) | ऊपरी सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#imathelement) | निचली सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#str) | निचली सीमा लेता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-imathelement-imathelement) | एक N-ary ऑपरेटर बनाता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-str-str) | एक N-ary ऑपरेटर बनाता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement) | इंटीग्रल लेता है |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes) | सीमाओं के बिना इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str-mathlimitlocations) | इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str) | इंटीग्रल लेता है |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/group/#) | नीचे की कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/group/#char-mathtopbotpositions-mathtopbotpositions) | समूह वर्ण जैसे नीचे की कर्ली ब्रैकेट या अन्य का उपयोग करके इस तत्व को एक समूह में रखता है |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/to_border_box/#) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/to_math_array/#) | एक लंबवत ऐरे में रखता है |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/accent/#char) | इस तत्व के ऊपर एक एक्सेंट मार्क सेट करता है (इस तत्व के ऊपर एक अक्षर) |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/overbar/#) | इस तत्व के शीर्ष पर एक बार सेट करता है |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/underbar/#) | इस तत्व के नीचे एक बार सेट करता है |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/to_box/#) | इस तत्व को एक गैर-दृश्यमान बॉक्स (तार्किक समूह) में रखता है <br/>            जिसे समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए उपयोग किया जाता है।<br/>            एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) संरेखण बिंदु के साथ या बिना ऑपरेटर एम्यूलेटर के रूप में कार्य कर सकता है, <br/>            लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस तरह समूहित किया जा सकता है कि भीतर लाइन ब्रेक की अनुमति न हो। |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext/get_children/#) |  |

### संबंधित देखें
* क्लास [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)
* क्लास [`MathematicalText`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)