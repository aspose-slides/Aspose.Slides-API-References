---
title: HtmlExternalResolver class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.importing/htmlexternalresolver/
---
## HtmlExternalResolver क्लास

HTML आयात रूटीन द्वारा छवियों जैसे संदर्भित वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट।  
इस रिज़ॉल्वर का उपयोग करने से सुरक्षा जोखिम पैदा हो सकता है जब क्लाइंट द्वारा प्रदान किया गया HTML फ़ाइल सर्वर सॉफ़्टवेयर को स्थानीय या नेटवर्क फ़ाइल प्राप्त करने के लिए मजबूर करे। सावधानी से उपयोग करें। यह अनुशंसा की जाती है कि HtmlExternalResolver को बिल्कुल निर्दिष्ट न करें (केवल एंबेडेड ऑब्जेक्ट पढ़े जाएंगे) या ऐसा उपवर्ग बनाएँ जो यह जांचे कि निर्दिष्ट URI मान्य है या नहीं।

HtmlExternalResolver प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/hi/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | Resolves the absolute URI from the base and relative URIs. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/hi/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | Maps a URI to an object containing the actual resource. |

### संदर्भ
* मॉड्यूल [`aspose.slides.importing`](/slides/python-net/hi/aspose.slides.importing)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)