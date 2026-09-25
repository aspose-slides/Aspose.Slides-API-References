---
title: Rectangle class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: एक आयत के स्थान और आकार को दर्शाने वाले चार पूर्णांकों का सेट संग्रहीत करता है।
type: docs
url: /hi/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Rectangle क्लास

चार पूर्णांक का सेट संग्रहीत करता है जो आयत के स्थान और आकार को दर्शाते हैं। .NET `System.Drawing.Rectangle` के साथ संगत।

Rectangle प्रकार निम्नलिखित सदस्य उजागर करता है:

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/hi/aspose.slides/rectangle/__init__/#int-int-int-int) | निर्दिष्ट स्थान और आकार के साथ एक आयत बनाता है। Float मानों को पूर्णांकों में ट्रंकेट किया जाता है। |

## गुण

| गुण | विवरण |
| :- | :- |
| [`x`](/slides/python-net/hi/aspose.slides/rectangle/x/) | इस आयत के ऊपरी-बाएँ कोने का x-निर्देशांक प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`y`](/slides/python-net/hi/aspose.slides/rectangle/y/) | इस आयत के ऊपरी-बाएँ कोने का y-निर्देशांक प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`width`](/slides/python-net/hi/aspose.slides/rectangle/width/) | इस आयत की चौड़ाई प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`height`](/slides/python-net/hi/aspose.slides/rectangle/height/) | इस आयत की ऊँचाई प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`left`](/slides/python-net/hi/aspose.slides/rectangle/left/) | इस आयत के बाएँ किनारे का x-निर्देशांक प्राप्त करता है। `x` के बराबर।<br/>            केवल-पढ़ने योग्य **int**. |
| [`top`](/slides/python-net/hi/aspose.slides/rectangle/top/) | इस आयत के शीर्ष किनारे का y-निर्देशांक प्राप्त करता है। `y` के बराबर।<br/>            केवल-पढ़ने योग्य **int**. |
| [`right`](/slides/python-net/hi/aspose.slides/rectangle/right/) | इस आयत के `x` और `width` के योग वाले x-निर्देशांक को प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`bottom`](/slides/python-net/hi/aspose.slides/rectangle/bottom/) | इस आयत के `y` और `height` के योग वाले y-निर्देशांक को प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`is_empty`](/slides/python-net/hi/aspose.slides/rectangle/is_empty/) | निर्दिष्ट करता है कि इस आयत की सभी संख्यात्मक गुण शून्य हैं या नहीं।<br/>            केवल-पढ़ने योग्य **bool**. |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/hi/aspose.slides/rectangle/contains/#int-int) | निर्धारित करता है कि निर्दिष्ट बिंदु इस आयत के भीतर समाहित है या नहीं। |
| [`contains(self, point)`](/slides/python-net/hi/aspose.slides/rectangle/contains/#point) | निर्धारित करता है कि निर्दिष्ट बिंदु इस आयत के भीतर समाहित है या नहीं। |
| [`contains(self, rect)`](/slides/python-net/hi/aspose.slides/rectangle/contains/#rectangle) | निर्धारित करता है कि `rect` द्वारा प्रतिनिधित्व किया गया आयताकार क्षेत्र पूरी तरह से इस आयत के भीतर समाहित है या नहीं। |

### टिप्पणियाँ

आयतों की तुलना उनके स्थान और आकार से `==` द्वारा की जाती है और उन्हें शब्दकोश कुंजियों या सेट सदस्यों के रूप में उपयोग किया जा सकता है।

### संबंधित देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)