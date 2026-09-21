---
title: MathDelimiter class
second_title: Aspose.Slides for Python के लिये .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter क्लास

डिलीमीटर ऑब्जेक्ट को निर्दिष्ट करता है, जिसमें प्रारंभिक और समाप्ति अक्षर होते हैं (जैसे कोष्ठक, ब्रेस, ब्रैकेट, और वर्टिकल बार), तथा इसके भीतर एक या अधिक गणितीय तत्व होते हैं, जो एक निर्दिष्ट अक्षर द्वारा अलग किए जाते हैं।  
उदाहरण: (𝑥2); [𝑥2|𝑦2]

**विरासत:**[`MathDelimiter`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)

MathDelimiter type निम्नलिखित सदस्य प्रदान करता है:

## कन्स्ट्रक्टर

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | निर्दिष्ट तत्व को एकल बेस आर्ग्युमेंट के रूप में लेकर MathDelimiter को प्रारम्भ करता है |

## गुण

| Property | Description |
| :- | :- |
| [`arguments`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/arguments/) | एक या अधिक गणितीय तत्व डिलीमीटर अक्षरों द्वारा अलग किए गए |
| [`beginning_character`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character प्रारंभ, या उद्घाटन, डिलीमीटर अक्षर को निर्दिष्ट करता है। <br/> गणितीय डिलीमीटर ऐसे समावेशी अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट, और ब्रेस।<br/> डिफ़ॉल्ट: '(' |
| [`separator_character`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character वह अक्षर निर्दिष्ट करता है जो डिलीमीटर ऑब्जेक्ट में तर्कों को अलग करता है। <br/> डिफ़ॉल्ट: '\|' |
| [`ending_character`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character समाप्त, या बंद, डिलीमीटर अक्षर को निर्दिष्ट करता है। <br/> गणितीय डिलीमीटर ऐसे समावेशी अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट, और ब्रेस।<br/> डिफ़ॉल्ट: ')' |
| [`grow_to_match_operand_height`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | BeginningCharacter, SeparatorCharacter, EndingCharacter के वृद्धि को निर्दिष्ट करता है<br/> जब true हो, तो डिलीमीटर ऊर्ध्वाधर रूप से बढ़ते हैं ताकि उनके ऑपरेण्ड की ऊँचाई से मेल खाएँ।<br/> डिफ़ॉल्ट मान true है |
| [`delimiter_shape`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | डिलीमीटर ऑब्जेक्ट में डिलीमीटर के आकार को निर्दिष्ट करता है। <br/> जब MathDelimiterShape.Centered होता है, तो डिलीमीटर गणितीय पाठ के गणितीय धुरी के चारों ओर केंद्रित होते हैं <br/> और उनकी सामग्री की पूरी ऊँचाई में फिट होने के लिये समायोजित होते हैं।<br/> जब MathDelimiterShape.Match होता है, तो उनकी ऊँचाई और आकार को ठीक उनके सामग्री से मिलाने के लिये बदला जाता है |

## मेथड्स

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/join/#str) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | इस अंशज और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/divide/#str) | इस अंशज और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | निर्दिष्ट प्रकार का भिन्न इस अंशज और निर्दिष्ट हर के साथ बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | निर्दिष्ट प्रकार का भिन्न इस अंशज और निर्दिष्ट हर के साथ बनाता है |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | एक गणितीय तत्व को निर्दिष्ट अक्षरों में सम्मिलित करता है जैसे कोष्ठक या अन्य अक्षर फ्रेमिंग के रूप में |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/enclose/#) | एक गणितीय तत्व को कोष्ठक में सम्मिलित करता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/function/#str) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और निर्दिष्ट अतिरिक्त तर्क |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और निर्दिष्ट अतिरिक्त तर्क |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | सबस्क्रिप्ट बनाता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | सबस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | सुपरस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | निर्दिष्ट तर्क से निर्दिष्ट डिग्री की गणितीय मूल निर्धारित करता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/radical/#str) | निर्दिष्ट तर्क से निर्दिष्ट डिग्री की गणितीय मूल निर्धारित करता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | ऊपरी सीमा लेता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | ऊपरी सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | निचली सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | निचली सीमा लेता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | एक N-ary ऑपरेटर बनाता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | एक N-ary ऑपरेटर बनाता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | इंटीग्रल लेता है |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | सीमा के बिना इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | इंटीग्रल लेता है |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/group/#) | इस तत्व को नीचे की कर्ली ब्रैकेट का उपयोग करके समूह में रखता है |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | इस तत्व को समूह में रखता है, जैसे नीचे की कर्ली ब्रैकेट या अन्य समूह अक्षर का उपयोग करके |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | एक ऊर्ध्वाधर एरे में रखता है |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/accent/#char) | इस तत्व के ऊपर एक एक्सेंट मार्क (अक्षर) सेट करता है |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/overbar/#) | इस तत्व के ऊपर एक बार सेट करता है |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/underbar/#) | इस तत्व के नीचे एक बार सेट करता है |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/to_box/#) | इस तत्व को एक गैर-भौतिक बॉक्स (तार्किक समूह) में रखता है <br/> जो समीकरण के घटकों या अन्य गणितीय पाठ के उदाहरण को समूहित करने के लिये उपयोग किया जाता है।<br/> एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर एम्यूलेटर के रूप में काम कर सकता है, चाहे उसके पास संरेखण बिंदु हो या न हो, <br/> लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या ऐसे समूहित किया जा सकता है कि भीतर लाइन ब्रेक न हो |
| [`delimit(self, separator_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/delimit/#char) | निर्दिष्ट डिलीमीटर अक्षर का उपयोग करके तर्कों को सीमित करता है |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter/get_children/#) | बच्चों के तत्व प्राप्त करता है |


### देखें
* क्लास [`MathDelimiter`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter)
* क्लास [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)