---
title: TextFrame class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/textframe/
---
## TextFrame वर्ग

एक TextFrame को दर्शाता है।

TextFrame प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/hi/aspose.slides/textframe/paragraphs/) | फ़्रेम में सभी पैराग्राफ़ की सूची लौटाता है।<br/>            केवल-पढ़ने-योग्य [`IParagraphCollection`](/slides/python-net/hi/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/hi/aspose.slides/textframe/text/) | TextFrame के लिए साधारण टेक्स्ट प्राप्त करता है या सेट करता है।<br/>            पढ़ें/लिखें **str**. |
| [`text_frame_format`](/slides/python-net/hi/aspose.slides/textframe/text_frame_format/) | इस TextFrame वस्तु के लिए फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है।<br/>            केवल-पढ़ने-योग्य [`ITextFrameFormat`](/slides/python-net/hi/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/hi/aspose.slides/textframe/hyperlink_queries/) | शामिल हाइपरलिंक तक आसान पहुँच प्रदान करता है।<br/>            केवल-पढ़ने-योग्य [`IHyperlinkQueries`](/slides/python-net/hi/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/hi/aspose.slides/textframe/slide/) | TextFrame का मूल स्लाइड लौटाता है।<br/>            केवल-पढ़ने-योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hi/aspose.slides/textframe/presentation/) | TextFrame की मूल प्रस्तुति लौटाता है।<br/>            केवल-पढ़ने-योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/hi/aspose.slides/textframe/parent_shape/) | यदि मूल ऑब्जेक्ट IShape इंटरफ़ेस को लागू नहीं करता तो मूल आकार लौटाता है या None<br/>            केवल-पढ़ने-योग्य [`IShape`](/slides/python-net/hi/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/hi/aspose.slides/textframe/parent_cell/) | यदि मूल ऑब्जेक्ट ICell इंटरफ़ेस को लागू नहीं करता तो मूल सेल लौटाता है या None।<br/>            केवल-पढ़ने-योग्य [`ICell`](/slides/python-net/hi/aspose.slides/icell). |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/hi/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मेलों को हाईलाइट करता है। |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/hi/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मेलों को हाईलाइट करता है। |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/hi/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मेलों को हाईलाइट करता है। |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/hi/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मेलों को हाईलाइट करता है। |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/hi/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor) | निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मेलों को हाईलाइट करता है। |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hi/aspose.slides/textframe/join_portions_with_same_formatting/#) | सभी पैराग्राफ़ में समान फ़ॉर्मेटिंग वाले रन को मिलाता है। |
| [`split_text_by_columns(self)`](/slides/python-net/hi/aspose.slides/textframe/split_text_by_columns/#) | [`ITextFrame`](/slides/python-net/hi/aspose.slides/itextframe) के टेक्स्ट कंटेंट को स्ट्रिंग्स की श्रृंखला में विभाजित करता है, <br/>            जहाँ प्रत्येक तत्व फ्रेम के भीतर अलग टेक्स्ट कॉलम से मेल खाता है। |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/hi/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | निर्दिष्ट टेक्स्ट की सभी घटनाओं को दूसरे निर्दिष्ट टेक्स्ट से बदलता है। |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/hi/aspose.slides/textframe/replace_regex/#str-str) | नियमित अभिव्यक्ति के सभी मेलों को निर्दिष्ट स्ट्रिंग से बदलता है। |

### संबंधित देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)