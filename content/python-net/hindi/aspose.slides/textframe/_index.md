---
title: TextFrame class
second_title: Aspose.Slides के लिए Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/textframe/
---
## TextFrame क्लास

एक TextFrame को दर्शाता है।

TextFrame प्रकार निम्नलिखित सदस्य प्रदान करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`paragraphs`](/slides/python-net/hi/aspose.slides/textframe/paragraphs/) | फ़्रेम में सभी पैराग्राफ़ की सूची लौटाता है।<br/>            Read-only [`IParagraphCollection`](/slides/python-net/hi/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/hi/aspose.slides/textframe/text/) | TextFrame के लिए साधारण टेक्स्ट प्राप्त करता है या सेट करता है।<br/>            Read/write **str**. |
| [`text_frame_format`](/slides/python-net/hi/aspose.slides/textframe/text_frame_format/) | इस TextFrame वस्तु के लिए फॉर्मेटिंग ऑब्जेक्ट लौटाता है।<br/>            Read-only [`ITextFrameFormat`](/slides/python-net/hi/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/hi/aspose.slides/textframe/hyperlink_queries/) | निहित हाइपरलिंक तक आसान पहुँच प्रदान करता है।<br/>            Read-only [`IHyperlinkQueries`](/slides/python-net/hi/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/hi/aspose.slides/textframe/slide/) | TextFrame की पैरेंट स्लाइड लौटाता है।<br/>            Read-only [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hi/aspose.slides/textframe/presentation/) | TextFrame की पैरेंट प्रस्तुति लौटाता है।<br/>            Read-only [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/hi/aspose.slides/textframe/parent_shape/) | पैरेंट shape लौटाता है या None यदि पैरेंट ऑब्जेक्ट IShape इंटरफ़ेस को लागू नहीं करता<br/>            Read-only [`IShape`](/slides/python-net/hi/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/hi/aspose.slides/textframe/parent_cell/) | पैरेंट सेल लौटाता है या None यदि पैरेंट ऑब्जेक्ट ICell इंटरफ़ेस को लागू नहीं करता।<br/>            Read-only [`ICell`](/slides/python-net/hi/aspose.slides/icell). |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/hi/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मिलान को हाइलाइट करता है। |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/hi/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मिलान को हाइलाइट करता है। |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/hi/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मिलान को हाइलाइट करता है। |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/hi/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलान को हाइलाइट करता है। |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/hi/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलान को हाइलाइट करता है। |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hi/aspose.slides/textframe/join_portions_with_same_formatting/#) | सभी पैराग्राफ़ में समान फॉर्मेटिंग वाले रन को जोड़ता है। |
| [`split_text_by_columns(self)`](/slides/python-net/hi/aspose.slides/textframe/split_text_by_columns/#) | [`ITextFrame`](/slides/python-net/hi/aspose.slides/itextframe) की टेक्स्ट सामग्री को स्ट्रिंग्स की एक array में विभाजित करता है,  <br/>            जहाँ प्रत्येक तत्व फ्रेम के भीतर एक अलग टेक्स्ट कॉलम से संबंधित होता है। |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/hi/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | निर्दिष्ट टेक्स्ट की सभी घटनाओं को दूसरे निर्दिष्ट टेक्स्ट से बदलता है। |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/hi/aspose.slides/textframe/replace_regex/#str-str) | नियमित अभिव्यक्ति के सभी मिलान को निर्दिष्ट स्ट्रिंग से बदलता है। |

### संबंधित देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)