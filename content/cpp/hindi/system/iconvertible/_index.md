---
title: IConvertible
second_title: Aspose.Slides for C++ API संदर्भ
description: "ऐसे मेथड्स को परिभाषित करता है जो लागू करने वाले रेफ़रेंस या वैल्यू टाइप के मान को समान मान वाले कॉमन लैंग्वेज रनटाइम टाइप में परिवर्तित करते हैं। इस वर्ग की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार की इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ उत्पन्न हो सकती हैं। इस वर्ग को हमेशा System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर को तर्क के रूप में फ़ंक्शनों में पास करें।"
type: docs
weight: 937
url: /hi/system/iconvertible/
---
## IConvertible वर्ग

वह विधियों को परिभाषित करता है जो लागू करने वाले रेफ़रेंस या वैल्यू टाइप के मान को समान मान वाले कॉमन लैंग्वेज रनटाइम टाइप में परिवर्तित करती हैं। इस वर्ग की वस्तुओं को केवल [System::MakeObject()](../makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार की इंस्टेंस को स्टैक पर या operator new का उपयोग करके न बनाएं, क्योंकि यह रनटाइम त्रुटियों और/या असर्शन फ़ॉल्ट्स का कारण बन सकता है। हमेशा इस वर्ग को [System::SmartPtr](../smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे तर्क के रूप में फ़ंक्शन में पास करें।

```cpp
class IConvertible : public virtual System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) सिमेंटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../object/gettype/) कॉल का समानार्थी। |
| virtual [System::TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() | इस इंस्टेंस के लिए टाइप कोड लौटाता है। |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | जाँचें कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप के इंस्टेंस को दर्शाता है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../object/lock/)() | C# lock() स्टेटमेंट के लॉक को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारंभ करता है। |
|  [Object](../object/object/)([Object](../object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n'tth टेम्पलेट आर्ग्यूमेंट को एक वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual **bool** [ToBoolean](./toboolean/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | निर्देशित सांस्कृतिक-विशिष्ट फ़ॉर्मेटिंग जानकारी का उपयोग करके इस इंस्टेंस के मान को समान [Boolean](../boolean/) मान में परिवर्तित करता है। |
| virtual **uint8_t** [ToByte](./tobyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | निर्देशित सांस्कृतिक-विशिष्ट फ़ॉर्मेटिंग जानकारी का उपयोग करके इस इंस्टेंस के मान को समान 8-बिट uint32_teger में परिवर्तित करता है। |
| virtual char_t [ToChar](./tochar/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | निर्देशित सांस्कृतिक-विशिष्ट फ़ॉर्मेटिंग जानकारी का उपयोग करके इस इंस्टेंस के मान को समान यूनिकोड अक्षर में परिवर्तित करता है। |
| virtual [System::DateTime](../datetime/) [ToDateTime](./todatetime/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | निर्देशित सांस्कृतिक-विशिष्ट फ़ॉर्मेटिंग जानकारी का उपयोग करके इस इंस्टेंस के मान को समान [System::DateTime](../datetime/) में परिवर्तित करता है। |
| virtual [System::Decimal](../decimal/) [ToDecimal](./todecimal/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | निर्देशित सांस्कृतिक-विशिष्ट फ़ॉर्मेटिंग जानकारी का उपयोग करके इस इंस्टेंस के मान को समान [System::Decimal](../decimal/) संख्या में परिवर्तित करता है। |
| virtual **double** [ToDouble](./todouble/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | निर्देशित सांस्कृतिक-विशिष्ट फ़ॉर्मेटिंग जानकारी का उपयोग करके इस इंस्टेंस के मान को समान डबल-प्रिसिजन फ़्लोटिंग पॉइंट संख्या में परिवर्तित करता है। |
| virtual **int16_t** [ToInt16](./toint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | निर्देशित सांस्कृतिक-विशिष्ट फ़ॉर्मेटिंग जानकारी का उपयोग करके इस इंस्टेंस के मान को समान 16-बिट साइन्ड इंटीजर में परिवर्तित करता है। |
| virtual **int32_t** [ToInt32](./toint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | निर्देशित सांस्कृतिक-विशिष्ट फ़ॉर्मेटिंग जानकारी का उपयोग करके इस इंस्टेंस के मान को समान 32-बिट साइन्ड इंटीजर में परिवर्तित करता है। |
| virtual **int64_t** [ToInt64](./toint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | निर्देशित सांस्कृतिक-विशिष्ट फ़ॉर्मेटिंग जानकारी का उपयोग करके इस इंस्टेंस के मान को समान 64-बिट साइन्ड इंटीजर में परिवर्तित करता है। |
| virtual **int8_t** [ToSByte](./tosbyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | निर्देशित सांस्कृतिक-विशिष्ट फ़ॉर्मेटिंग जानकारी का उपयोग करके इस इंस्टेंस के मान को समान 8-बिट साइन्ड इंटीजर में परिवर्तित करता है। |
| virtual **float** [ToSingle](./tosingle/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | निर्देशित सांस्कृतिक-विशिष्ट फ़ॉर्मेटिंग जानकारी का उपयोग करके इस इंस्टेंस के मान को समान सिंगल-प्रिसिजन फ़्लोटिंग पॉइंट संख्या में परिवर्तित करता है। |
| virtual [System::String](../string/) [ToString](./tostring/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | निर्देशित सांस्कृतिक-विशिष्ट फ़ॉर्मेटिंग जानकारी का उपयोग करके इस इंस्टेंस के मान को समान [System::String](../string/) में परिवर्तित करता है। |
| virtual [String](../string/) [ToString](./tostring/)() const | C# [Object.ToString()](../object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम बनाता है। |
| virtual [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\> [ToType](./totype/)(const [TypeInfo](../typeinfo/)\&, [System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | निर्देशित सांस्कृतिक-विशिष्ट फ़ॉर्मेटिंग जानकारी का उपयोग करके इस इंस्टेंस के मान को समान मान वाला निर्दिष्ट System::Type का [System::Object](../object/) में परिवर्तित करता है। |
| virtual **uint16_t** [ToUInt16](./touint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | निर्देशित सांस्कृतिक-विशिष्ट फ़ॉर्मेटिंग जानकारी का उपयोग करके इस इंस्टेंस के मान को समान 16-बिट uint32_teger में परिवर्तित करता है। |
| virtual **uint32_t** [ToUInt32](./touint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | निर्देशित सांस्कृतिक-विशिष्ट फ़ॉर्मेटिंग जानकारी का उपयोग करके इस इंस्टेंस के मान को समान 32-बिट uint32_teger में परिवर्तित करता है। |
| virtual **uint64_t** [ToUInt64](./touint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | निर्देशित सांस्कृतिक-विशिष्ट फ़ॉर्मेटिंग जानकारी का उपयोग करके इस इंस्टेंस के मान को समान 64-बिट uint32_teger में परिवर्तित करता है। |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) निर्माण को लागू करता है। |
| void [Unlock](../object/unlock/)() | C# lock() स्टेटमेंट के अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* वर्ग [Object](../object/)
* नामस्थान [System](../)
* पुस्तकालय [Aspose.Slides](../../)