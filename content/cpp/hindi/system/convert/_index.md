---
title: Convert
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "एक संरचना जिसमें एक प्रकार के मानों को दूसरे प्रकार के मानों में परिवर्तित करने वाले मेथड्स होते हैं। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान या रेफ़रेंस द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं को प्रबंधित करने के लिए कभी भी System::SmartPtr क्लास का उपयोग न करें।"
type: docs
weight: 1561
url: /hi/system/convert/
---
## परिवर्तन संरचना

एक संरचना जो एक प्रकार के मानों को दूसरे प्रकार के मानों में परिवर्तित करने वाली विधियों को समेटे हुए है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान द्वारा या संदर्भ द्वारा पास किया जाना चाहिए। इस प्रकार के वस्तुओं को प्रबंधित करने के लिए कभी भी [System::SmartPtr](../smartptr/) क्लास का उपयोग न करें।

```cpp
class Convert
```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | लागू नहीं किया गया। |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | डिकोड करता है बेस-64 एन्कोडेड डेटा जिसे यूनिकोड कैरेक्टरों की सरणी में एक रेंज के रूप में प्रस्तुत किया गया है। |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | डिकोड करता है बेस-64 एन्कोडेड डेटा जो एक स्ट्रिंग के रूप में प्रस्तुत किया गया है। |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | निर्दिष्ट बॉक्स्ड मान के प्रकार को दर्शाने वाला TypeCode मान लौटाता है। |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | लागू नहीं किया गया। |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | लागू नहीं किया गया। नकली कार्यान्वयन, जांचता है कि मान nullptr है या नहीं। |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | निर्दिष्ट बाइट एरे में तत्वों की एक रेंज को बेस-64 एन्कोड करता है और एन्कोडेड डेटा को यूनिकोड कैरेक्टरों की एरे के रूप में संग्रहीत करता है। |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | निर्दिष्ट बाइट एरे में तत्वों की एक रेंज को बेस-64 एन्कोड करता है और एन्कोडेड डेटा को यूनिकोड कैरेक्टरों की एरे के रूप में संग्रहीत करता है। |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | निर्दिष्ट बाइट एरे में तत्वों को बेस-64 एन्कोड करता है और एन्कोडेड डेटा को स्ट्रिंग के रूप में लौटाता है। |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | निर्दिष्ट बाइट एरे में तत्वों की एक रेंज को बेस-64 एन्कोड करता है और एन्कोडेड डेटा को स्ट्रिंग के रूप में लौटाता है। |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | निर्दिष्ट बाइट एरे में तत्वों को बेस-64 एन्कोड करता है और एन्कोडेड डेटा को स्ट्रिंग के रूप में लौटाता है। |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | निर्दिष्ट बाइट एरे में तत्वों की एक रेंज को बेस-64 एन्कोड करता है और एन्कोडेड डेटा को स्ट्रिंग के रूप में लौटाता है। |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | निर्दिष्ट बूलियन मान लौटाता है। |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | निर्दिष्ट 8-बिट अनसाइनड इंटिजर को समतुल्य बूलियन मान में परिवर्तित करता है। |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | निर्दिष्ट 8-बिट साइनड इंटिजर को समतुल्य बूलियन मान में परिवर्तित करता है। |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | निर्दिष्ट 16-बिट अनसाइनड इंटिजर को समतुल्य बूलियन मान में परिवर्तित करता है। |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | निर्दिष्ट 16-बिट साइनड इंटिजर को समतुल्य बूलियन मान में परिवर्तित करता है। |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | निर्दिष्ट 32-बिट अनसाइनड इंटिजर को समतुल्य बूलियन मान में परिवर्तित करता है। |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | निर्दिष्ट 32-बिट साइनड इंटिजर को समतुल्य बूलियन मान में परिवर्तित करता है। |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | निर्दिष्ट 64-बिट अनसाइनड इंटिजर को समतुल्य बूलियन मान में परिवर्तित करता है। |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | निर्दिष्ट 64-बिट साइनड इंटिजर को समतुल्य बूलियन मान में परिवर्तित करता है। |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | निर्दिष्ट फ्लोट संख्या को समतुल्य बूलियन मान में परिवर्तित करता है। |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | निर्दिष्ट डबल संख्या को समतुल्य बूलियन मान में परिवर्तित करता है। |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | निर्दिष्ट दशमलव संख्या को समतुल्य बूलियन मान में परिवर्तित करता है। |
| static **bool** [ToBoolean](./toboolean/)(char_t) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | निर्दिष्ट null-string को समतुल्य बूलियन मान में परिवर्तित करता है। |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | निर्दिष्ट c-string को बूलियन प्रकार के मान में परिवर्तित करता है। |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | निर्दिष्ट स्ट्रिंग को बूलियन प्रकार के मान में परिवर्तित करता है। |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट स्ट्रिंग को बूलियन प्रकार के मान में परिवर्तित करता है। |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट बॉक्स्ड मान को समतुल्य बूलियन मान में परिवर्तित करता है। |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | निर्दिष्ट बूलियन मान को समतुल्य 8-बिट अनसाइनड इंटिजर में परिवर्तित करता है। |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | निर्दिष्ट 8-बिट अनसाइनड इंटिजर लौटाता है। |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | निर्दिष्ट 8-बिट साइनड इंटिजर को समतुल्य 8-बिट अनसाइनड इंटिजर में परिवर्तित करता है। |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | निर्दिष्ट 16-बिट अनसाइनड इंटिजर को समतुल्य 8-बिट अनसाइनड इंटिजर में परिवर्तित करता है। |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | निर्दिष्ट 16-बिट साइनड इंटिजर को समतुल्य 8-बिट अनसाइनड इंटिजर में परिवर्तित करता है। |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | निर्दिष्ट 32-बिट अनसाइनड इंटिजर को समतुल्य 8-बिट अनसाइनड इंटिजर में परिवर्तित करता है। |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | निर्दिष्ट 32-बिट साइनड इंटिजर को समतुल्य 8-बिट अनसाइनड इंटिजर में परिवर्तित करता है। |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | निर्दिष्ट 64-बिट अनसाइनड इंटिजर को समतुल्य 8-बिट अनसाइनड इंटिजर में परिवर्तित करता है। |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | निर्दिष्ट 64-बिट साइनड इंटिजर को समतुल्य 8-बिट अनसाइनड इंटिजर में परिवर्तित करता है। |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | निर्दिष्ट फ्लोट संख्या को समतुल्य 8-बिट अनसाइनड इंटिजर में परिवर्तित करता है। |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | निर्दिष्ट डबल संख्या को समतुल्य 8-बिट अनसाइनड इंटिजर में परिवर्तित करता है। |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | निर्दिष्ट दशमलव संख्या को समतुल्य 8-बिट अनसाइनड इंटिजर में परिवर्तित करता है। |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | निर्दिष्ट यूनिकोड कैरेक्टर को समतुल्य 8-बिट अनसाइनड इंटिजर में परिवर्तित करता है। |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | निर्दिष्ट null-string को समतुल्य अनसाइनड 8-बिट इंटिजर मान में परिवर्तित करता है। |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | निर्दिष्ट c-string जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समतुल्य अनसाइनड 8-बिट इंटिजर मान में परिवर्तित करता है। |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समतुल्य अनसाइनड 8-बिट इंटिजर मान में परिवर्तित करता है। |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | निर्दिष्ट बेस में संख्या के स्ट्रिंग प्रतिनिधित्व वाली स्ट्रिंग को समतुल्य अनसाइनड 8-बिट इंटिजर मान में परिवर्तित करता है। |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान किए गए फ़ॉर्मेटिंग जानकारी का उपयोग करके संख्या के स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समतुल्य अनसाइनड 8-बिट इंटिजर मान में परिवर्तित करता है। |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान किए गए फ़ॉर्मेटिंग सूचना और नंबर शैली का उपयोग करके संख्या के स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समतुल्य अनसाइनड 8-बिट इंटिजर मान में परिवर्तित करता है। |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट बॉक्स्ड मान को समतुल्य अनसाइनड 8-बिट इंटिजर मान में परिवर्तित करता है। |
| static char_t [ToChar](./tochar/)(**bool**) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | निर्दिष्ट 8-बिट अनसाइनड इंटिजर को समतुल्य यूनिकोड कैरेक्टर में परिवर्तित करता है। |
| static char_t [ToChar](./tochar/)(**int8_t**) | निर्दिष्ट 8-बिट साइनड इंटिजर को समतुल्य यूनिकोड कैरेक्टर में परिवर्तित करता है। |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | निर्दिष्ट 16-बिट अनसाइनड इंटिजर को समतुल्य यूनिकोड कैरेक्टर में परिवर्तित करता है। |
| static char_t [ToChar](./tochar/)(**int16_t**) | निर्दिष्ट 16-बिट साइनड इंटिजर को समतुल्य यूनिकोड कैरेक्टर में परिवर्तित करता है। |
| static char_t [ToChar](./tochar/)(**uint32_t**) | निर्दिष्ट 32-बिट अनसाइनड इंटिजर को समतुल्य यूनिकोड कैरेक्टर में परिवर्तित करता है। |
| static char_t [ToChar](./tochar/)(**int32_t**) | निर्दिष्ट 32-बिट साइनड इंटिजर को समतुल्य यूनिकोड कैरेक्टर में परिवर्तित करता है। |
| static char_t [ToChar](./tochar/)(**uint64_t**) | निर्दिष्ट 64-बिट अनसाइनड इंटिजर को समतुल्य यूनिकोड कैरेक्टर में परिवर्तित करता है। |
| static char_t [ToChar](./tochar/)(**int64_t**) | निर्दिष्ट 64-बिट साइनड इंटिजर को समतुल्य यूनिकोड कैरेक्टर में परिवर्तित करता है। |
| static char_t [ToChar](./tochar/)(**float**) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static char_t [ToChar](./tochar/)(**double**) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static constexpr char_t [ToChar](./tochar/)(char_t) | निर्दिष्ट यूनिकोड कैरेक्टर को लौटाता है। |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static char_t [ToChar](./tochar/)(const char_t *) | निर्दिष्ट c-string के पहले और एकमात्र कैरेक्टर को char_t मान में परिवर्तित करता है। |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | निर्दिष्ट स्ट्रिंग के पहले और एकमात्र कैरेक्टर को char_t मान में परिवर्तित करता है। |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट स्ट्रिंग के पहले और एकमात्र कैरेक्टर को char_t मान में परिवर्तित करता है। |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट बॉक्स्ड मान को समतुल्य यूनिकोड कैरेक्टर में परिवर्तित करता है। |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException उत्पन्न करता है। |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException उत्पन्न करता है। |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException उत्पन्न करता है। |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException उत्पन्न करता है। |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | निर्दिष्ट तिथि और समय लौटाता है। |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | निर्दिष्ट स्ट्रिंग को [DateTime](../datetime/) क्लास के एक इंस्टेंस में परिवर्तित करता है। |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान की गई फ़ॉर्मेटिंग जानकारी का उपयोग करके निर्दिष्ट स्ट्रिंग को [DateTime](../datetime/) क्लास के एक इंस्टेंस में परिवर्तित करता है। |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट बॉक्स्ड वैल्यू को समतुल्य [DateTime](../datetime/) वैल्यू में परिवर्तित करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | निर्दिष्ट बूलियन वैल्यू को समतुल्य दशमलव संख्या में परिवर्तित करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | निर्दिष्ट 8-बिट अनसाइन्ड इंटीजर को समतुल्य दशमलव संख्या में परिवर्तित करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | निर्दिष्ट 8-बिट साइन्ड इंटीजर को समतुल्य दशमलव संख्या में परिवर्तित करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | निर्दिष्ट 16-बिट अनसाइन्ड इंटीजर को समतुल्य दशमलव संख्या में परिवर्तित करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | निर्दिष्ट 16-बिट साइन्ड इंटीजर को समतुल्य दशमलव संख्या में परिवर्तित करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | निर्दिष्ट 32-बिट अनसाइन्ड इंटीजर को समतुल्य दशमलव संख्या में परिवर्तित करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | निर्दिष्ट 32-बिट साइन्ड इंटीजर को समतुल्य दशमलव संख्या में परिवर्तित करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | निर्दिष्ट 64-बिट अनसाइन्ड इंटीजर को समतुल्य दशमलव संख्या में परिवर्तित करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | निर्दिष्ट 64-बिट साइन्ड इंटीजर को समतुल्य दशमलव संख्या में परिवर्तित करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | निर्दिष्ट फ़्लोट संख्या को समतुल्य दशमलव संख्या में परिवर्तित करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | निर्दिष्ट डबल संख्या को समतुल्य दशमलव संख्या में परिवर्तित करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | निर्दिष्ट दशमलव संख्या लौटाता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException उत्पन्न करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException उत्पन्न करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | निर्दिष्ट नल-स्ट्रिंग को समतुल्य [Decimal](../decimal/) वैल्यू में परिवर्तित करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट c-स्ट्रिंग को समतुल्य [Decimal](../decimal/) वैल्यू में परिवर्तित करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समतुल्य [Decimal](../decimal/) वैल्यू में परिवर्तित करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान की गई फ़ॉर्मेटिंग जानकारी का उपयोग करके संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समतुल्य [Decimal](../decimal/) वैल्यू में परिवर्तित करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट संख्या शैलियों और फ़ॉर्मेटिंग जानकारी का उपयोग करके संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समतुल्य [Decimal](../decimal/) वैल्यू में परिवर्तित करता है। |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट बॉक्स्ड वैल्यू को समतुल्य [Decimal](../decimal/) वैल्यू में परिवर्तित करता है। |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | निर्दिष्ट बूलियन वैल्यू को समतुल्य डबल-प्रेसिशन फ्लोटिंग पॉइंट संख्या में परिवर्तित करता है। |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | निर्दिष्ट 8-बिट अनसाइन्ड इंटीजर को समतुल्य डबल-प्रेसिशन फ्लोटिंग पॉइंट संख्या में परिवर्तित करता है। |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | निर्दिष्ट 8-बिट साइन्ड इंटीजर को समतुल्य डबल-प्रेसिशन फ्लोटिंग पॉइंट संख्या में परिवर्तित करता है। |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | निर्दिष्ट 16-बिट अनसाइन्ड इंटीजर को समतुल्य डबल-प्रेसिशन फ्लोटिंग पॉइंट संख्या में परिवर्तित करता है। |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | निर्दिष्ट 16-बिट साइन्ड इंटीजर को समतुल्य डबल-प्रेसिशन फ्लोटिंग पॉइंट संख्या में परिवर्तित करता है। |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | निर्दिष्ट 32-बिट अनसाइन्ड इंटीजर को समतुल्य डबल-प्रेसिशन फ्लोटिंग पॉइंट संख्या में परिवर्तित करता है। |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | निर्दिष्ट 32-बिट साइन्ड इंटीजर को समतुल्य डबल-प्रेसिशन फ्लोटिंग पॉइंट संख्या में परिवर्तित करता है। |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | निर्दिष्ट 64-बिट अनसाइन्ड इंटीजर को समतुल्य डबल-प्रेसिशन फ्लोटिंग पॉइंट संख्या में परिवर्तित करता है। |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | निर्दिष्ट 64-बिट साइन्ड इंटीजर को समतुल्य डबल-प्रेसिशन फ्लोटिंग पॉइंट संख्या में परिवर्तित करता है। |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | निर्दिष्ट सिंगल-प्रेसिशन संख्या को समतुल्य डबल-प्रेसिशन फ्लोटिंग पॉइंट संख्या में परिवर्तित करता है। |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | निर्दिष्ट डबल संख्या लौटाता है। |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | निर्दिष्ट दशमलव संख्या को समतुल्य डबल-प्रेसिशन फ्लोटिंग पॉइंट संख्या में परिवर्तित करता है। |
| static **double** [ToDouble](./todouble/)(char_t) | रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException उत्पन्न करता है। |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException उत्पन्न करता है। |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | निर्दिष्ट नल-स्ट्रिंग को समतुल्य डबल-प्रेसिशन फ्लोटिंग पॉइंट वैल्यू में परिवर्तित करता है। |
| static **double** [ToDouble](./todouble/)(const char_t *) | संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट c-स्ट्रिंग को समतुल्य डबल-प्रेसिशन फ्लोटिंग पॉइंट वैल्यू में परिवर्तित करता है। |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समतुल्य डबल-प्रेसिशन फ्लोटिंग पॉइंट वैल्यू में परिवर्तित करता है। |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान की गई फ़ॉर्मेटिंग जानकारी का उपयोग करके संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समतुल्य डबल-प्रेसिशन फ्लोटिंग पॉइंट वैल्यू में परिवर्तित करता है। |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान की गई फ़ॉर्मेटिंग जानकारी और संख्या शैली का उपयोग करके संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समतुल्य डबल-प्रेसिशन फ्लोटिंग पॉइंट वैल्यू में परिवर्तित करता है। |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट बॉक्स्ड वैल्यू को डबल-प्रेसिशन फ्लोटिंग पॉइंट वैल्यू में परिवर्तित करता है। यदि बॉक्स्ड वैल्यू का प्रकार [String](../string/) है, तो परिवर्तन के दौरान निर्दिष्ट स्ट्रिंग फ़ॉर्मेट का उपयोग किया जाता है। |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | निर्दिष्ट बूलियन वैल्यू को समतुल्य 16-बिट साइन्ड इंटीजर में परिवर्तित करता है। |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | निर्दिष्ट 8-बिट अनसाइन्ड इंटीजर को समतुल्य 16-बिट साइन्ड इंटीजर में परिवर्तित करता है। |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | निर्दिष्ट 8-बिट साइन्ड इंटीजर को समतुल्य 16-बिट साइन्ड इंटीज़र में परिवर्तित करता है। |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | निर्दिष्ट 16-बिट अनसाइन्ड इंटीजर को समतुल्य 16-बिट साइन्ड इंटीजर में परिवर्तित करता है। |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | निर्दिष्ट 16-बिट साइन्ड इंटीजर लौटाता है। |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | निर्दिष्ट 32-बिट अनसाइन्ड इंटीजर को समतुल्य 16-बिट साइन्ड इंटीजर में परिवर्तित करता है। |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | निर्दिष्ट 32-बिट साइन्ड इंटीजर को समतुल्य 16-बिट साइन्ड इंटीजर में परिवर्तित करता है। |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | निर्दिष्ट 64-बिट अनसाइन्ड इंटीजर को समतुल्य 16-बिट साइन्ड इंटीजर में परिवर्तित करता है। |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | निर्दिष्ट 64-बिट साइन्ड इंटीजर को समतुल्य 16-बिट साइन्ड इंटीजर में परिवर्तित करता है। |
| static **int16_t** [ToInt16](./toint16/)(**float**) | निर्दिष्ट फ़्लोट संख्या को समतुल्य 16-बिट साइन्ड इंटीजर में परिवर्तित करता है। |
| static **int16_t** [ToInt16](./toint16/)(**double**) | निर्दिष्ट डबल संख्या को समतुल्य 16-बिट साइन्ड इंटीजर में परिवर्तित करता है। |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | निर्दिष्ट दशमलव संख्या को समतुल्य 16-बिट साइन्ड इंटीजर में परिवर्तित करता है। |
| static **int16_t** [ToInt16](./toint16/)(char_t) | निर्दिष्ट यूनिकोड अक्षर को समतुल्य 16-बिट साइन्ड इंटीजर में परिवर्तित करता है। |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException उत्पन्न करता है। |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | निर्दिष्ट नल-स्ट्रिंग को समतुल्य 16-बिट इंटीजर वैल्यू में परिवर्तित करता है। |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट c-स्ट्रिंग को समतुल्य 16-बिट इंटीजर वैल्यू में परिवर्तित करता है। |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समतुल्य 16-बिट इंटीजर वैल्यू में परिवर्तित करता है। |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | निर्दिष्ट आधार में संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समतुल्य 16-बिट इंटीजर वैल्यू में परिवर्तित करता है। |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान की गई फ़ॉर्मेटिंग जानकारी का उपयोग करके संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समतुल्य 16-बिट इंटीजर वैल्यू में परिवर्तित करता है। |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान की गई फ़ॉर्मेटिंग जानकारी और संख्या शैली का उपयोग करके संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समतुल्य 16-बिट इंटीजर वैल्यू में परिवर्तित करता है। |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट बॉक्स्ड वैल्यू को समतुल्य 16-बिट इंटीजर वैल्यू में परिवर्तित करता है। |
| static constexpr int [ToInt32](./toint32/)(**bool**) | निर्दिष्ट बूलियन वैल्यू को समतुल्य 32-बिट साइन्ड इंटीजर में परिवर्तित करता है। |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | निर्दिष्ट 8-बिट अनसाइन्ड इंटीजर को समतुल्य 32-बिट साइन्ड इंटीजर में परिवर्तित करता है। |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | निर्दिष्ट 8-बिट साइन्ड इन्टेजर को समकक्ष 32-बिट साइन्ड इन्टेजर में बदलता है। |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | निर्दिष्ट 16-बिट अनसाइन्ड इन्टेजर को समकक्ष 32-बिट साइन्ड इन्टेजर में बदलता है। |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | निर्दिष्ट 16-बिट साइन्ड इन्टेजर को समकक्ष 32-बिट साइन्ड इन्टेजर में बदलता है। |
| static int [ToInt32](./toint32/)(**uint32_t**) | निर्दिष्ट 32-बिट अनसाइन्ड इन्टेजर को समकक्ष 32-बिट साइन्ड इन्टेजर में बदलता है। |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | निर्दिष्ट 32-बिट साइन्ड इन्टेजर को वापस करता है। |
| static int [ToInt32](./toint32/)(**uint64_t**) | निर्दिष्ट 64-बिट अनसाइन्ड इन्टेजर को समकक्ष 32-बिट साइन्ड इन्टेजर में बदलता है। |
| static int [ToInt32](./toint32/)(**int64_t**) | निर्दिष्ट 64-बिट साइन्ड इन्टेजर को समकक्ष 32-बिट साइन्ड इन्टेजर में बदलता है। |
| static int [ToInt32](./toint32/)(**float**) | निर्दिष्ट फ्लोट संख्या को समकक्ष 32-बिट साइन्ड इन्टेजर में बदलता है। |
| static int [ToInt32](./toint32/)(**double**) | निर्दिष्ट डबल संख्या को समकक्ष 32-बिट साइन्ड इन्टेजर में बदलता है। |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | निर्दिष्ट दशमलव संख्या को समकक्ष 32-बिट साइन्ड इन्टेजर में बदलता है। |
| static constexpr int [ToInt32](./toint32/)(char_t) | निर्दिष्ट यूनिकोड अक्षर को समकक्ष 32-बिट साइन्ड इन्टेजर में बदलता है। |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | निर्दिष्ट नल-स्ट्रिंग को समकक्ष 32-बिट इन्टेजर मूल्य में बदलता है। |
| static int [ToInt32](./toint32/)(const char_t *) | निर्दिष्ट c-स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, उसे समकक्ष 32-बिट इन्टेजर मूल्य में बदलता है। |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, उसे समकक्ष 32-बिट इन्टेजर मूल्य में बदलता है। |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | निर्दिष्ट आधार में संख्या के स्ट्रिंग प्रतिनिधित्व वाली स्ट्रिंग को समकक्ष 32-बिट इन्टेजर मूल्य में बदलता है। |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान की गई फ़ॉर्मेटिंग जानकारी का उपयोग करके, निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, उसे समकक्ष 32-बिट इन्टेजर मूल्य में बदलता है। |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान किए गए फ़ॉर्मेटिंग जानकारी और संख्या शैली का उपयोग करके, निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, उसे समकक्ष 32-बिट इन्टेजर मूल्य में बदलता है। |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट बॉक्स्ड मान को समकक्ष 32-बिट इन्टेजर मूल्य में बदलता है। |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | निर्दिष्ट बूलियन मान को समकक्ष 64-बिट साइन्ड इन्टेजर में बदलता है। |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | निर्दिष्ट 8-बिट अनसाइन्ड इन्टेजर को समकक्ष 64-बिट साइन्ड इन्टेजर में बदलता है। |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | निर्दिष्ट 8-बिट साइन्ड इन्टेजर को समकक्ष 64-बिट साइन्ड इन्टेजर में बदलता है। |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | निर्दिष्ट 16-बिट अनसाइन्ड इन्टेजर को समकक्ष 64-बिट साइन्ड इन्टेजर में बदलता है। |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | निर्दिष्ट 16-बिट साइन्ड इन्टेजर को समकक्ष 64-बिट साइन्ड इन्टेजर में बदलता है। |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | निर्दिष्ट 32-बिट अनसाइन्ड इन्टेजर को समकक्ष 64-बिट साइन्ड इन्टेजर में बदलता है। |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | निर्दिष्ट 32-बिट साइन्ड इन्टेजर को समकक्ष 64-बिट साइन्ड इन्टेजर में बदलता है। |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | निर्दिष्ट 64-बिट अनसाइन्ड इन्टेजर को समकक्ष 64-बिट साइन्ड इन्टेजर में बदलता है। |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | निर्दिष्ट 64-बिट साइन्ड इन्टेजर को वापस करता है। |
| static **int64_t** [ToInt64](./toint64/)(**float**) | निर्दिष्ट फ्लोट संख्या को समकक्ष 64-बिट साइन्ड इन्टेजर में बदलता है। |
| static **int64_t** [ToInt64](./toint64/)(**double**) | निर्दिष्ट डबल संख्या को समकक्ष 64-बिट साइन्ड इन्टेजर में बदलता है। |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | निर्दिष्ट दशमलव संख्या को समकक्ष 64-बिट साइन्ड इन्टेजर में बदलता है। |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | निर्दिष्ट यूनिकोड अक्षर को समकक्ष 64-बिट साइन्ड इन्टेजर में बदलता है। |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | निर्दिष्ट नल-स्ट्रिंग को समकक्ष 64-बिट इन्टेजर मूल्य में बदलता है। |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | निर्दिष्ट c-स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, उसे समकक्ष 64-बिट इन्टेजर मूल्य में बदलता है। |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, उसे समकक्ष 64-बिट इन्टेजर मूल्य में बदलता है। |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | निर्दिष्ट आधार में संख्या के स्ट्रिंग प्रतिनिधित्व वाली स्ट्रिंग को समकक्ष 64-बिट इन्टेजर मूल्य में बदलता है। |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान की गई फ़ॉर्मेटिंग जानकारी का उपयोग करके, निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, उसे समकक्ष 64-बिट इन्टेजर मूल्य में बदलता है। |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान की गई फ़ॉर्मेटिंग जानकारी और संख्या शैली का उपयोग करके, निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, उसे समकक्ष 64-बिट इन्टेजर मूल्य में बदलता है। |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट बॉक्स्ड मान को समकक्ष 64-बिट इन्टेजर मूल्य में बदलता है। |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | निर्दिष्ट बूलियन मान को समकक्ष 8-बिट साइन्ड इन्टेजर में बदलता है। |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | निर्दिष्ट 8-बिट अनसाइन्ड इन्टेजर को समकक्ष 8-बिट साइन्ड इन्टेजर में बदलता है। |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | निर्दिष्ट 8-बिट साइन्ड इन्टेजर को वापस करता है। |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | निर्दिष्ट 16-बिट अनसाइन्ड इन्टेजर को समकक्ष 8-बिट साइन्ड इन्टेजर में बदलता है। |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | निर्दिष्ट 16-बिट साइन्ड इन्टेजर को समकक्ष 8-बिट साइन्ड इन्टेजर में बदलता है। |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | निर्दिष्ट 32-बिट अनसाइन्ड इन्टेजर को समकक्ष 8-बिट साइन्ड इन्टेजर में बदलता है। |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | निर्दिष्ट 32-बिट साइन्ड इन्टेजर को समकक्ष 8-बिट साइन्ड इन्टेजर में बदलता है। |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | निर्दिष्ट 64-बिट अनसाइन्ड इन्टेजर को समकक्ष 8-बिट साइन्ड इन्टेजर में बदलता है। |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | निर्दिष्ट 64-बिट साइन्ड इन्टेजर को समकक्ष 8-बिट साइन्ड इन्टेजर में बदलता है। |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | निर्दिष्ट फ्लोट संख्या को समकक्ष 8-बिट साइन्ड इन्टेजर में बदलता है। |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | निर्दिष्ट डबल संख्या को समकक्ष 8-बिट साइन्ड इन्टेजर में बदलता है। |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | निर्दिष्ट दशमलव संख्या को समकक्ष 8-बिट साइन्ड इन्टेजर में बदलता है। |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | निर्दिष्ट यूनिकोड अक्षर को समकक्ष 8-बिट साइन्ड इन्टेजर में बदलता है। |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | निर्दिष्ट नल-स्ट्रिंग को समकक्ष 8-बिट इन्टेजर मूल्य में बदलता है। |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | निर्दिष्ट c-स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, उसे समकक्ष 8-बिट इन्टेजर मूल्य में बदलता है। |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, उसे समकक्ष 8-बिट इन्टेजर मूल्य में बदलता है। |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | निर्दिष्ट आधार में संख्या के स्ट्रिंग प्रतिनिधित्व वाली स्ट्रिंग को समकक्ष 8-बिट इन्टेजर मूल्य में बदलता है। |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान की गई फ़ॉर्मेटिंग जानकारी का उपयोग करके, निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, उसे समकक्ष अनसाइन्ड 8-बिट इन्टेजर मूल्य में बदलता है। |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान की गई फ़ॉर्मेटिंग जानकारी और संख्या शैली का उपयोग करके, निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, उसे समकक्ष 8-बिट इन्टेजर मूल्य में बदलता है। |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट बॉक्स्ड मान को समकक्ष 8-बिट इन्टेजर मूल्य में बदलता है। |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | निर्दिष्ट बूलियन मान को समकक्ष सिंगल-प्रिसिशन फ्लोटिंग पॉइंट संख्या में बदलता है। |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | निर्दिष्ट 8-बिट अनसाइन्ड इन्टेजर को समकक्ष सिंगल-प्रिसिशन फ्लोटिंग पॉइंट संख्या में बदलता है। |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | निर्दिष्ट 8-बिट साइन्ड इन्टेजर को समकक्ष सिंगल-प्रिसिशन फ्लोटिंग पॉइंट संख्या में बदलता है। |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | निर्दिष्ट 16-बिट अनसाइन्ड इन्टेजर को समकक्ष सिंगल-प्रिसिशन फ्लोटिंग पॉइंट संख्या में बदलता है। |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | निर्दिष्ट 16-बिट साइन्ड इन्टेजर को समकक्ष सिंगल-प्रिसिशन फ्लोटिंग पॉइंट संख्या में बदलता है। |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | निर्दिष्ट 32-बिट अनसाइन्ड इन्टेजर को समकक्ष सिंगल-प्रिसिशन फ्लोटिंग पॉइंट संख्या में बदलता है। |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | निर्दिष्ट 32-बिट साइन्ड इन्टेजर को समकक्ष सिंगल-प्रिसिशन फ्लोटिंग पॉइंट संख्या में बदलता है। |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | निर्दिष्ट 64-बिट अनसाइन्ड इंटीजर को समान एकल-प्रेसिशन फ्लोटिंग-पॉइंट संख्या में परिवर्तित करता है। |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | निर्दिष्ट 64-बिट साइन्ड इंटीजर को समान एकल-प्रेसिशन फ्लोटिंग-पॉइंट संख्या में परिवर्तित करता है। |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | निर्दिष्ट फ्लोट संख्या को लौटाता है। |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | निर्दिष्ट डबल-प्रेसिशन संख्या को समान एकल-प्रेसिशन फ्लोटिंग-पॉइंट संख्या में परिवर्तित करता है। |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | निर्दिष्ट दशमलव संख्या को समान एकल-प्रेसिशन फ्लोटिंग-पॉइंट संख्या में परिवर्तित करता है। |
| static **float** [ToSingle](./tosingle/)(char_t) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | निर्दिष्ट नल-स्ट्रिंग को समान एकल-प्रेसिशन फ्लोटिंग-पॉइंट मान में परिवर्तित करता है। |
| static **float** [ToSingle](./tosingle/)(const char_t *) | संख्या के स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट C-स्ट्रिंग को समान एकल-प्रेसिशन फ्लोटिंग-पॉइंट मान में परिवर्तित करता है। |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | संख्या के स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समान एकल-प्रेसिशन फ्लोटिंग-पॉइंट मान में परिवर्तित करता है। |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान किए गए फ़ॉर्मेटिंग जानकारी का उपयोग करके, संख्या के स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समान एकल-प्रेसिशन फ्लोटिंग-पॉइंट मान में परिवर्तित करता है। |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान किए गए फ़ॉर्मेटिंग जानकारी और संख्या शैली का उपयोग करके, संख्या के स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समान एकल-प्रेसिशन फ्लोटिंग-पॉइंट मान में परिवर्तित करता है। |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट बॉक्स्ड मान को एकल-प्रेसिशन फ्लोटिंग-पॉइंट मान में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | निर्दिष्ट मान को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | निर्दिष्ट मान को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | निर्दिष्ट मान को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | निर्दिष्ट मान को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | निर्दिष्ट मान को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | निर्दिष्ट मान को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | निर्दिष्ट मान को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | निर्दिष्ट मान को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**float**) | निर्दिष्ट मान को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**double**) | निर्दिष्ट मान को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | निर्दिष्ट मान को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | निर्दिष्ट मान को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके स्ट्रिंग में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके स्ट्रिंग में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके स्ट्रिंग में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके स्ट्रिंग में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके स्ट्रिंग में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके स्ट्रिंग में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके स्ट्रिंग में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके स्ट्रिंग में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके स्ट्रिंग में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके स्ट्रिंग में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके स्ट्रिंग में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके स्ट्रिंग में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट [IFormatProvider](../iformatprovider/) ऑब्जेक्ट द्वारा प्रदान किए गए निर्दिष्ट स्ट्रिंग फ़ॉर्मेट और संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके, निर्दिष्ट मान को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट [IFormatProvider](../iformatprovider/) ऑब्जेक्ट द्वारा प्रदान किए गए निर्दिष्ट स्ट्रिंग फ़ॉर्मेट और संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके, निर्दिष्ट मान को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट [IFormatProvider](../iformatprovider/) ऑब्जेक्ट द्वारा प्रदान किए गए निर्दिष्ट स्ट्रिंग फ़ॉर्मेट और संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके, निर्दिष्ट मान को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट [IFormatProvider](../iformatprovider/) ऑब्जेक्ट द्वारा प्रदान किए गए निर्दिष्ट स्ट्रिंग फ़ॉर्मेट और संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके, निर्दिष्ट मान को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट [IFormatProvider](../iformatprovider/) ऑब्जेक्ट द्वारा प्रदान किए गए निर्दिष्ट स्ट्रिंग फ़ॉर्मेट और संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके, निर्दिष्ट मान को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट [IFormatProvider](../iformatprovider/) ऑब्जेक्ट द्वारा प्रदान किए गए निर्दिष्ट स्ट्रिंग फ़ॉर्मेट और संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके, निर्दिष्ट मान को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को उसकी स्ट्रिंग अभिव्यक्ति में परिवर्तित करता है, निर्दिष्ट स्ट्रिंग फ़ॉर्मेट और निर्दिष्ट [IFormatProvider](../iformatprovider/) वस्तु द्वारा प्रदान की गई सांस्कृतिक-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके। |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को उसकी स्ट्रिंग अभिव्यक्ति में परिवर्तित करता है, निर्दिष्ट स्ट्रिंग फ़ॉर्मेट और निर्दिष्ट [IFormatProvider](../iformatprovider/) वस्तु द्वारा प्रदान की गई सांस्कृतिक-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके। |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को उसकी स्ट्रिंग अभिव्यक्ति में परिवर्तित करता है, निर्दिष्ट स्ट्रिंग फ़ॉर्मेट और निर्दिष्ट [IFormatProvider](../iformatprovider/) वस्तु द्वारा प्रदान की गई सांस्कृतिक-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके। |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को उसकी स्ट्रिंग अभिव्यक्ति में परिवर्तित करता है, निर्दिष्ट स्ट्रिंग फ़ॉर्मेट और निर्दिष्ट [IFormatProvider](../iformatprovider/) वस्तु द्वारा प्रदान की गई सांस्कृतिक-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके। |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को उसकी स्ट्रिंग अभिव्यक्ति में परिवर्तित करता है, निर्दिष्ट स्ट्रिंग फ़ॉर्मेट और निर्दिष्ट [IFormatProvider](../iformatprovider/) वस्तु द्वारा प्रदान की गई सांस्कृतिक-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके। |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को उसकी स्ट्रिंग अभिव्यक्ति में परिवर्तित करता है, निर्दिष्ट स्ट्रिंग फ़ॉर्मेट और निर्दिष्ट [IFormatProvider](../iformatprovider/) वस्तु द्वारा प्रदान की गई सांस्कृतिक-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके। |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | निर्दिष्ट मान को स्ट्रिंग में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | निर्दिष्ट मान को निर्दिष्ट स्ट्रिंग फ़ॉर्मेट का उपयोग करके स्ट्रिंग में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | निर्दिष्ट यूनिकोड अक्षरों की एरे को स्ट्रिंग में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट यूनिकोड अक्षरों की एरे को स्ट्रिंग में, निर्दिष्ट [IFormatProvider](../iformatprovider/) वस्तु द्वारा प्रदान की गई सांस्कृतिक-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके, परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | निर्दिष्ट मान को लौटाता है; कोई परिवर्तन नहीं किया जाता। |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को लौटाता है; कोई परिवर्तन नहीं किया जाता। |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | निर्दिष्ट मान को लौटाता है; कोई परिवर्तन नहीं किया जाता। |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | निर्दिष्ट मान को लौटाता है; कोई परिवर्तन नहीं किया जाता। |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | निर्दिष्ट मान को लौटाता है; कोई परिवर्तन नहीं किया जाता। |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को लौटाता है; कोई परिवर्तन नहीं किया जाता। |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | निर्दिष्ट मान को लौटाता है; कोई परिवर्तन नहीं किया जाता। |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट मान को लौटाता है; कोई परिवर्तन नहीं किया जाता। |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | निर्दिष्ट मान को लौटाता है; कोई परिवर्तन नहीं किया जाता। |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | निर्दिष्ट मान को लौटाता है; कोई परिवर्तन नहीं किया जाता। |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | निर्दिष्ट बूलियन मान को उसकी स्ट्रिंग अभिव्यक्ति में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट बूलियन मान को उसकी स्ट्रिंग अभिव्यक्ति में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | निर्दिष्ट बूलियन मान को उसकी स्ट्रिंग अभिव्यक्ति में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | निर्दिष्ट बूलियन मान को उसकी स्ट्रिंग अभिव्यक्ति में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट बूलियन मान को उसकी स्ट्रिंग अभिव्यक्ति में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | निर्दिष्ट बूलियन मान को उसकी स्ट्रिंग अभिव्यक्ति में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | निर्दिष्ट बूलियन मान को उसकी स्ट्रिंग अभिव्यक्ति में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | निर्दिष्ट पूर्णांक मान को निर्दिष्ट आधार में उसकी स्ट्रिंग अभिव्यक्ति में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | निर्दिष्ट पूर्णांक मान को निर्दिष्ट आधार में उसकी स्ट्रिंग अभिव्यक्ति में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | निर्दिष्ट पूर्णांक मान को निर्दिष्ट आधार में उसकी स्ट्रिंग अभिव्यक्ति में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | निर्दिष्ट पूर्णांक मान को निर्दिष्ट आधार में उसकी स्ट्रिंग अभिव्यक्ति में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट बॉक्स्ड मान को उसकी स्ट्रिंग अभिव्यक्ति में परिवर्तित करता है। यदि बॉक्स्ड मान का प्रकार [String](../string/) है, तो परिवर्तन के दौरान निर्दिष्ट स्ट्रिंग फ़ॉर्मेट का उपयोग किया जाता है। |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | निर्दिष्ट बूलियन मान को समकक्ष 16-bit अपरिच्छेदित पूर्णांक में परिवर्तित करता है। |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | निर्दिष्ट 8-bit अपरिच्छेदित पूर्णांक को समकक्ष 16-bit अपरिच्छेदित पूर्णांक में परिवर्तित करता है। |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | निर्दिष्ट 8-bit साइनड पूर्णांक को समकक्ष 16-bit अपरिच्छेदित पूर्णांक में परिवर्तित करता है। |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | निर्दिष्ट 16-bit अपरिच्छेदित पूर्णांक को लौटाता है। |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | निर्दिष्ट 16-bit साइनड पूर्णांक को समकक्ष 16-bit अपरिच्छेदित पूर्णांक में परिवर्तित करता है। |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | निर्दिष्ट 32-bit अपरिच्छेदित पूर्णांक को समकक्ष 16-bit अपरिच्छेदित पूर्णांक में परिवर्तित करता है। |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | निर्दिष्ट 32-bit साइनड पूर्णांक को समकक्ष 16-bit अपरिच्छेदित पूर्णांक में परिवर्तित करता है। |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | निर्दिष्ट 64-bit अपरिच्छेदित पूर्णांक को समकक्ष 16-bit अपरिच्छेदित पूर्णांक में परिवर्तित करता है। |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | निर्दिष्ट 64-bit साइनड पूर्णांक को समकक्ष 16-bit अपरिच्छेदित पूर्णांक में परिवर्तित करता है। |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | निर्दिष्ट फ़्लोट संख्या को समकक्ष 16-bit अपरिच्छेदित पूर्णांक में परिवर्तित करता है। |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | निर्दिष्ट डबल संख्या को समकक्ष 16-bit अपरिच्छेदित पूर्णांक में परिवर्तित करता है। |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | निर्दिष्ट दशमलव संख्या को समकक्ष 16-bit अपरिच्छेदित पूर्णांक में परिवर्तित करता है। |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | निर्दिष्ट यूनिकोड अक्षर को समकक्ष 16-bit अपरिच्छेदित पूर्णांक में परिवर्तित करता है। |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | परिवर्तन समर्थित नहीं है। हमेशा InvalidCastException फेंकेगा। |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | निर्दिष्ट नल-स्ट्रिंग को समकक्ष अपरिच्छेदित 16-bit पूर्णांक मान में परिवर्तित करता है। |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | निर्दिष्ट C-स्ट्रिंग जिसमें संख्या की स्ट्रिंग अभिव्यक्ति है, को समकक्ष अपरिच्छेदित 16-bit पूर्णांक मान में परिवर्तित करता है। |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | निर्दिष्ट स्ट्रिंग जिसमें संख्या की स्ट्रिंग अभिव्यक्ति है, को समकक्ष अपरिच्छेदित 16-bit पूर्णांक मान में परिवर्तित करता है। |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | निर्दिष्ट बेस में संख्या की स्ट्रिंग अभिव्यक्ति वाली स्ट्रिंग को समकक्ष अपरिच्छेदित 16-bit पूर्णांक मान में परिवर्तित करता है। |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट फ़ॉर्मेटिंग जानकारी का उपयोग करके, संख्या की स्ट्रिंग अभिव्यक्ति वाली स्ट्रिंग को समकक्ष अपरिच्छेदित 16-bit पूर्णांक मान में परिवर्तित करता है। |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट फ़ॉर्मेटिंग जानकारी और नंबर शैली का उपयोग करके, संख्या की स्ट्रिंग अभिव्यक्ति वाली स्ट्रिंग को समकक्ष अपरिच्छेदित 16-bit पूर्णांक मान में परिवर्तित करता है। |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट बॉक्स्ड मान को समकक्ष अपरिच्छेदित 16-bit पूर्णांक मान में परिवर्तित करता है। |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | निर्दिष्ट बूलियन मान को समकक्ष 32-bit अपरिच्छेदित पूर्णांक में परिवर्तित करता है। |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | निर्दिष्ट 8-bit अपरिच्छेदित पूर्णांक को समकक्ष 32-bit अपरिच्छेदित पूर्णांक में परिवर्तित करता है। |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | निर्दिष्ट 8-bit साइनड पूर्णांक को समकक्ष 32-bit अपरिच्छेदित पूर्णांक में परिवर्तित करता है। |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | निर्दिष्ट 16-bit अपरिच्छेदित पूर्णांक को समकक्ष 32-bit अपरिच्छेदित पूर्णांक में परिवर्तित करता है। |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | निर्दिष्ट 16-bit साइनड पूर्णांक को समकक्ष 32-bit अपरिच्छेदित पूर्णांक में परिवर्तित करता है। |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | निर्दिष्ट 32-bit अपरिच्छेदित पूर्णांक को लौटाता है। |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | निर्दिष्ट 32-बिट साइन किए गए पूर्णांक को समकक्ष 32-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | निर्दिष्ट 64-बिट अनसाइन्ड पूर्णांक को समकक्ष 32-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | निर्दिष्ट 64-बिट साइन किए गए पूर्णांक को समकक्ष 32-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | निर्दिष्ट फ्लोट संख्या को समकक्ष 32-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | निर्दिष्ट डबल संख्या को समकक्ष 32-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | निर्दिष्ट दशमलव संख्या को समकक्ष 32-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | निर्दिष्ट यूनिकोड अक्षर को समकक्ष 32-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | निर्दिष्ट नल-स्ट्रिंग को समकक्ष अनसाइन्ड 32-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट c-स्ट्रिंग को समकक्ष अनसाइन्ड 32-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समकक्ष अनसाइन्ड 32-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | निर्दिष्ट आधार में संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समकक्ष अनसाइन्ड 32-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान किए गए स्वरूपण जानकारी का उपयोग करके संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समकक्ष अनसाइन्ड 32-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान किए गए स्वरूपण जानकारी और संख्या शैली का उपयोग करके संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समकक्ष अनसाइन्ड 32-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट बॉक्स्ड मान को समकक्ष अनसाइन्ड 32-बिट पूर्णांक मान में परिवर्तित करता है। |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | निर्दिष्ट बूलियन मान को समकक्ष 64-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | निर्दिष्ट 8-बिट अनसाइन्ड पूर्णांक को समकक्ष 64-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | निर्दिष्ट 8-बिट साइन किए गए पूर्णांक को समकक्ष 64-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | निर्दिष्ट 16-बिट अनसाइन्ड पूर्णांक को समकक्ष 64-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | निर्दिष्ट 16-बिट साइन किए गए पूर्णांक को समकक्ष 64-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | निर्दिष्ट 32-बिट अनसाइन्ड पूर्णांक को समकक्ष 64-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | निर्दिष्ट 32-बिट साइन किए गए पूर्णांक को समकक्ष 64-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | निर्दिष्ट 64-बिट अनसाइन्ड पूर्णांक लौटाता है। |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | निर्दिष्ट 64-बिट साइन किए गए पूर्णांक को समकक्ष 64-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | निर्दिष्ट फ्लोट संख्या को समकक्ष 64-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | निर्दिष्ट डबल संख्या को समकक्ष 64-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | निर्दिष्ट दशमलव संख्या को समकक्ष 64-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | निर्दिष्ट यूनिकोड अक्षर को समकक्ष 64-बिट अनसाइन्ड पूर्णांक में परिवर्तित करता है। |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException फेंकता है। |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | निर्दिष्ट नल-स्ट्रिंग को समकक्ष अनसाइन्ड 64-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट c-स्ट्रिंग को समकक्ष अनसाइन्ड 64-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समकक्ष अनसाइन्ड 64-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | निर्दिष्ट आधार में संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समकक्ष अनसाइन्ड 64-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान किए गए स्वरूपण जानकारी का उपयोग करके संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समकक्ष अनसाइन्ड 64-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान किए गए स्वरूपण जानकारी और संख्या शैली का उपयोग करके संख्या की स्ट्रिंग प्रतिनिधित्व वाली निर्दिष्ट स्ट्रिंग को समकक्ष अनसाइन्ड 64-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट बॉक्स्ड मान को समकक्ष अनसाइन्ड 64-बिट पूर्णांक मान में परिवर्तित करता है। |
## संबंधित देखें

* नामस्थान [System](../)
* पुस्तकालय [Aspose.Slides](../../)