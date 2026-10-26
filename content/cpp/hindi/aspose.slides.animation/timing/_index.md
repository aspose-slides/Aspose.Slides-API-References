---
title: Timing
second_title: Aspose.Slides for C++ API संदर्भ
description: एनीमेशन टाइमिंग को दर्शाता है।
type: docs
weight: 625
url: /hi/aspose.slides.animation/timing/
---
## टाइमिंग क्लास

एनीमेशन टाइमिंग को दर्शाता है।

```cpp
class Timing : public Aspose::Slides::Animation::ITiming,
               public Aspose::Slides::IDOMObject
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग कर वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **float** [get_Accelerate](./get_accelerate/)() override | अवधि के एक्सेलेरेट व्यवहार प्रभाव का प्रतिशत बताता है। **float** पढ़ें। |
| **bool** [get_AutoReverse](./get_autoreverse/)() override | फॉरवर्ड दिशा में चलाने के बाद एनीमेशन को प्रतिकूल दिशा में स्वचालित रूप से चलाने का वर्णन करता है। **bool** पढ़ें। |
| **float** [get_Decelerate](./get_decelerate/)() override | अवधि के डीसलेरेट व्यवहार प्रभाव का प्रतिशत बताता है। **float** पढ़ें। |
| **float** [get_Duration](./get_duration/)() override | एनीमेशन प्रभाव की अवधि का वर्णन करता है। **float** पढ़ें। |
| **float** [get_RepeatCount](./get_repeatcount/)() override | प्रभाव को दोहराने की संख्या बताता है। **float** पढ़ें। |
| **float** [get_RepeatDuration](./get_repeatduration/)() override | प्रभाव को दोहराने की संख्या बताता है। **float** पढ़ें। |
| **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() override | यह गुण बताता है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। **bool** पढ़ें। |
| **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() override | यह गुण बताता है कि प्रभाव अगली क्लिक तक दोहराया जाएगा या नहीं। **bool** पढ़ें। |
| [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() override | पूरी होने के बाद प्रभाव को पुनः शुरू करना है या नहीं, यह निर्दिष्ट करता है। [EffectRestartType](../effectrestarttype/) पढ़ें। |
| **bool** [get_Rewind](./get_rewind/)() override | यह गुण बताता है कि प्रभाव चलाने के बाद रीवाइंड किया जाएगा या नहीं। **bool** पढ़ें। |
| **float** [get_Speed](./get_speed/)() override | टाइमिंग को कितना तेज (या धीमा) करना है, इसका प्रतिशत निर्दिष्ट करता है। **float** पढ़ें। |
| **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() override | ट्रिगर के बाद की देरी समय का वर्णन करता है। **float** पढ़ें। |
| [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() override | ट्रिगर प्रकार का वर्णन करता है। [EffectTriggerType](../effecttriggertype/) पढ़ें। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानुपाती। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानुपाती। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट लक्ष्य टाइप द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानुपाती। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानुपाती। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Accelerate](./set_accelerate/)(**float**) override | अवधि के एक्सेलेरेट व्यवहार प्रभाव का प्रतिशत बताता है। **float** लिखें। |
| void [set_AutoReverse](./set_autoreverse/)(**bool**) override | फॉरवर्ड दिशा में चलाने के बाद एनीमेशन को प्रतिकूल दिशा में स्वचालित रूप से चलाने का वर्णन करता है। **bool** लिखें। |
| void [set_Decelerate](./set_decelerate/)(**float**) override | अवधि के डीसलेरेट व्यवहार प्रभाव का प्रतिशत बताता है। **float** लिखें। |
| void [set_Duration](./set_duration/)(**float**) override | एनीमेशन प्रभाव की अवधि का वर्णन करता है। **float** लिखें। |
| void [set_RepeatCount](./set_repeatcount/)(**float**) override | प्रभाव को दोहराने की संख्या बताता है। **float** लिखें। |
| void [set_RepeatDuration](./set_repeatduration/)(**float**) override | प्रभाव को दोहराने की संख्या बताता है। **float** लिखें। |
| void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) override | यह गुण दर्शाता है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। **bool** लिखें। |
| void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) override | यह गुण दर्शाता है कि प्रभाव अगले क्लिक तक दोहराया जाएगा या नहीं। **bool** लिखें। |
| void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) override | पूरा होने के बाद प्रभाव को पुनः शुरू करना है या नहीं, यह निर्दिष्ट करता है। [EffectRestartType](../effectrestarttype/) लिखें। |
| void [set_Rewind](./set_rewind/)(**bool**) override | यह गुण दर्शाता है कि प्रभाव प्ले होने के बाद रीवाइंड किया जाएगा या नहीं। **bool** लिखें। |
| void [set_Speed](./set_speed/)(**float**) override | टाइमिंग को कितना तेज (या धीमा) करना है, इसका प्रतिशत निर्दिष्ट करता है। **float** लिखें। |
| void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) override | ट्रिगर के बाद की देरी समय का वर्णन करता है। **float** लिखें। |
| void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) override | ट्रिगर प्रकार का वर्णन करता है। [EffectTriggerType](../effecttriggertype/) लिखें। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को एक वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानुपाती। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संबंधित देखें

* क्लास [ITiming](../itiming/)
* क्लास [IDOMObject](../../aspose.slides/idomobject/)
* नामस्थान [Aspose::Slides::Animation](../)
* लाइब्रेरी [Aspose.Slides](../../)