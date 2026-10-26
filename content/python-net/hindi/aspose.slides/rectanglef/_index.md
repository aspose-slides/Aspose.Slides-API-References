---
title: RectangleF class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: एक आयत के स्थान और आकार को दर्शाने वाले चार फ्लोटिंग-पॉइंट संख्याओं का सेट संग्रहीत करता है।
type: docs
url: /hi/aspose.slides/rectanglef/
net_type: System.Drawing.RectangleF
---
## RectangleF क्लास

Stores a set of four floating-point numbers that represent the location and size of a rectangle. Compatible with .NET `System.Drawing.RectangleF`.

**Inheritance:**[`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) → [`Rectangle`](/slides/python-net/hi/aspose.slides/rectangle)

The RectangleF type exposes the following members:

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [`__init__(self, x=0.0, y=0.0, width=0.0, height=0.0)`](/slides/python-net/hi/aspose.slides/rectanglef/__init__/#float-float-float-float) | निर्दिष्ट स्थान और आकार के साथ एक आयत बनाता है। |

## गुण

| गुण | विवरण |
| :- | :- |
| [`x`](/slides/python-net/hi/aspose.slides/rectanglef/x/) | इस आयत के ऊपर-बाएँ कोने का x-निर्देशांक प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **float**. |
| [`y`](/slides/python-net/hi/aspose.slides/rectanglef/y/) | इस आयत के ऊपर-बाएँ कोने का y-निर्देशांक प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **float**. |
| [`width`](/slides/python-net/hi/aspose.slides/rectanglef/width/) | इस आयत की चौड़ाई प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **float**. |
| [`height`](/slides/python-net/hi/aspose.slides/rectanglef/height/) | इस आयत की ऊँचाई प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **float**. |
| [`left`](/slides/python-net/hi/aspose.slides/rectanglef/left/) | इस आयत के बाएँ किनारे का x-निर्देशांक प्राप्त करता है। यह `x` के बराबर है।<br/>            केवल-पढ़ने योग्य **float**. |
| [`top`](/slides/python-net/hi/aspose.slides/rectanglef/top/) | इस आयत के शीर्ष किनारे का y-निर्देशांक प्राप्त करता है। यह `y` के बराबर है।<br/>            केवल-पढ़ने योग्य **float**. |
| [`right`](/slides/python-net/hi/aspose.slides/rectanglef/right/) | इस आयत के `x` और `width` के योग का x-निर्देशांक प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **float**. |
| [`bottom`](/slides/python-net/hi/aspose.slides/rectanglef/bottom/) | इस आयत के `y` और `height` के योग का y-निर्देशांक प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **float**. |
| [`is_empty`](/slides/python-net/hi/aspose.slides/rectanglef/is_empty/) | निर्धारित करता है कि क्या इस आयत की सभी संख्यात्मक गुणों के मान शून्य हैं।<br/>            केवल-पढ़ने योग्य **bool**. |

## विधियां

| विधि | विवरण |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/hi/aspose.slides/rectanglef/contains/#float-float) | निर्धारित करता है कि क्या निर्दिष्ट बिंदु इस आयत के भीतर शामिल है। |
| [`contains(self, point)`](/slides/python-net/hi/aspose.slides/rectanglef/contains/#pointf) | निर्धारित करता है कि क्या निर्दिष्ट बिंदु इस आयत के भीतर शामिल है। |
| [`contains(self, rect)`](/slides/python-net/hi/aspose.slides/rectanglef/contains/#rectanglef) | निर्धारित करता है कि क्या `rect` द्वारा प्रतिनिधित्व किया गया आयताकार क्षेत्र पूरी तरह से इस आयत के भीतर शामिल है। |


### टिप्पणी

आयतों की तुलना उनके स्थान और आकार से `==` के साथ की जाती है और उन्हें शब्दकोश कुंजियों या सेट सदस्यों के रूप में उपयोग किया जा सकता है।


### देखें
* क्लास [`Rectangle`](/slides/python-net/hi/aspose.slides/rectangle)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)