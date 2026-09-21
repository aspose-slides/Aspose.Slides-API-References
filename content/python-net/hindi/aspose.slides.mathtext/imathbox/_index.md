---
title: IMathBox class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/imathbox/
---
## IMathBox क्लास

गणितीय तत्व की तर्कसंगत बॉक्सिंग (पैकेजिंग) को निर्दिष्ट करता है।            
            उदाहरण के लिए, एक बॉक्स्ड ऑब्जेक्ट एक ऑपरेटर एमुलेटर के रूप में काम कर सकता है, चाहे उसके पास संरेखण बिंदु हो या न हो,            
            लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस प्रकार समूहित किया जा सकता है कि उसके भीतर लाइन ब्रेक की अनुमति न हो।            
            उदाहरण के लिए, "==" ऑपरेटर को बॉक्स्ड किया जाना चाहिए ताकि लाइन ब्रेक रोक सके।

The IMathBox type exposes the following members:

## गुण

| गुण | विवरण |
| :- | :- |
| [`base`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/base/) | मूल तर्क |
| [`operator_emulator`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/operator_emulator/) | ऑपरेटर एमुलेटर।<br/>            जब सत्य हो, तो बॉक्स और इसकी सामग्री एक ही ऑपरेटर की तरह व्यवहार करती हैं और एक ऑपरेटर की गुणधर्मों को विरासत में प्राप्त करती हैं। <br/>            इसका मतलब है, उदाहरण के लिए, कि यह वर्ण लाइन ब्रेक के बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटरों के साथ संरेखित किया जा सकता है।<br/>            ऑपरेटर एमुलेटर अक्सर तब उपयोग किए जाते हैं जब एक या अधिक ग्लाइफ़ मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='।<br/>            डिफ़ॉल्ट मान: false |
| [`no_break`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/no_break/) | कोई ब्रेक नहीं।<br/>            यह गुण वस्तु बॉक्स पर "unbreakable" गुण निर्दिष्ट करता है। जब सत्य हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता।<br/>            यह कई बाइनरी ऑपरेटरों से बनते ऑपरेटर एमुलेटर के लिए महत्वपूर्ण हो सकता है। <br/>            जब यह तत्व निर्दिष्ट नहीं किया जाता, तो बॉक्स के भीतर ब्रेक हो सकता है।<br/>            डिफ़ॉल्ट: true |
| [`differential`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/differential/) | डिफ़रेंशियल।<br/>            जब सत्य हो, बॉक्स एक डिफ़रेंशियल के रूप में कार्य करता है (जैसे, समाकल में 𝑑𝑥), और उचित <br/>            गणितीय डिफ़रेंशियल के लिए क्षैतिज स्पेसिंग प्राप्त करता है।<br/>            डिफ़ॉल्ट: false |
| [`alignment_point`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/alignment_point/) | जब सत्य हो, यह ऑपरेटर एमुलेटर एक संरेखण बिंदु के रूप में कार्य करता है; अर्थात, <br/>            अन्य समीकरणों में निर्धारित संरेखण बिंदुओं को इसके साथ संरेखित किया जा सकता है।<br/>            डिफ़ॉल्ट: false |
| [`explicit_break`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/explicit_break/) | स्पष्ट ब्रेक निर्धारित करता है कि बॉक्स ऑब्जेक्ट की शुरुआत में लाइन ब्रेक है या नहीं, <br/>            ताकि लाइन बॉक्स ऑब्जेक्ट की शुरुआत में रैप हो।<br/>            पिछली पंक्ति के गणितीय पाठ में ऑपरेटर की संख्या को निर्दिष्ट करता है जो<br/>            वर्तमान पंक्ति के गणितीय पाठ के लिए संरेखण बिंदु के रूप में उपयोग किया जाएगा<br/>            संभावित मान: 1..255<br/>            डिफ़ॉल्ट: 0 (कोई स्पष्ट ब्रेक नहीं) |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathbox/to_box/#) |  |

### संबंधित देखें
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)