---
title: Version
second_title: Aspose.Slides के लिए C++ API रेफरेंस
description: "एक संस्करण संख्या का प्रतिनिधित्व करता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शन को मान या संदर्भ द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं को प्रबंधित करने के लिए कभी भी System::SmartPtr क्लास का उपयोग न करें।"
type: docs
weight: 1470
url: /hi/system/version/
---
## Version क्लास

Represents a version number. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Version
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | वर्तमान वस्तु और निर्दिष्ट वस्तु द्वारा प्रतिनिधित्व किए गए संस्करणों की तुलना करता है। |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | यह निर्धारित करता है कि वर्तमान और निर्दिष्ट वस्तुओं द्वारा प्रतिनिधित्व किए गए संस्करण नंबर समान हैं या नहीं। |
| int [get_Build](./get_build/)() const | बिल्ड नंबर लौटाता है। |
| int [get_Major](./get_major/)() const | मुख्य संस्करण लौटाता है। |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | संशोधन नंबर का उच्च 16-बिट मान लौटाता है। |
| int [get_Minor](./get_minor/)() const | छोटा संस्करण लौटाता है। |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | संशोधन संख्या का निम्न 16-बिट मान लौटाता है। |
| int [get_Revision](./get_revision/)() const | संशोधन संख्या लौटाता है। |
| int [GetHashCode](./gethashcode/)() const | वर्तमान वस्तु के लिए हैश कोड लौटाता है। |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | एक संस्करण संख्या की स्ट्रिंग प्रस्तुति को [Version](./) क्लास के समतुल्य उदाहरण में परिवर्तित करता है। |
| [String](../string/) [ToString](./tostring/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए संस्करण संख्या की स्ट्रिंग प्रस्तुति लौटाता है। |
| [String](../string/) [ToString](./tostring/)(int) const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए संस्करण संख्या के निर्दिष्ट अनुभागों की संख्या की स्ट्रिंग प्रस्तुति लौटाता है। |
|  [Version](./version/)(int, int, int, int) | निर्दिष्ट प्रमुख, लघु, बिल्ड और revsion मानों का प्रतिनिधित्व करने वाला एक उदाहरण बनाता है। |
|  [Version](./version/)(int, int, int) | निर्दिष्ट प्रमुख, लघु और बिल्ड मानों का प्रतिनिधित्व करने वाला एक उदाहरण बनाता है। |
|  [Version](./version/)(int, int) | निर्दिष्ट प्रमुख और मानों का प्रतिनिधित्व करने वाला एक उदाहरण बनाता है। |
|  [Version](./version/)(const [String](../string/)\&) | एक स्ट्रिंग के रूप में प्रतिनिधित्व किए गए संस्करण संख्या का प्रतिनिधित्व करने वाला एक उदाहरण बनाता है। |
|  [Version](./version/)() | संस्करण संख्या 0.0.-1.-1 को दर्शाने वाला एक उदाहरण बनाता है। |

## संबंधित देखें

* नामस्थान [System](../)
* ग्रंथालय [Aspose.Slides](../../)