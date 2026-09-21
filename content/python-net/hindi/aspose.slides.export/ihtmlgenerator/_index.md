---
title: IHtmlGenerator class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator क्लास

HTML जेनरेटर।

The IHtmlGenerator type exposes the following members:

## प्रॉपर्टीज़

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`slide_image_size`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/slide_image_size/) | Returns slide image size.<br/>            केवल-पढ़ने-योग्य **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | स्लाइड इमेज आकार निर्दिष्ट करने वाली इकाई लौटाता है।<br/>            केवल-पढ़ने-योग्य [`SvgCoordinateUnit`](/slides/python-net/hi/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | स्लाइड इमेज आकार निर्दिष्ट करने वाली इकाई का CSS कोड लौटाता है।<br/>            केवल-पढ़ने-योग्य **str**. |
| [`previous_slide_index`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | पहले रेंडर किए गए स्लाइड का सूचकांक या -1 यदि पहला स्लाइड रेंडर हो रहा है, लौटाता है।<br/>            केवल-पढ़ने-योग्य **int**. |
| [`slide_index`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/slide_index/) | वर्तमान में रेंडर हो रहे स्लाइड का सूचकांक लौटाता है।<br/>            केवल-पढ़ने-योग्य **int**. |
| [`next_slide_index`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/next_slide_index/) | वर्तमान स्लाइड के बाद रेंडर किए जाने वाले स्लाइड का सूचकांक या -1 यदि वर्तमान में अंतिम स्लाइड रेंडर हो रही है, लौटाता है।<br/>            केवल-पढ़ने-योग्य **int**. |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/add_html/#str) | फ़ॉर्मेट किया गया HTML टेक्स्ट जोड़ता है। |
| [`add_html(self, html)`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | फ़ॉर्मेट किया गया HTML टेक्स्ट जोड़ता है। |
| [`add_html(self, html, start_index, length)`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | फ़ॉर्मेट किया गया HTML टेक्स्ट जोड़ता है। |
| [`add_text(self, text)`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/add_text/#str) | HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष अक्षरों को HTML एंटिटीज़ से बदलता है।<br/>            लाइन ब्रेकेज और सफ़ैद स्थान नहीं बदले जाते। |
| [`add_text(self, text)`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष अक्षरों को HTML एंटिटीज़ से बदलता है।<br/>            लाइन ब्रेकेज और सफ़ैद स्थान नहीं बदले जाते। |
| [`add_text(self, text, start_index, length)`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष अक्षरों को HTML एंटिटीज़ से बदलता है।<br/>            लाइन ब्रेकेज और सफ़ैद स्थान नहीं बदले जाते। |
| [`add_attribute_value(self, value)`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | एट्रिब्यूट वैल्यू को क्वोट करता है और इसे HTML फ़ाइल में जोड़ता है। |
| [`add_attribute_value(self, value)`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | एट्रिब्यूट वैल्यू को क्वोट करता है और इसे HTML फ़ाइल में जोड़ता है। |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | एट्रिब्यूट वैल्यू को क्वोट करता है और इसे HTML फ़ाइल में जोड़ता है। |

### देखें
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)