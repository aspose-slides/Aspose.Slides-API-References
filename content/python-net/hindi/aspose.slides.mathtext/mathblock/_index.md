---
title: MathBlock class
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathblock/
---
## MathBlock क्लास

एक MathParagraph के भीतर स्थित गणितीय पाठ का एक उदाहरण निर्दिष्ट करता है जो अपनी स्वयं की पंक्ति से शुरू होता है। सभी गणितीय ज़ोन, जिसमें समीकरण, अभिव्यक्तियाँ, समीकरणों या अभिव्यक्तियों की सरणियाँ, और सूत्र शामिल हैं, को गणितीय ब्लॉक द्वारा प्रदर्शित किया जाता है।

**Inheritance:**[`MathBlock`](/slides/python-net/hi/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)

The MathBlock type exposes the following members:

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/__init__/#) | MathBlock क्लास की नई instance को प्रारंभ करता है। |
| [`__init__(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/__init__/#imathelement) | एक नया गणितीय ब्लॉक बनाता है और निर्दिष्ट तत्व उसमें रखता है |
| [`__init__(self, math_elements)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## गुण

| गुण | विवरण |
| :- | :- |
| [`count`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/count/) | कलेक्शन में वास्तव में सम्मिलित बच्चों की गणितीय तत्वों की संख्या प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`is_read_only`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/is_read_only/) | false लौटाता है क्योंकि बच्चों के तत्वों का कलेक्शन संशोधित किया जा सकता है। |

निर्दिष्ट अनुक्रमांक पर IMathElement को प्राप्त करता है या निर्धारित करता है।

## इंडेक्सर

| नाम | विवरण |
| :- | :- |
| [`[index]`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/__getitem__/) | आइटम का शून्य-आधारित अनुक्रमांक |

## विधियां

| विधि | विवरण |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/join/#imathelement) | एक गणितीय तत्व को इस गणितीय ब्लॉक के साथ जोड़ता है |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/join/#str) | एक गणितीय पाठ को इस गणितीय ब्लॉक के साथ जोड़ता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/divide/#imathelement) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/divide/#str) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | निर्दिष्ट प्रकार का एक भिन्न इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | निर्दिष्ट प्रकार का एक भिन्न इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/enclose/#) | एक गणितीय तत्व को कोष्ठकों में घेरता है |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/enclose/#char-char) | इस ब्लॉक के बच्चों के तत्वों को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षरों में फ्रेमिंग के रूप में घेरता है |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | इस ब्लॉक के बच्चों के तत्वों को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य में फ़्रेमिंग के रूप में घेरता है<br/>            और विभाजन अक्षर के साथ सीमांकित करता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/function/#imathelement) | इस instance को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/function/#str) | इस instance को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | इस instance को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | इस instance को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | इस instance को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | इस instance को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क के साथ निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | इस instance को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क के साथ निर्दिष्ट फ़ंक्शन लेता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | सबस्क्रिप्ट बनाता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_subscript/#str) | सबस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | सुपरसक्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_superscript/#str) | सुपरसक्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | दाएँ तरफ सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | दाएँ तरफ सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | बाएँ तरफ सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | बाएँ तरफ सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/radical/#imathelement) | निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल निर्धारित करता है। |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/radical/#str) | निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल निर्धारित करता है। |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | ऊपरी सीमा लेता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | ऊपरी सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | निचली सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | निचली सीमा लेता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | एक N-ary ऑपरेटर बनाता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | एक N-ary ऑपरेटर बनाता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | समाकल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | समाकल लेता है |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | बिना सीमाओं के समाकल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | बिना सीमाओं के समाकल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | बिना सीमाओं के समाकल लेता है |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/group/#) | नीचे की कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | नीचे की कर्ली ब्रैकेट या किसी अन्य समूहिंग अक्षर का उपयोग करके इस तत्व को एक समूह में रखता है |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/to_border_box/#) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/to_math_array/#) | बच्चों के तत्वों को एक लंबवत सरणी में रखता है |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/accent/#char) | एक उच्चारण चिह्न सेट करता है (इस तत्व के ऊपर एक अक्षर) |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/overbar/#) | इस तत्व के ऊपर एक बार सेट करता है |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/underbar/#) | इस तत्व के नीचे एक बार सेट करता है |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/to_box/#) | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है <br/>            जो समीकरण या गणितीय पाठ के अन्य उदाहरण के घटकों को समूहित करने के लिए उपयोग किया जाता है।<br/>            एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) संरेखण बिंदु के साथ या बिना एक ऑपरेटर अनुकरणकर्ता के रूप में कार्य कर सकता है, <br/>            एक लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस प्रकार समूहित किया जा सकता है कि भीतर लाइन ब्रेक की अनुमति न हो। |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/get_children/#) | बच्चों के तत्व प्राप्त करें |
| [`add(self, item)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/add/#imathelement) | कलेक्शन के अंत में एक गणितीय तत्व जोड़ता है। |
| [`clear(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/clear/#) | कलेक्शन से सभी तत्व हटाता है। |
| [`contains(self, item)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/contains/#imathelement) | निर्धारित करता है कि कलेक्शन में कोई विशेष मान मौजूद है या नहीं। |
| [`copy_to(self, array, array_index)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | निर्दिष्ट एरे में कॉपी करता है। |
| [`remove(self, item)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/remove/#imathelement) | कलेक्शन से किसी विशिष्ट वस्तु की पहली उपस्थिति हटाता है। |
| [`index_of(self, item)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/index_of/#imathelement) | कलेक्शन में किसी विशिष्ट गणितीय तत्व का अनुक्रमांक निर्धारित करता है। |
| [`insert(self, index, item)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | निर्दिष्ट अनुक्रमांक पर कलेक्शन में एक MathElement सम्मिलित करता है। |
| [`remove_at(self, index)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/remove_at/#int) | कलेक्शन के निर्दिष्ट अनुक्रमांक पर तत्व को हटाता है। |
| [`join_block(self, other)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/join_block/#imathblock) | एक अन्य गणितीय ब्लॉक को इस के साथ जोड़ता है |
| [`delimit(self, separator_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/delimit/#char) | कोष्ठकों के बिना विभाजन अक्षर के साथ बच्चों के तत्वों को सीमांकित करता है |
| [`write_as_math_ml(self, stream)`](/slides/python-net/hi/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | इस [`MathBlock`](/slides/python-net/hi/aspose.slides.mathtext/mathblock) की सामग्री को MathML के रूप में सहेजता है |


### संबंधित देखें
* क्लास [`MathBlock`](/slides/python-net/hi/aspose.slides.mathtext/mathblock)
* क्लास [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)