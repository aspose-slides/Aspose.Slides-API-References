---
title: Decimal
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "एक दशमलव संख्या का प्रतिनिधित्व करता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान या संदर्भ द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं को प्रबंधित करने के लिए कभी भी System::SmartPtr क्लास का उपयोग न करें।"
type: docs
weight: 261
url: /hi/system/decimal/
---
## Decimal क्लास

एक दशमलव संख्या का प्रतिनिधित्व करता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान या संदर्भ द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं को प्रबंधित करने के लिए कभी भी [System::SmartPtr](../smartptr/) क्लास का उपयोग न करें।

```cpp
class Decimal
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | निर्दिष्ट [Decimal](./) मानों को जोड़ता है। |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | निर्दिष्ट मान से बड़ा या उसके बराबर सबसे छोटा पूर्णांक मान वापस करता है। |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | पहले [Decimal](./) ऑब्जेक्ट द्वारा दर्शाए गए मान की तुलना दूसरे [Decimal](./) ऑब्जेक्ट द्वारा दर्शाए गए मान से यह निर्धारित करता है कि वह कम है, बराबर है या बड़ा है। |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान की तुलना निर्दिष्ट ऑब्जेक्ट द्वारा दर्शाए गए मान से यह निर्धारित करता है कि वह कम है, बराबर है या बड़ा है। |
| [Decimal](./decimal/)() | 0 का प्रतिनिधित्व करने वाला एक इंस्टेंस बनाता है। |
| [Decimal](./decimal/)(std::int8_t) | निर्दिष्ट मान का प्रतिनिधित्व करने वाला एक इंस्टेंस बनाता है। |
| [Decimal](./decimal/)(std::int16_t) | निर्दिष्ट मान का प्रतिनिधित्व करने वाला एक इंस्टेंस बनाता है। |
| [Decimal](./decimal/)(std::int32_t) | निर्दिष्ट मान का प्रतिनिधित्व करने वाला एक इंस्टेंस बनाता है। |
| [Decimal](./decimal/)(std::int64_t) | निर्दिष्ट मान का प्रतिनिधित्व करने वाला एक इंस्टेंस बनाता है। |
| [Decimal](./decimal/)(std::uint8_t) | निर्दिष्ट मान का प्रतिनिधित्व करने वाला एक इंस्टेंस बनाता है। |
| [Decimal](./decimal/)(std::uint16_t) | निर्दिष्ट मान का प्रतिनिधित्व करने वाला एक इंस्टेंस बनाता है। |
| [Decimal](./decimal/)(std::uint32_t) | निर्दिष्ट मान का प्रतिनिधित्व करने वाला एक इंस्टेंस बनाता है। |
| [Decimal](./decimal/)(std::uint64_t) | निर्दिष्ट मान का प्रतिनिधित्व करने वाला एक इंस्टेंस बनाता है। |
| [Decimal](./decimal/)(**float**) | निर्दिष्ट मान का प्रतिनिधित्व करने वाला एक इंस्टेंस बनाता है। |
| [Decimal](./decimal/)(**double**) | निर्दिष्ट मान का प्रतिनिधित्व करने वाला एक इंस्टेंस बनाता है। |
| explicit [Decimal](./decimal/)(const std::string\&) | एक मान का प्रतिनिधित्व करने वाला इंस्टेंस बनाता है जिसकी स्ट्रिंग प्रतिनिधित्व std::string क्लास के इंस्टेंस के रूप में निर्दिष्ट है। |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | निर्दिष्ट घटकों से एक [Decimal](./) ऑब्जेक्ट बनाता है। |
| [Decimal](./decimal/)(const [Decimal](./)\&) | निर्दिष्ट [Decimal](./) ऑब्जेक्ट के समान संख्या का प्रतिनिधित्व करने वाली [Decimal](./) क्लास का इंस्टेंस बनाता है। |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | बाइनरी प्रतिनिधित्व वाली पूर्णांक एरे से [Decimal](./) क्लास का इंस्टेंस बनाता है। |
| [Decimal](./decimal/)(std::nullptr_t) | हमेशा ArgumentNullException फेंकता है। |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | निर्दिष्ट मान का प्रतिनिधित्व करने वाली [Decimal](./) क्लास का इंस्टेंस बनाता है। |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | निर्दिष्ट [Decimal](./) मानों को विभाजित करता है। |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | वर्तमान ऑब्जेक्ट और निर्दिष्ट ऑब्जेक्ट द्वारा दर्शाए गए मान बराबर हैं या नहीं, निर्धारित करता है। |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | वर्तमान ऑब्जेक्ट और निर्दिष्ट ऑब्जेक्ट द्वारा दर्शाए गए मान बराबर हैं या नहीं, निर्धारित करता है। |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | निर्दिष्ट ऑब्जेक्ट्स द्वारा दर्शाए गए मान बराबर हैं या नहीं, निर्धारित करता है। |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | निर्दिष्ट मान से छोटा या बराबर सबसे बड़ा पूर्णांक मान वापस करता है। |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) निर्दिष्ट OLE मुद्रा मान को समतुल्य [Decimal](./) मान में बदलता है। लागू नहीं है। |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | निर्दिष्ट [Decimal](./) ऑब्जेक्ट को उसके द्वारा दर्शाए गए मान की बाइनरी प्रतिनिधित्व में बदलता है। |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) निर्दिष्ट [Decimal](./) मान को बाइट्स की एरे में बदलता है। |
| int [GetHashCode](./gethashcode/)() const | वर्तमान ऑब्जेक्ट के लिए एक हैश कोड वापस करता है। |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | ऑब्जेक्ट प्रकार कोड प्राप्त करता है। |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | निर्दिष्ट [Decimal](./) मानों को गुणा करता है। |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | निर्दिष्ट ऑब्जेक्ट द्वारा दर्शाए गए मान के निराकरण से प्राप्त मान का प्रतिनिधित्व करने वाली नई [Decimal](./) क्लास का इंस्टेंस वापस करता है। |
| explicit [operator bool](./operator_bool/)() const | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान को बूलियन मान में बदलता है। |
| explicit [operator double](./operator_double/)() const | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान को डबल-प्रिसिशन फ्लोटिंग पॉइंट मान में बदलता है। |
| explicit [operator float](./operator_float/)() const | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान को सिंगल-प्रिसिशन फ्लोटिंग पॉइंट मान में बदलता है। |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | वर्तमान ऑब्जेक्ट और निर्दिष्ट ऑब्जेक्ट द्वारा दर्शाए गए मान समान नहीं हैं या नहीं, निर्धारित करता है। |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान 0 से अलग है या नहीं, निर्धारित करता है। |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | वर्तमान और निर्दिष्ट ऑब्जेक्ट्स द्वारा दर्शाए गए मानों के मोड्युलो ऑपरेशन के परिणाम का प्रतिनिधित्व करने वाली नई [Decimal](./) क्लास का इंस्टेंस वापस करता है। |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | वर्तमान ऑब्जेक्ट को एक नया मान असाइन करता है जो वर्तमान और निर्दिष्ट ऑब्जेक्ट्स द्वारा दर्शाए गए मानों के मोड्युलो ऑपरेशन का परिणाम है। |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | वर्तमान और निर्दिष्ट ऑब्जेक्ट्स द्वारा दर्शाए गए मानों के गुणा के परिणाम का प्रतिनिधित्व करने वाली नई [Decimal](./) क्लास का इंस्टेंस वापस करता है। |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | वर्तमान ऑब्जेक्ट को एक नया मान असाइन करता है जो वर्तमान और निर्दिष्ट ऑब्जेक्ट्स द्वारा दर्शाए गए मानों के गुणा का परिणाम है। |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | वर्तमान और निर्दिष्ट ऑब्जेक्ट्स द्वारा दर्शाए गए मानों के योग का प्रतिनिधित्व करने वाली नई [Decimal](./) क्लास का इंस्टेंस वापस करता है। |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान को बढ़ाता है। |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | वर्तमान ऑब्जेक्ट को एक नया मान असाइन करता है जो वर्तमान और निर्दिष्ट ऑब्जेक्ट्स द्वारा दर्शाए गए मानों का योग है। |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान से निर्दिष्ट ऑब्जेक्ट द्वारा दर्शाए गए मान को घटाने के परिणाम का प्रतिनिधित्व करने वाली नई [Decimal](./) क्लास का इंस्टेंस वापस करता है। |
| [Decimal](./) [operator-](./operator_minus/)() const | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान के निराकरण से प्राप्त मान का प्रतिनिधित्व करने वाली नई [Decimal](./) क्लास का इंस्टेंस वापस करता है। |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान को घटाता है। |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | वर्तमान ऑब्जेक्ट को एक नया मान असाइन करता है जो वर्तमान ऑब्जेक्ट के मान से निर्दिष्ट ऑब्जेक्ट के मान को घटाने का परिणाम है। |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान को निर्दिष्ट ऑब्जेक्ट द्वारा दर्शाए गए मान से विभाजित करने के परिणाम का प्रतिनिधित्व करने वाली नई [Decimal](./) क्लास का इंस्टेंस वापस करता है। |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | वर्तमान ऑब्जेक्ट को एक नया मान असाइन करता है जो वर्तमान ऑब्जेक्ट के मान को निर्दिष्ट ऑब्जेक्ट के मान से विभाजित करने का परिणाम है। |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान की तुलना निर्दिष्ट ऑब्जेक्ट द्वारा दर्शाए गए मान से कम है या नहीं, निर्धारित करता है। |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान की तुलना निर्दिष्ट ऑब्जेक्ट द्वारा दर्शाए गए मान से कम या बराबर है या नहीं, निर्धारित करता है। |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | निर्दिष्ट ऑब्जेक्ट द्वारा दर्शाए गए मान को वर्तमान ऑब्जेक्ट को असाइन करता है। |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | वर्तमान ऑब्जेक्ट और निर्दिष्ट ऑब्जेक्ट द्वारा दर्शाए गए मान बराबर हैं या नहीं, निर्धारित करता है। |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान 0 है या नहीं, निर्धारित करता है। |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान की तुलना निर्दिष्ट ऑब्जेक्ट द्वारा दर्शाए गए मान से बड़ा है या नहीं, निर्धारित करता है। |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान की तुलना निर्दिष्ट ऑब्जेक्ट द्वारा दर्शाए गए मान से बड़ा या बराबर है या नहीं, निर्धारित करता है। |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | दशमलव संख्या की स्ट्रिंग प्रतिनिधित्व को [Decimal](./) क्लास के समकक्ष इंस्टेंस में बदलता है। |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | निर्दिष्ट शैली का उपयोग करके दशमलव संख्या की स्ट्रिंग प्रतिनिधित्व को [Decimal](./) क्लास के समकक्ष इंस्टेंस में बदलता है। |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट फ़ॉर्मेट प्रोवाइडर का उपयोग करके दशमलव संख्या की स्ट्रिंग प्रतिनिधित्व को [Decimal](./) क्लास के समकक्ष इंस्टेंस में बदलता है। |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट शैली और फ़ॉर्मेट प्रोवाइडर का उपयोग करके दशमलव संख्या की स्ट्रिंग प्रतिनिधित्व को [Decimal](./) क्लास के समकक्ष इंस्टेंस में बदलता है। |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | दो [Decimal](./) मानों को विभाजित करने के बाद शेषफल की गणना करता है। |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | निर्दिष्ट मान को निकटतम पूर्णांक में राउंड करता है। एक पैरामीटर यह तय करता है कि यदि मान दो निकटतम संख्याओं के बराबर दूरी पर है तो फ़ंक्शन का व्यवहार क्या होगा। |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | निर्दिष्ट मान को निर्दिष्ट दशमलव अंकों की संख्या के साथ निकटतम मान में राउंड करता है। एक पैरामीटर यह तय करता है कि यदि मान दो निकटतम संख्याओं के बराबर दूरी पर है तो फ़ंक्शन का व्यवहार क्या होगा। |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | एक निर्दिष्ट [Decimal](./) मान को दूसरे से घटाता है। |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | [Decimal](./) मान को अनसाइन्ड 8-बिट पूर्णांक मान में बदलता है। |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | [Decimal](./) मान को डबल प्रिसिशन फ़्लोटिंग पॉइंट संख्या में बदलता है। |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | [Decimal](./) मान को साइनड 16-बिट पूर्णांक मान में बदलता है। |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | [Decimal](./) मान को साइनड 32-बिट पूर्णांक मान में बदलता है। |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | [Decimal](./) मान को साइनड 64-बिट पूर्णांक मान में बदलता है। |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) निर्दिष्ट [Decimal](./) मान को समतुल्य OLE मुद्रा मान में बदलता है। लागू नहीं है। |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | [Decimal](./) मान को साइनड 8-बिट पूर्णांक मान में बदलता है। |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | [Decimal](./) मान को सिंगल प्रिसिशन फ़्लोटिंग पॉइंट संख्या में बदलता है। |
| std::string [ToStdString](./tostdstring/)() const | ऑब्जेक्ट द्वारा दर्शाए गए मान की स्ट्रिंग प्रतिनिधित्व को शामिल करने वाला std::string का इंस्टेंस वापस करता है। |
| [String](../string/) [ToString](./tostring/)() const | ऑब्जेक्ट द्वारा दर्शाए गए मान की स्ट्रिंग प्रतिनिधित्व वापस करता है। |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | वर्तमान ऑब्जेक्ट को संस्कृति-विशिष्ट फ़ॉर्मेट सूचना का उपयोग करके स्ट्रिंग में बदलता है। |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | निर्दिष्ट [IFormatProvider](../iformatprovider/) ऑब्जेक्ट द्वारा प्रदान किए गए स्ट्रिंग फ़ॉर्मेट और संस्कृति-विशिष्ट फ़ॉर्मेट सूचना का उपयोग करके वर्तमान ऑब्जेक्ट को उसकी स्ट्रिंग प्रतिनिधित्व में बदलता है। |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | ऑब्जेक्ट द्वारा दर्शाए गए मान की स्ट्रिंग प्रतिनिधित्व वापस करता है। आन्तरिक उपयोग के लिये। |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | [Decimal](./) मान को अनसाइन्ड 16-बिट पूर्णांक मान में बदलता है। |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | [Decimal](./) मान को अनसाइन्ड 32-बिट पूर्णांक मान में बदलता है। |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | [Decimal](./) मान को अनसाइन्ड 64-बिट पूर्णांक मान में बदलता है। |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | निर्दिष्ट [Decimal](./) ऑब्जेक्ट द्वारा दर्शाए गए मान के समान पूर्णांक भाग वाला, सभी दशमलव अंकों को हटाकर, [Decimal](./) ऑब्जेक्ट वापस करता है। |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समकक्ष [Decimal](./) मान में बदलता है। |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | प्रदान की गई फ़ॉर्मेटिंग जानकारी और संख्या शैली का उपयोग करके संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समकक्ष [Decimal](./) मान में बदलता है। |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | [Decimal](./) क्लास की टाइप जानकारी का प्रतिनिधित्व करने वाले [TypeInfo](../typeinfo/) ऑब्जेक्ट का रेफ़रेंस वापस करता है। |
| [~Decimal](./~decimal/)() | डिस्ट्रक्टर। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static [MaxValue](./maxvalue/) | [Decimal](./) क्लास द्वारा दर्शाई जा सकने वाली सबसे बड़ी संख्या का प्रतिनिधित्व करता है। |
| static [MinusOne](./minusone/) | संख्या -1 का प्रतिनिधित्व करता है। |
| static [MinValue](./minvalue/) | [Decimal](./) क्लास द्वारा दर्शाई जा सकने वाली सबसे छोटी संख्या का प्रतिनिधित्व करता है। |
| static [One](./one/) | संख्या 1 का प्रतिनिधित्व करता है। |
| static [Zero](./zero/) | संख्या 0 का प्रतिनिधित्व करता है। |
## टाइपडिफ़्स

| टाइपडिफ़ | विवरण |
| --- | --- |
| [number_type](./number_type/) | Detail::decimal_number_type के लिए एक उपनाम है। |
## टिप्पणी

```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```
## देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)