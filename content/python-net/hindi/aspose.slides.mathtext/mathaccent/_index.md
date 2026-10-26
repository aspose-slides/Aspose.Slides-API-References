---
title: MathAccent class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathaccent/
---
## MathAccent क्लास

एक्सेंट फ़ंक्शन को निर्दिष्ट करता है, जो एक बेस और एक संयोजी उच्चारण चिह्न से बना होता है उदाहरण: 𝑎́

**विरासत:**[`MathAccent`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent) → [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)

MathAccent प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## निर्माताओं

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/__init__/#imathelement) | निर्दिष्ट गणितीय तत्व पर एक गणितीय एक्सेंट बनाता है जिसमें डिफ़ॉल्ट एक्सेंट अक्षर मान होता है |
| [`__init__(self, element, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/__init__/#imathelement-char) | निर्दिष्ट गणितीय तत्व पर एक गणितीय एक्सेंट बनाता है |

## गुण

| गुण | विवरण |
| :- | :- |
| [`base`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/base/) | वह तर्क जिस पर एक्सेंट लगाया गया |
| [`character`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/character/) | एक्सेंट वर्ण<br/>            मान (U+0300–U+036F) या (U+20D0–U+20EF) की सीमा में होना चाहिए<br/>            डिफ़ॉल्ट मान: संयोजी सर्क़्लिफ़ एक्सेंट (U+0302) |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/join/#imathelement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/join/#str) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/divide/#imathelement) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/divide/#str) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/divide/#imathelement-mathfractiontypes) | निर्दिष्ट प्रकार के साथ इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/divide/#str-mathfractiontypes) | निर्दिष्ट प्रकार के साथ इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/enclose/#) | एक गणितीय तत्व को कोष्ठकों में संलग्न करता है |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/enclose/#char-char) | एक गणितीय तत्व को निर्दिष्ट अक्षरों में, जैसे कोष्ठक या अन्य अक्षर फ्रेमिंग के रूप में, संलग्न करता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/function/#imathelement) | एक तर्क का फ़ंक्शन लेता है जिसमें यह इंस्टेंस फ़ंक्शन नाम के रूप में उपयोग होता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/function/#str) | एक तर्क का फ़ंक्शन लेता है जिसमें यह इंस्टेंस फ़ंक्शन नाम के रूप में उपयोग होता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/as_argument_of_function/#imathelement) | निर्दिष्ट फ़ंक्शन लेता है जिसमें यह इंस्टेंस तर्क के रूप में उपयोग होता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/as_argument_of_function/#str) | निर्दिष्ट फ़ंक्शन लेता है जिसमें यह इंस्टेंस तर्क के रूप में उपयोग होता है |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsofoneargument) | निर्दिष्ट फ़ंक्शन लेता है जिसमें यह इंस्टेंस तर्क के रूप में उपयोग होता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | निर्दिष्ट फ़ंक्शन लेता है जिसमें यह इंस्टेंस तर्क के रूप में और अतिरिक्त निर्दिष्ट तर्क के साथ उपयोग होता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-str) | निर्दिष्ट फ़ंक्शन लेता है जिसमें यह इंस्टेंस तर्क के रूप में और अतिरिक्त निर्दिष्ट तर्क के साथ उपयोग होता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/set_subscript/#imathelement) | सबस्क्रिप्ट बनाता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/set_subscript/#str) | सबस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/set_superscript/#imathelement) | सुपरस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/set_superscript/#str) | सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#imathelement-imathelement) | दाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#str-str) | दाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#imathelement-imathelement) | बाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#str-str) | बाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/radical/#imathelement) | निर्दिष्ट तर्क से दी गई डिग्री का गणितीय मूल निर्धारित करता है। |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/radical/#str) | निर्दिष्ट तर्क से दी गई डिग्री का गणितीय मूल निर्धारित करता है। |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/set_upper_limit/#imathelement) | ऊपरी सीमा लेता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/set_upper_limit/#str) | ऊपरी सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/set_lower_limit/#imathelement) | निचली सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/set_lower_limit/#str) | निचली सीमा लेता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-imathelement-imathelement) | एक N-ary ऑपरेटर बनाता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-str-str) | एक N-ary ऑपरेटर बनाता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement) | इंटीग्रल लेता है |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes) | सीमाओं के बिना इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str-mathlimitlocations) | इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str) | इंटीग्रल लेता है |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/group/#) | इस तत्व को नीचे वाले कर्ली ब्रैकेट का उपयोग करके समूह में रखता है |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/group/#char-mathtopbotpositions-mathtopbotpositions) | इस तत्व को समूह में रखता है, जैसे नीचे वाला कर्ली ब्रैकेट या अन्य ग्रूपिंग अक्षर का उपयोग करके |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/to_border_box/#) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/to_math_array/#) | एक लंबवत सरणी में रखता है |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/accent/#char) | एक एक्सेंट मार्क सेट करता है (इस तत्व के ऊपर एक अक्षर) |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/overbar/#) | इस तत्व के ऊपर एक बार सेट करता है |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/underbar/#) | इस तत्व के नीचे एक बार सेट करता है |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/to_box/#) | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है <br/>            जो समीकरण के घटकों या गणितीय पाठ के अन्य उदाहरणों को समूहित करने के लिए उपयोग किया जाता है।<br/>            एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर एमुलेटर के रूप में कार्य कर सकता है, संरेखण बिंदु के साथ या बिना, <br/>            लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस प्रकार समूहित किया जा सकता है कि भीतर लाइन ब्रेक की इजाज़त न हो। |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent/get_children/#) | संतान तत्व प्राप्त करें |


### देखें भी
* क्लास [`MathAccent`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent)
* क्लास [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)