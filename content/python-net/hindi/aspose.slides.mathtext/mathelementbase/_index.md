---
title: MathElementBase class
second_title: Aspose.Slides for Python के माध्यम से .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathelementbase/
---
## MathElementBase क्लास

IMathElement के लिए बेस क्लास, जिसमें कुछ मेथड्स का कार्यान्वयन है जो सभी विरासत में मिली क्लासेज़ के लिए सामान्य है।  
केवल आंतरिक उपयोग के लिए। विरासत में मिली क्लास IMathElement होनी चाहिए।

MathElementBase प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/join/#imathelement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/join/#str) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/divide/#imathelement) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/divide/#str) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/divide/#imathelement-mathfractiontypes) | निर्दिष्ट प्रकार के साथ इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/divide/#str-mathfractiontypes) | निर्दिष्ट प्रकार के साथ इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/enclose/#) | एक गणितीय तत्व को कोष्ठकों में लपेटता है |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/enclose/#char-char) | एक गणितीय तत्व को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षर फ्रेमिंग के रूप में लपेटता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/function/#imathelement) | इस उदाहरण को फ़ंक्शन नाम के रूप में प्रयोग करते हुए एक तर्क का फ़ंक्शन लेता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/function/#str) | इस उदाहरण को फ़ंक्शन नाम के रूप में प्रयोग करते हुए एक तर्क का फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#imathelement) | इस उदाहरण को तर्क के रूप में लेकर निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#str) | इस उदाहरण को तर्क के रूप में लेकर निर्दिष्ठ फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsofoneargument) | इस उदाहरण को तर्क के रूप में लेकर निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | इस उदाहरण को तर्क के रूप में लेकर निर्दिष्ट फ़ंक्शन और अतिरिक्त निर्दिष्ट तर्क लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsoftwoarguments-str) | इस उदाहरण को तर्क के रूप में लेकर निर्दिष्ट फ़ंक्शन और अतिरिक्त निर्दिष्ट तर्क लेता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/set_subscript/#imathelement) | सबस्क्रिप्ट बनाता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/set_subscript/#str) | सबस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/set_superscript/#imathelement) | सुपरस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/set_superscript/#str) | सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_right/#imathelement-imathelement) | दाएँ पक्ष पर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_right/#str-str) | दाएँ पक्ष पर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_left/#imathelement-imathelement) | बाएँ पक्ष पर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_left/#str-str) | बाएँ पक्ष पर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/radical/#imathelement) | निर्दिष्ट तर्क से दिए गए घात की गणितीय मूल (रूट) निर्दिष्ट करता है। |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/radical/#str) | निर्दिष्ट तर्क से दिए गए घात की गणितीय मूल (रूट) निर्दिष्ट करता है। |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/set_upper_limit/#imathelement) | ऊपरी सीमा लेता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/set_upper_limit/#str) | ऊपरी सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/set_lower_limit/#imathelement) | निचली सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/set_lower_limit/#str) | निचली सीमा लेता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/nary/#mathnaryoperatortypes-imathelement-imathelement) | एक N-ary ऑपरेटर बनाता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/nary/#mathnaryoperatortypes-str-str) | एक N-ary ऑपरेटर बनाता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-imathelement-imathelement) | इंटीग्रल लेता है |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes) | सीमा के बिना इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-str-str-mathlimitlocations) | इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-str-str) | इंटीग्रल लेता है |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/group/#) | निचले कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/group/#char-mathtopbotpositions-mathtopbotpositions) | निचले कर्ली ब्रैकेट या अन्य समूहिंग अक्षर का उपयोग करके इस तत्व को एक समूह में रखता है |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/to_border_box/#) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/to_math_array/#) | एक वर्टिकल एरे में रखता है |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/accent/#char) | एक एक्सेंट मार्क सेट करता है (इस तत्व के ऊपर का अक्षर) |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/overbar/#) | इस तत्व के ऊपर एक बार सेट करता है |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/underbar/#) | इस तत्व के नीचे एक बार सेट करता है |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/to_box/#) | इस तत्व को एक नग़ैरूप बॉक्स (तार्किक समूह) में रखता है <br/>            जो समीकरण के घटकों या अन्य गणितीय पाठ के उदाहरण को समूहित करने के लिए उपयोग किया जाता है।<br/>            एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर एम्यूलेटर के रूप में कार्य कर सकता है, संरेखण बिंदु के साथ या बिना, <br/>            एक लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस प्रकार समूहित हो सकता है जिससे उसके भीतर लाइन ब्रेक की अनुमति न हो। |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase/get_children/#) |  |

### देखें भी
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)