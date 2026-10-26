---
title: ITiming
second_title: Aspose.Slides for C++ API संदर्भ
description: एनिमेशन टाइमिंग का प्रतिनिधित्व करता है।
type: docs
weight: 443
url: /hi/aspose.slides.animation/itiming/
---
## ITiming वर्ग

एनिमेशन टाइमिंग का प्रतिनिधित्व करता है।

```cpp
class ITiming : public virtual System::Object
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिये। |
| virtual **float** [get_Accelerate](./get_accelerate/)() | अवधि के त्वरित व्यवहार प्रभाव का प्रतिशत वर्णन करता है। **float** पढ़ें। |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | वर्णन करता है कि क्या फ़ॉरवर्ड दिशा में चलने के बाद एनीमेशन को रिवर्स में स्वतः चलना चाहिए। **bool** पढ़ें। |
| virtual **float** [get_Decelerate](./get_decelerate/)() | अवधि के धीमे व्यवहार प्रभाव का प्रतिशत वर्णन करता है। **float** पढ़ें। |
| virtual **float** [get_Duration](./get_duration/)() | एनीमेशन प्रभाव की अवधि वर्णन करता है। **float** पढ़ें। |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | प्रभाव को दोहराने की संख्या वर्णन करता है। **float** पढ़ें। |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | प्रभाव को दोहराने की संख्या वर्णन करता है। **float** पढ़ें। |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | यह गुण निर्दिष्ट करता है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। **bool** पढ़ें। |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | यह गुण निर्दिष्ट करता है कि प्रभाव अगले क्लिक तक दोहराया जाएगा या नहीं। **bool** पढ़ें। |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | निर्दिष्ट करता है कि क्या प्रभाव पूरी होने के बाद पुनः प्रारंभ होना चाहिए। [EffectRestartType](../effectrestarttype/) पढ़ें। |
| virtual **bool** [get_Rewind](./get_rewind/)() | यह गुण निर्दिष्ट करता है कि प्रभाव समाप्त होने के बाद रीवाइंड होगा या नहीं। **bool** पढ़ें। |
| virtual **float** [get_Speed](./get_speed/)() | टाइमिंग को तेज (या धीमा) करने का प्रतिशत निर्दिष्ट करता है। **float** पढ़ें। |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | ट्रिगर के बाद देरी समय का वर्णन करता है। **float** पढ़ें। |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | ट्रिगर प्रकार का वर्णन करता है। [EffectTriggerType](../effecttriggertype/) पढ़ें। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट का लॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का प्रयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर्स को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट आरम्भ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट आरम्भ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस के साथ वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग और nullptr के केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग्स के केस के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | अवधि के त्वरित व्यवहार प्रभाव का प्रतिशत वर्णन करता है। **float** लिखें। |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | वर्णन करता है कि क्या फ़ॉरवर्ड दिशा में चलने के बाद एनीमेशन को रिवर्स में स्वतः चलना चाहिए। **bool** लिखें। |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | अवधि के धीमे व्यवहार प्रभाव का प्रतिशत वर्णन करता है। **float** लिखें। |
| virtual void [set_Duration](./set_duration/)(**float**) | एनीमेशन प्रभाव की अवधि वर्णन करता है। **float** लिखें। |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | प्रभाव को दोहराने की संख्या वर्णन करता है। **float** लिखें। |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | प्रभाव को दोहराने की संख्या वर्णन करता है। **float** लिखें। |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | यह गुण निर्धारित करता है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। **bool** लिखें। |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | यह गुण निर्धारित करता है कि प्रभाव अगले क्लिक तक दोहराया जाएगा या नहीं। **bool** लिखें। |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | निर्धारित करता है कि क्या प्रभाव पूर्ण होने के बाद पुनः प्रारंभ होना चाहिए। [EffectRestartType](../effectrestarttype/) लिखें। |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | यह गुण निर्धारित करता है कि प्रभाव समाप्त होने के बाद रीवाइंड होगा या नहीं। **bool** लिखें। |
| virtual void [set_Speed](./set_speed/)(**float**) | टाइमिंग को तेज (या धीमा) करने का प्रतिशत निर्दिष्ट करता है। **float** लिखें। |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | ट्रिगर के बाद देरी समय का वर्णन करता है। **float** लिखें। |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | ट्रिगर प्रकार का वर्णन करता है। [EffectTriggerType](../effecttriggertype/) लिखें। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'वें टेम्पलेट आर्ग्यूमेंट को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनर में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का प्रयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर्स को मुक्त करता है। |

## देखें

* वर्ग [Object](../../system/object/)
* नेमस्पेस [Aspose::Slides::Animation](../)
* लाइब्रेरी [Aspose.Slides](../../)