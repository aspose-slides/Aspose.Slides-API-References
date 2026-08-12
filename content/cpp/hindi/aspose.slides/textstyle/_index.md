---
title: TextStyle
second_title: Aspose.Slides for C++ API संदर्भ
description: यह वर्ग पाठ शैली स्वरूपण गुणों को सम्मिलित करता है।
type: docs
weight: 5500
url: /hi/aspose.slides/textstyle/
---
## TextStyle वर्ग

यह वर्ग पाठ शैली स्वरूपण गुणों को सम्मिलित करता है।

```cpp
class TextStyle : public Aspose::Slides::PVIObject,
                  public Aspose::Slides::ITextStyle,
                  public Aspose::Slides::IStyleColorOwner
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्दिष्ट वस्तु के साथ तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के बराबर भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के बराबर भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\> [get_DefaultParagraphFormat](./get_defaultparagraphformat/)() override | डिफ़ॉल्ट पैराग्राफ गुण। केवल पढ़ने योग्य [IParagraphFormat](../iparagraphformat/)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [IDOMObject](../idomobject/)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | पैरेंट [IPresentationComponent](../ipresentationcomponent/) लौटाता है। केवल पढ़ने योग्य [IPresentationComponent](../ipresentationcomponent/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफरेंस काउंटर डेटा संरचना प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyleEffectiveData](../itextstyleeffectivedata/)\> [GetEffective](./geteffective/)() override | विरासत लागू होने के साथ प्रभावी टेक्स्ट स्टाइल स्वरूपण डेटा प्राप्त करता है। |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | हैश कोड लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\> [GetLevel](./getlevel/)(**int32_t**) override | यदि शैली स्तर मौजूद है तो उसे लौटाता है, अन्यथा null लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँच करता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() बयान का लॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारम्भ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लासों की कॉपी निर्माण सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लासों की कॉपी निर्माण सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स को रेफरेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स को रेफरेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | नल पॉइंटर के साथ वैल्यू टाइप ऑब्जेक्ट की रेफरेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | string और nullptr केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का strings केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्धारित मान द्वारा साझा रेफरेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को एक कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफरेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफरेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफरेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() बयान का अनलॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफरेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफरेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## देखें भी

* वर्ग [PVIObject](../pviobject/)
* वर्ग [ITextStyle](../itextstyle/)
* वर्ग [IStyleColorOwner](../istylecolorowner/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)