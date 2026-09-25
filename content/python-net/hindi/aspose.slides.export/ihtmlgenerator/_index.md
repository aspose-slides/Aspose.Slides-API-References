---
title: IHtmlGenerator class
second_title: Aspose.Slides Python के लिए .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator क्लास

Html जनरेटर।

The IHtmlGenerator type exposes the following members:

## गुण

| गुण | विवरण |
| :- | :- |
| [`slide_image_size`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/slide_image_size/) | स्लाइड छवि आकार वापस करता है।<br/>केवल-पढ़ने योग्य [`SizeF`](/slides/python-net/hi/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | स्लाइड छवि आकार निर्दिष्ट करने वाली इकाई वापस करता है।<br/>केवल-पढ़ने योग्य [`SvgCoordinateUnit`](/slides/python-net/hi/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | स्लाइड छवि आकार निर्दिष्ट करने वाली इकाई का CSS कोड वापस करता है।<br/>केवल-पढ़ने योग्य **str**. |
| [`previous_slide_index`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | पहले रेंडर किए गए स्लाइड का इंडेक्स वापस करता है या -1 यदि पहला स्लाइड रेंडर किया जा रहा है।<br/>केवल-पढ़ने योग्य **int**. |
| [`slide_index`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/slide_index/) | वर्तमान में रेंडर हो रहे स्लाइड का इंडेक्स वापस करता है।<br/>केवल-पढ़ने योग्य **int**. |
| [`next_slide_index`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/next_slide_index/) | उस स्लाइड का इंडेक्स वापस करता है, जो वर्तमान स्लाइड के बाद रेंडर होगी या -1 यदि वर्तमान में आखिरी स्लाइड रेंडर हो रहा है।<br/>केवल-पढ़ने योग्य **int**. |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/add_html/#str) | फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है। |
| [`add_html(self, html)`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है। |
| [`add_html(self, html, start_index, length)`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है। |
| [`add_text(self, text)`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/add_text/#str) | HTML फ़ाइलों में सादा टेक्स्ट जोड़ता है, विशेष अक्षरों को HTML एंटिटी से बदलते हुए।<br/>लाइन ब्रेक और व्हाइटस्पेस बदले नहीं जाते। |
| [`add_text(self, text)`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | HTML फ़ाइलों में सादा टेक्स्ट जोड़ता है, विशेष अक्षरों को HTML एंटिटी से बदलते हुए।<br/>लाइन ब्रेक और व्हाइटस्पेस बदले नहीं जाते। |
| [`add_text(self, text, start_index, length)`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | HTML फ़ाइलों में सादा टेक्स्ट जोड़ता है, विशेष अक्षरों को HTML एंटिटी से बदलते हुए।<br/>लाइन ब्रेक और व्हाइटस्पेस बदले नहीं जाते। |
| [`add_attribute_value(self, value)`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | गुणधर्म मान को उद्धरण में लेता है और इसे HTML फ़ाइल में जोड़ता है। |
| [`add_attribute_value(self, value)`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | गुणधर्म मान को उद्धरण में लेता है और इसे HTML फ़ाइल में जोड़ता है। |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/hi/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | गुणधर्म मान को उद्धरण में लेता है और इसे HTML फ़ाइल में जोड़ता है। |


### देखें भी
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)