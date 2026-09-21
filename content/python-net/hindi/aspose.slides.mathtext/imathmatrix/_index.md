---
title: IMathMatrix class
second_title: Aspose.Slides for Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix क्लास

मैट्रिक्स ऑब्जेक्ट को निर्दिष्ट करता है, जिसमें एक या अधिक पंक्तियों और स्तंभों में व्यवस्थित चाइल्ड तत्व होते हैं।  
यह उल्लेख करना महत्वपूर्ण है कि मैट्रिस में अंतर्निहित डिलीमीटर नहीं होते।  
मैट्रिक्स को ब्रैकेट्स में रखने के लिए आपको डिलीमीटर ऑब्जेक्ट (IMathDelimiter) का उपयोग करना चाहिए।  
मैट्रिस में अंतराल बनाने के लिए Null आर्ग्युमेंट्स का उपयोग किया जा सकता है।  

IMathMatrix प्रकार निम्न सदस्यों को उजागर करता है:

## गुण

| Property | Description |
| :- | :- |
| [`row_count`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/row_count/) | मैट्रिक्स में पंक्तियों की संख्या |
| [`column_count`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/column_count/) | मैट्रिक्स में स्तंभों की संख्या |
| [`hide_placeholders`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर छिपाएँ<br/>            Default: false |
| [`base_justification`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/base_justification/) | आसपास के टेक्स्ट के सापेक्ष लंबवत संरेखण निर्दिष्ट करता है। <br/>            संभावित मान हैं top, bottom, और center.<br/>            Default: Center |
| [`min_column_width`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/min_column_width/) | टविप्स (1/20 बिंदु) में न्यूनतम स्तंभ चौड़ाई<br/>            गैप स्पेसिंग (जिसे “Column Gap” या “Gap Width” कहा जाता है) MinColumnWidth में जोड़ी जाती है ताकि कुल मैट्रिक्स कॉलम स्पेसिंग निर्धारित हो सके<br/>            (विभिन्न स्तंभों के समान किनारों के बीच की दूरी)।<br/>            Default: 0. |
| [`column_gap_rule`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | मैट्रिक्स के स्तंभों के बीच क्षैतिज स्पेसिंग का प्रकार; <br/>            क्षैतिज स्पेसिंग इकाइयाँ ems या points (टविप्स में संग्रहीत) हो सकती हैं।<br/>            Default: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/column_gap/) | मैट्रिक्स के स्तंभों के बीच क्षैतिज स्पेसिंग का मान;<br/>            यदि ColumnGapRule को 3 ("Exactly") पर सेट किया गया है, तो इकाई को टविप्स (1/20 बिंदु) के रूप में व्याख्यायित किया जाता है<br/>            यदि ColumnGapRule को 4 ("Multiple") पर सेट किया गया है, तो इकाई को 0.5 em वृद्धि की संख्या के रूप में व्याख्यायित किया जाता है।<br/>            अन्य मामलों में अनदेखा किया जाता है।<br/>            Default: 0 |
| [`row_gap_rule`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का प्रकार; <br/>            लंबवत स्पेसिंग इकाइयाँ लाइन्स या पॉइंट्स (टविप्स में संग्रहीत) हो सकती हैं।<br/>            Default: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/row_gap/) | मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का मान;<br/>            यदि RowGapRule को 3 ("Exactly") पर सेट किया गया है, तो इकाई को टविप्स (1/20 बिंदु) के रूप में व्याख्यायित किया जाता है<br/>            यदि RowGapRule को 4 ("Multiple") पर सेट किया गया है, तो इकाई को आधी लाइनों के रूप में व्याख्यायित किया जाता है।<br/>            Default: 0 |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | निर्दिष्ट कॉलम का क्षैतिज संरेखण प्राप्त करें |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | निर्दिष्ट कॉलम का क्षैतिज संरेखण सेट करें |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | निर्दिष्ट कॉलमों का क्षैतिज संरेखण सेट करें |
| [`insert_row_before(self, row_index)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | निर्दिष्ट पंक्ति से पहले नई पंक्ति सम्मिलित करें<br/>            प्रारम्भ में नई पंक्ति के सभी तत्व None होते हैं। |
| [`insert_row_after(self, row_index)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | निर्दिष्ट पंक्ति के बाद नई पंक्ति सम्मिलित करें<br/>            प्रारम्भ में नई पंक्ति के सभी तत्व None होते हैं। |
| [`delete_row(self, row_index)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/delete_row/#int) | निर्दिष्ट पंक्ति को हटाता है |
| [`insert_column_before(self, column_index)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | निर्दिष्ट कॉलम से पहले नई कॉलम सम्मिलित करें<br/>            प्रारम्भ में नई कॉलम के सभी तत्व None होते हैं। |
| [`insert_column_after(self, column_index)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | निर्दिष्ट कॉलम के बाद नई कॉलम सम्मिलित करें<br/>            प्रारम्भ में नई कॉलम के सभी तत्व None होते हैं। |
| [`delete_column(self, column_index)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/delete_column/#int) | निर्दिष्ट कॉलम को हटाता है |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### देखें भी
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)