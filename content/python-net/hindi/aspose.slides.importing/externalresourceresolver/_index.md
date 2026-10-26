---
title: ExternalResourceResolver class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver क्लास

Callback क्लास उपयोग किया जाता है बाहरी संसाधनों को हल करने के लिए Html, Svg दस्तावेज़ आयात के दौरान। इस रिसॉल्वर का उपयोग करने से एक भेद्यता उत्पन्न हो सकती है जब क्लाइंट द्वारा प्रदान किया गया HTML या SVG फ़ाइल सर्वर सॉफ़्टवेयर को स्थानीय या नेटवर्क फ़ाइल प्राप्त करने के लिए मजबूर करती है। सावधानी से उपयोग करें। यह अनुशंसा की जाती है कि ExternalResourceResolver को बिल्कुल न निर्दिष्ट किया जाए (केवल एम्बेडेड ऑब्जेक्ट पढ़े जाएंगे) या कोई सबक्लास बनाया जाए जो जांचे कि निर्दिष्ट uri वैध है या नहीं।

ExternalResourceResolver प्रकार निम्नलिखित सदस्य प्रदर्शित करता है:

## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## मेथड

| मेथड | विवरण |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/hi/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | बेस और रिलेटिव URI से पूर्ण URI को हल करता है। |
| [`get_entity(self, absolute_uri)`](/slides/python-net/hi/aspose.slides.importing/externalresourceresolver/get_entity/#str) | एक URI को वास्तविक संसाधन वाले ऑब्जेक्ट में मैप करता है। |

### सम्बंधित देखें
* मॉड्यूल [`aspose.slides.importing`](/slides/python-net/hi/aspose.slides.importing)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)