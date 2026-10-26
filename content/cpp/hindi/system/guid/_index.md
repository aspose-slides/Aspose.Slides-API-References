---
title: Guid
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "एक ग्लोबली यूनिक आइडेंटिफायर का प्रतिनिधित्व करता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान द्वारा या संदर्भ द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं का प्रबंधन करने के लिए System::SmartPtr क्लास का कभी उपयोग न करें।"
type: docs
weight: 885
url: /hi/system/guid/
---
## Guid क्लास

Represents a Globally Unique IDentifier This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) क्लास to manage objects of this type.

```cpp
class Guid
```

## विधियाँ

| Method | Description |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | वर्तमान और निर्दिष्ट ऑब्जेक्ट्स द्वारा प्रतिनिधित्व किए गए GUIDs की अंकगणितीय तुलना करता है। |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | निर्धारित करता है कि वर्तमान और निर्दिष्ट ऑब्जेक्ट्स द्वारा प्रतिनिधित्व किए गए GUIDs समान हैं या नहीं। |
| int [GetHashCode](./gethashcode/)() const | वर्तमान ऑब्जेक्ट के लिए एक हैश कोड लौटाता है। |
|  [Guid](./guid/)() | सभी शून्य वाले GUID का प्रतिनिधित्व करने वाला ऑब्जेक्ट बनाता है। |
|  [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | 8-बिट अनसाइन्ड इंटीजर मानों की एरे के रूप में निर्दिष्ट GUID का प्रतिनिधित्व करने वाला ऑब्जेक्ट बनाता है। |
|  [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | 8-बिट अनसाइन्ड इंटीजर मानों की एरे व्यू के रूप में निर्दिष्ट GUID का प्रतिनिधित्व करने वाला ऑब्जेक्ट बनाता है। |
|  [Guid](./guid/)(const [String](../string/)\&) | स्ट्रिंग के रूप में निर्दिष्ट GUID का प्रतिनिधित्व करने वाला ऑब्जेक्ट बनाता है। |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Guid](./) क्लास का एक इंस्टेंस बनाता है निर्दिष्ट GUID घटकों से। |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | [Guid](./) क्लास का एक इंस्टेंस बनाता है निर्दिष्ट GUID घटकों से। |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | [Guid](./) क्लास का एक इंस्टेंस बनाता है निर्दिष्ट अनसाइन्ड इंटीजर्स और बाइट्स से। |
|  [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | [Guid](./) क्लास का एक इंस्टेंस बनाता है निर्दिष्ट अनसाइन्ड इंटीजर्स और बाइट्स से। |
|  [Guid](./guid/)(const [Guid](./)\&) | निर्दिष्ट ऑब्जेक्ट के समान GUID का प्रतिनिधित्व करने वाला ऑब्जेक्ट बनाता है। |
| static [Guid](./) [NewGuid](./newguid/)() | एक नया GUID उत्पन्न करता है और एक [Guid](./) ऑब्जेक्ट लौटाता है जो इसे दर्शाता है। |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | निर्धारित करता है कि वर्तमान और निर्दिष्ट ऑब्जेक्ट्स द्वारा प्रतिनिधित्व किए गए GUIDs असमान हैं या नहीं। |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | वर्तमान ऑब्जेक्ट को निर्दिष्ट [Guid](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया GUID मान असाइन करता है। |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | निर्धारित करता है कि वर्तमान और निर्दिष्ट ऑब्जेक्ट्स द्वारा प्रतिनिधित्व किए गए GUIDs समान हैं या नहीं। |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | GUID की निर्दिष्ट स्ट्रिंग प्रतिरूप को समकक्ष [Guid](./) ऑब्जेक्ट में परिवर्तित करता है। |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए GUID को बाइट्स की एरे में परिवर्तित करता है। |
| [String](../string/) [ToString](./tostring/)() const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए GUID को उसकी स्ट्रिंग प्रतिरूप में परिवर्तित करता है। |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए GUID को निर्दिष्ट स्ट्रिंग फ़ॉर्मेट का उपयोग करके उसकी स्ट्रिंग प्रतिरूप में परिवर्तित करता है। |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए GUID को निर्दिष्ट स्ट्रिंग फ़ॉर्मेट और कल्चर का उपयोग करके उसकी स्ट्रिंग प्रतिरूप में परिवर्तित करता है। |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | निर्दिष्ट स्ट्रिंग को [Guid](./) ऑब्जेक्ट में परिवर्तित करने का प्रयास करता है। |
|  [~Guid](./~guid/)() | विनाशकर्ता। |

## फ़ील्ड्स

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | एक GUID का प्रतिनिधित्व करता है जिसकी मान 0 है। |

## संबंधित

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)