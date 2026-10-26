---
title: BoxedEnum
second_title: Aspose.Slides for C++ API संदर्भ
description: "बॉक्स्ड एन्युमरेशन मान का प्रतिनिधित्व करता है। इस वर्ग की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रन-टाइम त्रुटियाँ और/या असर्शन फॉल्ट हो सकते हैं। हमेशा इस वर्ग को System::SmartPtr प्वाइंटर में लपेटें और इस प्वाइंटर का उपयोग फंक्शनों में तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 92
url: /hi/system/boxedenum/
---
## BoxedEnum वर्ग

बॉक्स्ड एन्युमरेशन मान का प्रतिनिधित्व करता है। इस वर्ग की वस्तुओं को केवल [System::MakeObject()](../makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रन-टाइम त्रुटियाँ और/या एसेर्शन दोष उत्पन्न हो सकते हैं। हमेशा इस वर्ग को [System::SmartPtr](../smartptr/) प्वाइंटर में लपेटें और इस प्वाइंटर का उपयोग करके इसे फ़ंक्शनों में तर्क के रूप में पास करें।

```cpp
template<typename E,typename UT>class BoxedEnum : public System::BoxedValue<typename std::underlying_type<E>::type>
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| E | Type of the enumeration value |
| UT | The underlying type of enumeration **E** |

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  [BoxedEnum](./boxedenum/)(E) | एक इंस्टेंस बनाता है जो निर्दिष्ट एन्युमरेशन मान का प्रतिनिधित्व करता है। |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../object/equals/) सेमान्टिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस टाइप के ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | वैल्यू टाइप के ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ऑब्जेक्ट से सम्बद्ध रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../object/gettype/) कॉल का समानांतर। |
| virtual [TypeCode](../typecode/) [GetTypeCode](../boxedvaluebase/gettypecode/)() const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए बॉक्स्ड मान के प्रकार को दर्शाने वाले मान को लौटाता है। |
| **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | बॉक्स्ड एन्युमरेशन स्थिरांक के मान को 64-बिट पूर्णांक मान में परिवर्तित करता है। |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| **bool** [IsBoxedEnum](./isboxedenum/)() override | निर्धारित करता है कि वर्तमान ऑब्जेक्ट enum प्रकार के बॉक्स्ड मान का प्रतिनिधित्व करता है या नहीं। |
| void [Lock](../object/lock/)() | C# lock() स्टेटमेंट को लॉक करने का कार्यान्वयन करता है। इसे सीधे कॉल करें या [LockContext](../lockcontext/) सेंटीनी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारम्भ करता है। |
|  [Object](../object/object/)([Object](../object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, सिर्फ नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लासों के लिए कॉपी निर्माण को सक्षम करता है। |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, सिर्फ नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लासों के लिए कॉपी निर्माण को सक्षम करता है। |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | निर्दिष्ट एन्युमरेशन के निर्दिष्ट नाम के साथ एन्युमरेशन स्थिरांक के मान को बॉक्स करता है। एक पैरामीटर यह निर्धारित करता है कि एन्युमरेशन स्थिरांक के नाम को निर्दिष्ट करने वाली स्ट्रिंग की व्याख्या करते समय केस को छोड़ा जाए या नहीं। |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | निर्दिष्ट एन्युमरेशन के निर्दिष्ट नाम के साथ एन्युमरेशन स्थिरांक के मान को बॉक्स करता है। |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशिष्टीकरण। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) का स्ट्रिंग्स केस के लिए विशिष्टीकरण। |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | nth टेम्प्लेट तर्क को एक कमजोर प्वाइंटर (शेयर किए हुए के बजाय) सेट करता है। कंटेनरों में प्वाइंटर को कमजोर मोड में बदलना संभव बनाता है। |
| int [SharedCount](../object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट प्वाइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और उसे लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट प्वाइंटर्स या ThisProtector का उपयोग करें। |
| [System::String](../string/) [ToString](./tostring/)() const override | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए बॉक्स्ड मान को स्ट्रिंग में परिवर्तित करता है। |
| [System::String](../string/) [ToString](../boxedvaluebase/tostring/)(const [System::String](../string/)\&) const | निर्दिष्ट फ़ॉर्मेट स्ट्रिंग का उपयोग करके बॉक्स्ड ऑब्जेक्ट को स्ट्रिंग में परिवर्तित करता है। |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) निर्माण को लागू करता है। |
| void [Unlock](../object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने का कार्यान्वयन करता है। इसे सीधे कॉल करें या [LockContext](../lockcontext/) सेंटीनी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट प्वाइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट प्वाइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* वर्ग [BoxedValue](../boxedvalue/)
* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)