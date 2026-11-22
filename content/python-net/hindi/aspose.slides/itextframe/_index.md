---
title: ITextFrame class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/itextframe/
---
## ITextFrame क्लास

एक TextFrame का प्रतिनिधित्व करता है।

ITextFrame प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`paragraphs`](/slides/python-net/hi/aspose.slides/itextframe/paragraphs/) | फ़्रेम में सभी पैराग्राफ़ की सूची लौटाता है।<br/>            केवल-पढ़ने योग्य [`IParagraphCollection`](/slides/python-net/hi/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/hi/aspose.slides/itextframe/text/) | TextFrame के लिए साधारण टेक्स्ट प्राप्त या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`text_frame_format`](/slides/python-net/hi/aspose.slides/itextframe/text_frame_format/) | इस TextFrame ऑब्जेक्ट के लिए फॉर्मेटिंग ऑब्जेक्ट लौटाता है।<br/>            केवल-पढ़ने योग्य [`ITextFrameFormat`](/slides/python-net/hi/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/hi/aspose.slides/itextframe/hyperlink_queries/) | समाहित हाइपरलिंक तक आसान पहुँच प्रदान करता है।<br/>            केवल-पढ़ने योग्य [`IHyperlinkQueries`](/slides/python-net/hi/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/hi/aspose.slides/itextframe/parent_shape/) | पैरेंट शेप लौटाता है या None यदि पैरेंट ऑब्जेक्ट IShape इंटरफ़ेस लागू नहीं करता है।<br/>            केवल-पढ़ने योग्य [`IShape`](/slides/python-net/hi/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/hi/aspose.slides/itextframe/parent_cell/) | पैरेंट सेल लौटाता है या None यदि पैरेंट ऑब्जेक्ट ICell इंटरफ़ेस लागू नहीं करता है।<br/>            केवल-पढ़ने योग्य [`ICell`](/slides/python-net/hi/aspose.slides/icell). |
| [`slide`](/slides/python-net/hi/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides/itextframe/presentation/) |  |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/hi/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मैचों को हाइलाइट करता है। |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/hi/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मैचों को हाइलाइट करता है। |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/hi/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मैचों को हाइलाइट करता है। |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/hi/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मैचों को हाइलाइट करता है। |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/hi/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मैचों को हाइलाइट करता है। |
| [`get_text_rect(self)`](/slides/python-net/hi/aspose.slides/itextframe/get_text_rect/#) | पैरेंट शेप की ज्यामिति द्वारा परिभाषित टेक्स्ट आयत प्राप्त करता है। |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hi/aspose.slides/itextframe/join_portions_with_same_formatting/#) | सभी पैराग्राफ़ में समान स्वरूपण वाले रन को जोड़ता है। |
| [`split_text_by_columns(self)`](/slides/python-net/hi/aspose.slides/itextframe/split_text_by_columns/#) | [`ITextFrame`](/slides/python-net/hi/aspose.slides/itextframe) के टेक्स्ट कंटेंट को स्ट्रिंग्स की एरे में विभाजित करता है, <br/>            जहाँ प्रत्येक तत्व फ्रेम के भीतर एक अलग टेक्स्ट कॉलम से मेल खाता है। |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/hi/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | निर्दिष्ट टेक्स्ट की सभी घटनाओं को दूसरे निर्दिष्ट टेक्स्ट से बदलता है। |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/hi/aspose.slides/itextframe/replace_regex/#str-str) | नियमित अभिव्यक्ति के सभी मैचों को निर्दिष्ट स्ट्रिंग से बदलता है। |


### देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)