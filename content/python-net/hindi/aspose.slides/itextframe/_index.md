---
title: ITextFrame class
second_title: Aspose.Slides for Python के लिए .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides/itextframe/
---
## ITextFrame वर्ग

एक TextFrame का प्रतिनिधित्व करता है।

ITextFrame प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/hi/aspose.slides/itextframe/paragraphs/) | फ़्रेम में सभी पैराग्राफ़ की सूची लौटाता है।<br/>            केवल-पढ़ने योग्य [`IParagraphCollection`](/slides/python-net/hi/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/hi/aspose.slides/itextframe/text/) | TextFrame के लिए साधारण पाठ को प्राप्त करता है या सेट करता है।<br/>            पढ़ें/लिखें **str**. |
| [`text_frame_format`](/slides/python-net/hi/aspose.slides/itextframe/text_frame_format/) | इस TextFrame वस्तु के लिए स्वरूपण ऑब्जेक्ट लौटाता है।<br/>            केवल-पढ़ने योग्य [`ITextFrameFormat`](/slides/python-net/hi/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/hi/aspose.slides/itextframe/hyperlink_queries/) | शामिल हाइपरलिंक तक आसान पहुंच प्रदान करता है।<br/>            केवल-पढ़ने योग्य [`IHyperlinkQueries`](/slides/python-net/hi/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/hi/aspose.slides/itextframe/parent_shape/) | यदि पेरेंट ऑब्जेक्ट IShape इंटरफ़ेस को लागू नहीं करता है तो पैरेंट आकार या None लौटाता है।<br/>            केवल-पढ़ने योग्य [`IShape`](/slides/python-net/hi/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/hi/aspose.slides/itextframe/parent_cell/) | यदि पेरेंट ऑब्जेक्ट ICell इंटरफ़ेस को लागू नहीं करता है तो पैरेंट सेल या None लौटाता है।<br/>            केवल-पढ़ने योग्य [`ICell`](/slides/python-net/hi/aspose.slides/icell). |
| [`slide`](/slides/python-net/hi/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides/itextframe/presentation/) |  |

## विधियाँ

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/hi/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor) | निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को उजागर करता है। |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/hi/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को उजागर करता है। |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/hi/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को उजागर करता है। |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/hi/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor) | निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलान को उजागर करता है। |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/hi/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलान को उजागर करता है। |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hi/aspose.slides/itextframe/join_portions_with_same_formatting/#) | सभी पैराग्राफ़ में समान स्वरूपण वाले रन को जोड़ता है। |
| [`split_text_by_columns(self)`](/slides/python-net/hi/aspose.slides/itextframe/split_text_by_columns/#) | [`ITextFrame`](/slides/python-net/hi/aspose.slides/itextframe) की टेक्स्ट सामग्री को स्ट्रिंग्स की एक एरे में विभाजित करता है,<br/>            जहाँ प्रत्येक तत्व फ्रेम के भीतर अलग टेक्स्ट कॉलम से मेल खाता है। |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/hi/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | निर्दिष्ट टेक्स्ट की सभी घटनाओं को अन्य निर्दिष्ट टेक्स्ट से बदलता है। |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/hi/aspose.slides/itextframe/replace_regex/#str-str) | नियमित अभिव्यक्ति के सभी मिलान को निर्दिष्ट स्ट्रिंग से बदलता है। |


### देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)