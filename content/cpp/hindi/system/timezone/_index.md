---
title: TimeZone
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "एक समय क्षेत्र का प्रतिनिधित्व करता है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फॉल्ट्स हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन में आर्ग्यूमेंट के रूप में पास करने के लिए करें।"
type: docs
weight: 1327
url: /hi/system/timezone/
---
## TimeZone क्लास

एक समय क्षेत्र का प्रतिनिधित्व करता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन दोष हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शन के आर्गुमेंट के रूप में पास करें।

```cpp
class TimeZone : public System::Object
```

## विधियां

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहां दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहां दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| static [TimeZonePtr](../timezoneptr/) [get_CurrentTimeZone](./get_currenttimezone/)() | [TimeZone](./) क्लास का एक नया इंस्टेंस लौटाता है जो वर्तमान समय क्षेत्र का प्रतिनिधित्व करता है। |
| virtual [String](../string/) [get_DaylightName](./get_daylightname/)() const | वर्तमान वस्तु द्वारा दर्शाए गए समय क्षेत्र के डेलाइट सेविंग टाइम का नाम लौटाता है। |
| virtual [String](../string/) [get_StandardName](./get_standardname/)() const | वर्तमान वस्तु द्वारा दर्शाए गए समय क्षेत्र के स्टैंडर्ड टाइम का नाम लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | वस्तु से जुड़ी रेफरेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual [Globalization::DaylightTimePtr](../../system.globalization/daylighttimeptr/) [GetDaylightChanges](./getdaylightchanges/)(**int32_t**) | किसी विशेष वर्ष के लिए डेलाइट सेविंग टाइम अवधि लौटाता है। |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) मेथड का समकक्ष। कस्टम वस्तुओं के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../object/gettype/) कॉल का समकक्ष। |
| virtual [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)([DateTime](../datetime/)) | निर्दिष्ट स्थानीय समय के लिए UTC ऑफसेट लौटाता है। |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | जाँचता है कि वस्तु targetType द्वारा वर्णित टाइप की इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| virtual **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)([DateTime](../datetime/)) | निर्धारित करता है कि निर्दिष्ट [DateTime](../datetime/) वस्तु द्वारा दर्शाए गए तिथि और समय मान को यह निर्धारित करता है कि क्या यह वर्तमान [TimeZone](./) वस्तु द्वारा दर्शाए गए समय क्षेत्र के डेलाइट सेविंग टाइम रेंज में आता है। |
| void [Lock](../object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग को लागू करता है। इसे सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../object/object/)([Object](../object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नई वस्तु को इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नई वस्तु को इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | वस्तुओं की रेफरेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफरेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | रेफरेंस-तुलना वैल्यू टाइप वस्तु को nullptr से करती है। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | string और nullptr के केस के लिए [Object::ReferenceEquals](../object/referenceequals/) का विशिष्टकरण। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | strings के केस के लिए [Object::ReferenceEquals](../object/referenceequals/) का विशिष्टकरण। |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफरेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्यूमेंट को एक वीक पॉइंटर सेट करता है (शेयर किए हुए के बजाय)। कंटेनर्स में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../object/sharedcount/)() const | साझा रेफरेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | साझा रेफरेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | साझा रेफरेंस काउंट को घटाता है और वापस करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../string/) [ToString](../object/tostring/)() const | C# [Object.ToString()](../object/tostring/) मेथड का समकक्ष। कस्टम वस्तुओं को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) निर्माण को लागू करता है। |
| void [Unlock](../object/unlock/)() | C# lock() स्टेटमेंट की अनलॉकिंग को लागू करता है। इसे सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | वीक रेफरेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../object/weakrefremoved/)() | वीक रेफरेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../object/~object/)() | वस्तु को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## देखें

* क्लास [Object](../object/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)