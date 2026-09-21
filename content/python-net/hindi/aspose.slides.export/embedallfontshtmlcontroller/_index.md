---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController क्लास

फ़ॉर्मेटिंग कंट्रोलर क्लास जिसका उपयोग सभी प्रस्तुति फ़ॉन्ट को WOFF फ़ॉर्मेट में एम्बेड करने के लिए किया जाता है।

EmbedAllFontsHtmlController टाइप निम्नलिखित सदस्यों को उजागर करता है:

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | नया उदाहरण बनाता है |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/hi/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | नया उदाहरण बनाता है |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/hi/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | HTML दस्तावेज़ हेडर लिखने के लिए कॉल किया जाता है। प्रत्येक प्रस्तुति रूपांतरण में एक बार कॉल किया जाता है। |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/hi/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | HTML दस्तावेज़ फुटर लिखने के लिए कॉल किया जाता है। प्रत्येक प्रस्तुति रूपांतरण में एक बार कॉल किया जाता है। |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/hi/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | HTML स्लाइड हेडर लिखने के लिए कॉल किया जाता है। प्रत्येक स्लाइड में एक बार कॉल किया जाता है। |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/hi/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | HTML स्लाइड फुटर लिखने के लिए कॉल किया जाता है। प्रत्येक स्लाइड में एक बार कॉल किया जाता है। |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/hi/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | शेप के रेंडरिंग से पहले कॉल किया जाता है। प्रत्येक शेप के लिए एक बार कॉल किया जाता है। यदि यह फ़ंक्शन जेनरेटर में कुछ लिखता है, तो वर्तमान स्लाइड छवि निर्माण समाप्त हो जाएगा, जोड़ी गया HTML फ्रैगमेंट डाल दिया जाएगा और नई छवि पूर्ववर्ती के ऊपर शुरू होगी। |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/hi/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | शेप के रेंडरिंग से पहले कॉल किया जाता है। प्रत्येक शेप के लिए एक बार कॉल किया जाता है। यदि यह फ़ंक्शन जेनरेटर में कुछ लिखता है, तो वर्तमान स्लाइड छवि निर्माण समाप्त हो जाएगा, जोड़ी गया HTML फ्रैगमेंट डाल दिया जाएगा और नई छवि पूर्ववर्ती के ऊपर शुरू होगी। |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/hi/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | [`Presentation`](/slides/python-net/hi/aspose.slides/presentation) में मौजूद सभी फ़ॉन्ट लिखें। |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/hi/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | डेटा को base64 के रूप में सीधे HTML दस्तावेज़ में लिखता है। |

### संबंधित देखें
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)