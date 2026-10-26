---
title: MathBlock class
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathblock/
---
## MathBlock वर्ग

MathParagraph के भीतर रखे गए गणितीय पाठ का एक उदाहरण निर्दिष्ट करता है और यह अपनी स्वयं की पंक्ति पर शुरू होता है।  
All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block.

**विरासत:**[`MathBlock`](/slides/python-net/hi/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)

MathBlock प्रकार निम्न सदस्य उजागर करता है:

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/__init__/#) | MathBlock वर्ग का एक नया उदाहरण आरंभ करता है। |
| [`__init__(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/__init__/#imathelement) | एक नया गणितीय ब्लॉक बनाता है और निर्दिष्ट तत्व उसमें रखता है। |
| [`__init__(self, math_elements)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## गुण

| गुण | विवरण |
| :- | :- |
| [`count`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/count/) | संग्रह में वास्तविक रूप से मौजूद चाइल्ड गणित तत्वों की संख्या प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`is_read_only`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/is_read_only/) | गलत लौटाता है क्योंकि चाइल्ड तत्वों का संग्रह बदला जा सकता है। |

निर्दिष्ट सूचकांक पर IMathElement को प्राप्त करता है या सेट करता है।

## इंडेक्सर

| नाम | विवरण |
| :- | :- |
| [`[index]`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/__getitem__/) | आइट्म का शून्य-आधारित सूचकांक |

## विधियाँ

| मेथड | विवरण |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/join/#imathelement) | एक गणितीय तत्व को इस गणितीय 블ॉक के साथ जोड़ता है |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/join/#str) | एक गणितीय पाठ को इस गणितीय 블ॉक के साथ जोड़ता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/divide/#imathelement) | इस अभाजक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/divide/#str) | इस अभाजक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | निर्दिष्ट प्रकार का एक भिन्न बनाता है जिसमें यह अभाजक और निर्दिष्ट हर होते हैं |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | निर्दिष्ट प्रकार का एक भिन्न बनाता है जिसमें यह अभाजक और निर्दिष्ट हर होते हैं |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/enclose/#char-char) | इस 블ॉक के चाइल्ड तत्वों को निर्दिष्ट अक्षरों में रखते है जैसे कोष्ठक या अन्य अक्षर फ्रेमिंग के रूप में |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | इस ब्लॉक के चाइल्ड तत्वों को निर्दिष्ट अक्षरों में रखता है जैसे कोष्ठक या अन्य को फ्रेमिंग के रूप में<br/>            और एक विभाजक अक्षर के साथ सीमांकित करता है |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/enclose/#) | एक गणितीय तत्व को कोष्ठक में रखता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/function/#imathelement) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/function/#str) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर लेता है |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर और अतिरिक्त निर्दिष्ट तर्क के साथ लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर और अतिरिक्त निर्दिष्ट तर्क के साथ लेता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | सबस्क्रिप्ट बनाता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_subscript/#str) | सबस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | सुपरस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_superscript/#str) | सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/radical/#imathelement) | निर्दिष्ट तर्क से दिए गये घातांक की गणितीय मूल को निर्दिष्ट करता है। |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/radical/#str) | निर्दिष्ट तर्क से दिए गये घातांक की गणितीय मूल को निर्दिष्ट करता है। |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | ऊपरी सीमा लेता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | ऊपरी सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | निचली सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | निचली सीमा लेता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | एक N-ary ऑपरेटर बनाता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | एक N-ary ऑपरेटर बनाता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | इंटीग्रल लेता है |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | बिना सीमाओं के इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | बिना सीमाओं के इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | बिना सीमाओं के इंटीग्रल लेता है |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/group/#) | निचले कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | निचले कर्ली ब्रैकेट या अन्य किसी समूह अक्षर का उपयोग करके इस तत्व को एक समूह में रखता है |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/to_border_box/#) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/to_math_array/#) | चाइल्ड तत्वों को एक लंबवत सरणी में रखता है |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/accent/#char) | एक एक्सेंट मार्क सेट करता है (इस तत्व के ऊपर का अक्षर) |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/overbar/#) | इस तत्व के ऊपर एक बार सेट करता है |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/underbar/#) | इस तत्व के नीचे एक बार सेट करता है |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/to_box/#) | इस तत्व को एक गैर-दृश्यमान बॉक्स (तार्किक समूह) में रखता है <br/>            जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है।<br/>            एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर इम्यूलेटर के रूप में काम कर सकता है, संरेखण बिंदु के साथ या बिना, <br/>            एक लाइन ब्रेक बिंदु के रूप में, या इस प्रकार समूहित किया जा सकता है कि उसके भीतर लाइन ब्रेक की अनुमति न हो। |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/get_children/#) | चाइल्ड तत्व प्राप्त करें |
| [`add(self, item)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/add/#imathelement) | संग्रह के अंत में एक गणित तत्व जोड़ता है। |
| [`clear(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/clear/#) | संग्रह से सभी तत्वों को हटाता है। |
| [`contains(self, item)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/contains/#imathelement) | निर्धारित करता है कि क्या संग्रह में कोई विशिष्ट मान मौजूद है। |
| [`copy_to(self, array, array_index)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | निर्दिष्ट एरे में कॉपी करता है। |
| [`remove(self, item)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/remove/#imathelement) | संग्रह से किसी विशिष्ट वस्तु की पहली घटना को हटाता है। |
| [`index_of(self, item)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/index_of/#imathelement) | संग्रह में किसी विशिष्ट गणितीय तत्व का सूचकांक निर्धारित करता है। |
| [`insert(self, index, item)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | निर्दिष्ट सूचकांक पर संग्रह में एक MathElement डालता है। |
| [`remove_at(self, index)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/remove_at/#int) | संग्रह के निर्दिष्ट सूचकांक पर तत्व को हटाता है। |
| [`join_block(self, other)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/join_block/#imathblock) | एक अन्य गणितीय ब्लॉक को इस के साथ जोड़ता है |
| [`delimit(self, separator_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/delimit/#char) | कोष्ठकों के बिना एक विभाजक अक्षर के साथ चाइल्ड तत्वों को सीमांकित करता है |
| [`write_as_math_ml(self, stream)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | इस [`MathBlock`](/slides/python-net/hi/aspose.slides.mathtext/mathblock) की सामग्री को MathML के रूप में सहेजता है |

### संबंधित देखें
* वर्ग [`MathBlock`](/slides/python-net/hi/aspose.slides.mathtext/mathblock)
* वर्ग [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)