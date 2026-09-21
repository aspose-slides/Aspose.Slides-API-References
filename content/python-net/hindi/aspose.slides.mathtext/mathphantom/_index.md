---
title: MathPhantom class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathphantom/
---
## MathPhantom क्लास

एक भूतिया गणितीय वस्तु (<m:phant>) का प्रतिनिधित्व करता है जो अपने बाल घटक के लेआउट को प्रभावित करता है बिना उसे अनिवार्य रूप से प्रदर्शित किए। एक भूतिया अपनी आधार अभिव्यक्ति को छुपा सकता है जबकि इसकी चौड़ाई, ऊँचाई, या गहराई को बनाए रखता है ताकि समीकरणों को संरेखित किया जा सके या स्थान आरक्षित किया जा सके। दृश्यता और ज्यामिति व्यवहार को Show, ZeroWid, ZeroAsc, ZeroDesc, और Transp जैसी प्रॉपर्टीज़ द्वारा नियंत्रित किया जाता है।

**विरासत:**[`MathPhantom`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)

MathPhantom प्रकार निम्न सदस्य प्रकट करता है:

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | [`MathPhantom`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom) क्लास का नया उदाहरण प्रारंभ करता है <br/>            निर्दिष्ट आधार गणितीय तत्व का उपयोग करके। |

## गुण

| गुण | विवरण |
| :- | :- |
| [`base`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/base/) | आधार तर्क |
| [`show`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/show/) | आधार तत्व प्रदर्शित है या नहीं, इसे दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [`zero_width`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/zero_width/) | आधार तत्व की चौड़ाई को शून्य माना जाना चाहिए या नहीं, इसे दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [`zero_asc`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/zero_asc/) | आधार तत्व की आरोह (बीसलाइन के ऊपर की ऊँचाई) को शून्य माना जाना चाहिए या नहीं, इसे दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [`zero_desc`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/zero_desc/) | आधार तत्व की अवरोह (बीसलाइन के नीचे की गहराई) को शून्य माना जाना चाहिए या नहीं, इसे दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [`transp`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/transp/) | वर्ग-आधारित स्पेसिंग नियमों के लिए भूतिया पारदर्शी है या नहीं, इसे दर्शाने वाला मान प्राप्त करता है या सेट करता है। |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/join/#imathelement) | गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/join/#str) | गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/divide/#imathelement) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/divide/#str) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | निर्दिष्ट प्रकार की भिन्न को इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | निर्दिष्ट प्रकार की भिन्न को इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/enclose/#) | गणितीय तत्व को कोष्ठक में लपेटता है |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/enclose/#char-char) | गणितीय तत्व को निर्दिष्ट अक्षरों, जैसे कोष्ठक या अन्य संकेतों, में फ्रेमिंग के रूप में लपेटता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/function/#imathelement) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का एक फ़ंक्शन लेता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/function/#str) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का एक फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | इस उदाहरण को तर्क के रूप में उपयोग करके और निर्दिष्ट अतिरिक्त तर्क के साथ निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | इस उदाहरण को तर्क के रूप में उपयोग करके और निर्दिष्ट अतिरिक्त तर्क के साथ निर्दिष्ट फ़ंक्शन लेता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | सबस्क्रिप्ट बनाता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/set_subscript/#str) | सबस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | सुपरस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/set_superscript/#str) | सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/radical/#imathelement) | निर्दिष्ट तर्क से दिए गए घात का गणितीय मूल निर्दिष्ट करता है। |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/radical/#str) | निर्दिष्ट तर्क से दिए गए घात का गणितीय मूल निर्दिष्ट करता है। |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | ऊपरी सीमा लेता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | ऊपरी सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | निचली सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | निचली सीमा लेता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | एक N-ary ऑपरेटर बनाता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | एक N-ary ऑपरेटर बनाता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | समाकल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | समाकल लेता है |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | सीमा बिना समाकल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | समाकल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | समाकल लेता है |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/group/#) | नीचे की कर्ली ब्रेस का उपयोग करके इस तत्व को समूह में रखता है |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | नीचे की कर्ली ब्रेस या अन्य समूह संकेत का उपयोग करके इस तत्व को समूह में रखता है |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/to_border_box/#) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/to_math_array/#) | वर्टिकल एरे में रखता है |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/accent/#char) | एक एक्सेंट मार्क सेट करता है (इस तत्व के ऊपर का अक्षर) |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/overbar/#) | इस तत्व के ऊपर एक बार सेट करता है |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/underbar/#) | इस तत्व के नीचे एक बार सेट करता है |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/to_box/#) | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है <br/>            जिसका उपयोग समीकरण या गणितीय पाठ के अन्य उदाहरण के घटकों को समूहित करने के लिए किया जाता है।<br/>            एक बॉक्स्ड वस्तु (उदाहरण के लिए) एक ऑपरेटर अनुकरणकर्ता के रूप में कार्य कर सकती है, संरेखण बिंदु के साथ या बिना, <br/>            लाइन ब्रेक बिंदु के रूप में, या ऐसे समूहित हो सकती है जिससे भीतर लाइन ब्रेक की अनुमति न हो। |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom/get_children/#) | संतान तत्व प्राप्त करें |

### देखें भी
* क्लास [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)
* क्लास [`MathPhantom`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)