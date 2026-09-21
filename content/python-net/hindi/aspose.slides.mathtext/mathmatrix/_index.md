---
title: MathMatrix class
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix क्लास

एक या अधिक पंक्तियों और स्तंभों में व्यवस्थित चाइल्ड एलिमेंट्स वाले मैट्रिक्स ऑब्जेक्ट को निर्दिष्ट करता है।  
यह ध्यान देना महत्वपूर्ण है कि मैट्रिक्स के पास अंतर्निहित डेलीमीटर नहीं होते हैं।  
मैट्रिक्स को कोष्ठकों में रखने के लिए आपको डेलीमीटर ऑब्जेक्ट (IMathDelimiter) का उपयोग करना चाहिए।  
मैट्रिक्स में गैप बनाने के लिए Null तर्कों का उपयोग किया जा सकता है।

**विरासत:**[`MathMatrix`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)

MathMatrix प्रकार निम्नलिखित सदस्य प्रदर्शित करता है।

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | MathMatrix क्लास का नया इंस्टेंस आरंभ करता है। |

## गुण

| गुण | विवरण |
| :- | :- |
| [`row_count`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/row_count/) | मैट्रिक्स में पंक्तियों की संख्या |
| [`column_count`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/column_count/) | मैट्रिक्स में स्तंभों की संख्या |
| [`hide_placeholders`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | खाली मैट्रिक्स एलिमेंट्स के लिए प्लेसहोल्डर्स को छिपाएँ<br/>डिफ़ॉल्ट: false |
| [`base_justification`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/base_justification/) | आसपास के टेक्स्ट के सापेक्ष ऊर्ध्वाधर जस्टिफिकेशन निर्दिष्ट करता है।<br/>संभव मान हैं top, bottom, और center।<br/>डिफ़ॉल्ट: Center |
| [`min_column_width`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/min_column_width/) | ट्विप्स में न्यूनतम कॉलम चौड़ाई (1/20 बिंदु)<br/>गैप स्पेसिंग (जिसे “Column Gap” या “Gap Width” भी कहा जाता है) MinColumnWidth में जोड़ी जाती है कुल मैट्रिक्स कॉलम स्पेसिंग निर्धारित करने के लिए<br/>(विभिन्न कॉलमों के समान किनारों के बीच का अंतर)।<br/>डिफ़ॉल्ट: 0. |
| [`column_gap_rule`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | मैट्रिक्स के कॉलमों के बीच क्षैतिज स्पेसिंग का प्रकार;<br/>क्षैतिज स्पेसिंग इकाइयाँ ems या पॉइंट्स (ट्विप्स में संग्रहित) हो सकती हैं।<br/>डिफ़ॉल्ट: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/column_gap/) | मैट्रिक्स के कॉलमों के बीच क्षैतिज स्पेसिंग का मान;<br/>यदि ColumnGapRule को 3 (“Exactly”) पर सेट किया गया है, तो इकाई को ट्विप्स (1/20 बिंदु) के रूप में व्याख्यायित किया जाता है<br/>यदि ColumnGapRule को 4 (“Multiple”) पर सेट किया गया है, तो इकाई को 0.5 em वृद्धि की संख्या के रूप में व्याख्यायित किया जाता है।<br/>अन्य मामलों में अनदेखा किया जाता है।<br/>डिफ़ॉल्ट: 0 |
| [`row_gap_rule`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का प्रकार;<br/>ऊर्ध्वाधर स्पेसिंग इकाइयाँ लाइन्स या पॉइंट्स (ट्विप्स में संग्रहित) हो सकती हैं।<br/>डिफ़ॉल्ट: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/row_gap/) | मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का मान;<br/>यदि RowGapRule को 3 (“Exactly”) पर सेट किया गया है, तो इकाई को ट्विप्स (1/20 बिंदु) के रूप में व्याख्यायित किया जाता है<br/>यदि RowGapRule को 4 (“Multiple”) पर सेट किया गया है, तो इकाई को आधी लाइन्स के रूप में व्याख्यायित किया जाता है।<br/>डिफ़ॉल्ट: 0 |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/join/#imathelement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/join/#str) | एक गणितीय टेक्स्ट को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | इस न्यूमेरेटर और निर्दिष्ट डिनॉमिनेटर के साथ एक फ्रैक्शन बनाता है |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/divide/#str) | इस न्यूमेरेटर और निर्दिष्ट डिनॉमिनेटर के साथ एक फ्रैक्शन बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | निर्दिष्ट प्रकार का फ्रैक्शन इस न्यूमेरेटर और निर्दिष्ट डिनॉमिनेटर के साथ बनाता है |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | निर्दिष्ट प्रकार का फ्रैक्शन इस न्यूमेरेटर और निर्दिष्ट डिनॉमिनेटर के साथ बनाता है |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/enclose/#) | गणितीय तत्व को कोष्ठक में घेरता है |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | गणितीय तत्व को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षरों में फ्रेमिंग के रूप में घेरता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/function/#imathelement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/function/#str) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | इस इंस्टेंस को तर्क के रूप में उपयोग करके और अतिरिक्त तर्क को निर्दिष्ट करके फ़ंक्शन लेता है |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | इस इंस्टेंस को तर्क के रूप में उपयोग करके और अतिरिक्त तर्क को निर्दिष्ट करके फ़ंक्शन लेता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | सबस्क्रिप्ट बनाता है |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | सबस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | सुपरस्क्रिप्ट बनाता है |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | निर्दिष्ट तर्क से दी गई डिग्री का गणितीय मूल निर्दिष्ट करता है। |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/radical/#str) | निर्दिष्ट तर्क से दी गई डिग्री का गणितीय मूल निर्दिष्ट करता है। |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | ऊपरी सीमा लेता है |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | ऊपरी सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | नीची सीमा लेता है |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | नीची सीमा लेता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | एक N-ary ऑपरेटर बनाता है |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | एक N-ary ऑपरेटर बनाता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | इंटीग्रल लेता है |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | सीमा के बिना इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | इंटीग्रल लेता है |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | इंटीग्रल लेता है |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/group/#) | नीचे के कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | नीचे के कर्ली ब्रैकेट या अन्य ग्रुपिंग कैरक्टर का उपयोग करके इस तत्व को एक समूह में रखता है |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/to_border_box/#) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/to_math_array/#) | एक ऊर्ध्वाधर एरे में रखता है |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/accent/#char) | एक एक्सेंट मार्क सेट करता है (इस तत्व के शीर्ष पर एक अक्षर) |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/overbar/#) | इस तत्व के शीर्ष पर एक बार सेट करता है |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/underbar/#) | इस तत्व के नीचे एक बार सेट करता है |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/to_box/#) | इस तत्व को एक गैर-दृश्यमान बॉक्स (तार्किक समूह) में रखता है <br/>जिसका उपयोग समीकरण के घटकों या गणितीय टेक्स्ट की अन्य इकाइयों को समूहित करने के लिए किया जाता है।<br/>एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) संरेखण बिंदु के साथ या बिना ऑपरेटर एम्यूलेटर के रूप में कार्य कर सकता है, <br/>लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या समूहित हो सकता है ताकि भीतर लाइन ब्रेक की अनुमति न हो। |
| [`get_column_alignment(self, column_index)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | निर्दिष्ट कॉलम की क्षैतिज संरेखण प्राप्त करें |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | निर्दिष्ट कॉलम की क्षैतिज संरेखण सेट करें |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | निर्दिष्ट कॉलमों की क्षैतिज संरेखण सेट करें |
| [`insert_row_before(self, row_index)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | निर्दिष्ट पंक्ति से पहले एक नई पंक्ति डालें<br/>शुरुआत में नई पंक्ति के सभी तत्व None होते हैं। |
| [`insert_row_after(self, row_index)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | निर्दिष्ट पंक्ति के बाद एक नई पंक्ति डालें<br/>शुरुआत में नई पंक्ति के सभी तत्व None होते हैं। |
| [`delete_row(self, row_index)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/delete_row/#int) | निर्दिष्ट पंक्ति को हटाता है |
| [`insert_column_before(self, column_index)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | निर्दिष्ट कॉलम से पहले एक नया कॉलम डालें<br/>शुरुआत में नए कॉलम के सभी तत्व None होते हैं। |
| [`insert_column_after(self, column_index)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | निर्दिष्ट कॉलम के बाद एक नया कॉलम डालें<br/>शुरुआत में नए कॉलम के सभी तत्व None होते हैं। |
| [`delete_column(self, column_index)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/delete_column/#int) | निर्दिष्ट कॉलम को हटाता है |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix/get_children/#) | चाइल्ड एलिमेंट्स प्राप्त करें |

### संबंधित देखें
* क्लास [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)
* क्लास [`MathMatrix`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)