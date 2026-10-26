---
title: MathBox class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathbox/
---
## MathBox क्लास

गणितीय तत्व के तार्किक बॉक्सिंग (पैकेजिंग) को निर्दिष्ट करता है। उदाहरण के लिए, एक बॉक्स्ड ऑब्जेक्ट ऑपरेटर एम्यूलेटर के रूप में कार्य कर सकता है, संरेखण बिंदु के साथ या बिना, लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस तरह समूहित किया जा सकता है कि उसके भीतर लाइन ब्रेक की अनुमति न हो। उदाहरण के लिए, "==" ऑपरेटर को बॉक्स्ड होना चाहिए ताकि लाइन ब्रेक न हो।

**विरासत:**[`MathBox`](/slides/python-net/hi/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)

The MathBox type exposes the following members:

## कंस्ट्रक्टर्स

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/__init__/#imathelement) | Initializes MathBox with the specified element as an argument |

## प्रॉपर्टीज

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/base/) | आधार तर्क |
| [`operator_emulator`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/operator_emulator/) | ऑपरेटर एम्यूलेटर.<br/>            जब true हो, बॉक्स और इसकी सामग्री एक एकल ऑपरेटर की तरह व्यवहार करती है और ऑपरेटर के गुणों को विरासत में लेती है। <br/>            इसका मतलब है, उदाहरण के लिए, कि यह अक्षर लाइन ब्रेक के बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटरों के साथ संरेखित किया जा सकता है।<br/>            ऑपरेटर एम्यूलेटर अक्सर तब उपयोग किए जाते हैं जब एक या अधिक glyphs मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='.<br/>            डिफॉल्ट मान: false |
| [`no_break`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/no_break/) | कोई ब्रेक नहीं<br/>            यह प्रॉपर्टी ऑब्जेक्ट बॉक्स पर "unbreakable" प्रॉपर्टी को निर्दिष्ट करती है। जब true हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता।<br/>            यह एक से अधिक बाइनरी ऑपरेटरों वाले ऑपरेटर एम्यूलेटर्स के लिए महत्वपूर्ण हो सकता है। <br/>            जब यह तत्व निर्दिष्ट नहीं किया गया है, तो बॉक्स के भीतर ब्रेक हो सकते हैं।<br/>            डिफॉल्ट: true |
| [`differential`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/differential/) | डिफरेंशियल<br/>            जब true हो, बॉक्स एक डिफरेंशियल (उदा., 𝑑𝑥 किसी इंटेग्रैंड में) की तरह कार्य करता है, और गणितीय डिफरेंशियल के लिए उचित <br/>            क्षैतिज स्पेसिंग प्राप्त करता है।<br/>            डिफॉल्ट: false |
| [`alignment_point`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/alignment_point/) | जब true हो, यह ऑपरेटर एम्यूलेटर एक संरेखण बिंदु के रूप में कार्य करता है; अर्थात्, <br/>            अन्य समीकरणों में निर्दिष्ट संरेखण बिंदुओं को इसके साथ संरेखित किया जा सकता है।<br/>            डिफॉल्ट: false |
| [`explicit_break`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/explicit_break/) | स्पष्ट ब्रेक निर्दिष्ट करता है कि Box ऑब्जेक्ट की शुरुआत में लाइन ब्रेक है या नहीं, <br/>            जिससे लाइन बॉक्स ऑब्जेक्ट की शुरुआत में मोड़ लेती है।<br/>            पिछले गणितीय पाठ की पंक्ति में ऑपरेटर की संख्या निर्दिष्ट करता है जो<br/>            वर्तमान गणितीय पाठ की पंक्ति के लिए संरेखण बिंदु के रूप में उपयोग की जाएगी<br/>            संभावित मान: 1..255<br/>            डिफॉल्ट: 0 (कोई स्पष्ट ब्रेक नहीं) |

## मेथड्स

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/join/#imathelement) | गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/join/#str) | गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/divide/#imathelement) | इस अंशज और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/divide/#str) | इस अंशज और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | निर्दिष्ट प्रकार का एक भिन्न बनाता है इस अंशज और निर्दिष्ट हर के साथ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | निर्दिष्ट प्रकार का एक भिन्न बनाता है इस अंशज और निर्दिष्ट हर के साथ |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/enclose/#) | गणितीय तत्व को कोष्ठक में घेरता है |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/enclose/#char-char) | निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षरों में फ्रेमिंग के साथ गणितीय तत्व को घेरता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/function/#imathelement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/function/#str) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में उपयोग करके लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में उपयोग करके लेता है |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में उपयोग करके लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में उपयोग करके लेता है और अतिरिक्त तर्क निर्दिष्ट करता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में उपयोग करके लेता है और अतिरिक्त तर्क निर्दिष्ट करता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | सबस्क्रिप्ट बनाता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/set_subscript/#str) | सबस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | सुपरसक्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/set_superscript/#str) | सुपरसक्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | दाएँ तरफ़ सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | दाएँ तरफ़ सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | बाएँ तरफ़ सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | बाएँ तरफ़ सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/radical/#imathelement) | दिए गए डिग्री की गणितीय मूल निकालता है निर्दिष्ट तर्क से। |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/radical/#str) | दिए गए डिग्री की गणितीय मूल निकालता है निर्दिष्ट तर्क से। |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | ऊपरी सीमा लेता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | ऊपरी सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | निचली सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | निचली सीमा लेता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | एक N-ary ऑपरेटर बनाता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | एक N-ary ऑपरेटर बनाता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | इंटीग्रल लेता है |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | सीमाओं के बिना इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | इंटीग्रल लेता है |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/group/#) | इस तत्व को नीचे की कर्ली ब्रैकेट का उपयोग करके समूह में रखता है |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | इस तत्व को समूहित अक्षर जैसे नीचे की कर्ली ब्रैकेट या अन्य का उपयोग करके समूह में रखता है |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/to_border_box/#) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/to_math_array/#) | एक लंबवत एरे में रखता है |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/accent/#char) | एक एक्सेंट मार्क सेट करता है (इस तत्व के ऊपर एक अक्षर) |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/overbar/#) | इस तत्व के ऊपर एक बार सेट करता है |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/underbar/#) | इस तत्व के नीचे एक बार सेट करता है |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/to_box/#) | इस तत्व को एक नॉन-विजुअल बॉक्स (तार्किक समूह) में रखता है <br/>            जिसका उपयोग समीकरण के घटकों या अन्य गणितीय टेक्स्ट के उदाहरण को समूहित करने के लिए किया जाता है।<br/>            एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) ऑपरेटर एम्यूलेटर के रूप में कार्य कर सकता है, संरेखण बिंदु के साथ या बिना, <br/>            लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस तरह समूहित किया जा सकता है कि उसके भीतर लाइन ब्रेक की अनुमति न हो। |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathbox/get_children/#) | संतान तत्व प्राप्त करें |

### संबंधित देखें
* क्लास [`MathBox`](/slides/python-net/hi/aspose.slides.mathtext/mathbox)
* क्लास [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)