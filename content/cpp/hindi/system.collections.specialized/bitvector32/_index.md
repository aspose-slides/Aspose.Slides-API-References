---
title: BitVector32
second_title: Aspose.Slides for C++ API संदर्भ
description: एक सरल हल्का बिट वेक्टर प्रदान करता है जिससे 32 बिट स्टोरेज तक आसान पूर्णांक या बूलियन एक्सेस किया जा सकता है।
type: docs
weight: 1
url: /hi/system.collections.specialized/bitvector32/
---
## BitVector32 क्लास

एक सरल हल्का बिट वेक्टर प्रदान करता है जिससे 32 बिट स्टोरेज तक आसान पूर्णांक या [Boolean](../../system/boolean/) एक्सेस किया जा सकता है।

```cpp
class BitVector32
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
|  [BitVector32](./bitvector32/)() | नए खाली [BitVector32](./) का एक नया उदाहरण प्रारम्भ करता है। |
|  [BitVector32](./bitvector32/)(**int32_t**) | निर्दिष्ट आंतरिक डेटा के साथ [BitVector32](./) संरचना का नया उदाहरण प्रारम्भ करता है। |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | निर्दिष्ट मान में मौज़ूद जानकारी के साथ [BitVector32](./) संरचना का नया उदाहरण प्रारम्भ करता है। |
| static **int32_t** [CreateMask](./createmask/)() | श्रृंखला में पहला मास्क बनाता है। |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | श्रृंखला में अगला मास्क बनाता है। |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | निर्दिष्ट अधिकतम मान के साथ श्रृंखला में पहला सेक्शन बनाता है। |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | निर्दिष्ट अधिकतम मान के साथ श्रृंखला में अगला सेक्शन बनाता है। |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | निर्धारित करता है कि निर्दिष्ट वस्तु वर्तमान के समान है या नहीं। |
| **int32_t** [get_Data](./get_data/)() | इस बिट वेक्टर में संग्रहीत कच्चा डेटा लौटाता है... |
| **int32_t** [GetHashCode](./gethashcode/)() const | वर्तमान वस्तु के लिए हैश कोड लौटाता है। |
| **bool** [idx_get](./idx_get/)(**int32_t**) | निर्दिष्ट सभी बिट्स सेट हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | निर्दिष्ट सेक्शन के लिए मान प्राप्त करता है। |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | निर्दिष्ट सभी बिट्स सेट हैं या नहीं, यह दर्शाने वाला मान सेट करता है। |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | निर्दिष्ट सेक्शन के लिए मान सेट करता है। |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | मूल्य पैरामीटर द्वारा दर्शाए गए मान को स्ट्रिंग में परिवर्तित करता है। |
| [String](../../system/string/) [ToString](./tostring/)() const | वर्तमान वस्तु द्वारा दर्शाए गए मान को स्ट्रिंग में परिवर्तित करता है। |

## देखें भी

* नामस्थान [System::Collections::Specialized](../)
* लाइब्रेरी [Aspose.Slides](../../)