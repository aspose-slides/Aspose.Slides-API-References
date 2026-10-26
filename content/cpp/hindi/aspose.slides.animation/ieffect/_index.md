---
title: IEffect
second_title: Aspose.Slides for C++ API संदर्भ
description: एनीमेशन प्रभाव को दर्शाता है।
type: docs
weight: 248
url: /hi/aspose.slides.animation/ieffect/
---
## IEffect क्लास

एनीमेशन प्रभाव को दर्शाता है।

```cpp
class IEffect : public virtual System::Object
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता, फिर भी दो NaN को समान माना जाता है, ऐसा C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता, फिर भी दो NaN को समान माना जाता है, ऐसा C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_AfterAnimationColor](./get_afteranimationcolor/)() | प्रभाव के लिए बाद की एनीमेशन रंग निर्धारित किया गया। पढ़ें [IColorFormat](../../aspose.slides/icolorformat/)। |
| virtual [Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/) [get_AfterAnimationType](./get_afteranimationtype/)() | प्रभाव के लिए बाद की एनीमेशन प्रकार निर्धारित किया गया। पढ़ें [AfterAnimationType](../afteranimationtype/)। |
| virtual [Aspose::Slides::Animation::AnimateTextType](../animatetexttype/) [get_AnimateTextType](./get_animatetexttype/)() | प्रभाव के लिए एनीमेट टेक्स्ट प्रकार निर्धारित करता है। आकार का टेक्स्ट अक्षर, शब्द, या सभी एक साथ एनीमेट किया जा सकता है। पढ़ें [AnimateTextType](../animatetexttype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\> [get_Behavior](./get_behavior/)(**int32_t**) | निर्दिष्ट इंडेक्स पर एनीमेशन व्यवहार लौटाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\> [get_Behaviors](./get_behaviors/)() | प्रभाव के लिए व्यवहार का संग्रह लौटाता है। पढ़ें [IBehaviorCollection](../ibehaviorcollection/)। |
| virtual **float** [get_DelayBetweenTextParts](./get_delaybetweentextparts/)() | एनीमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच देरी निर्धारित करता है। एक सकारात्मक मान प्रभाव की अवधि का प्रतिशत दर्शाता है। एक नकारात्मक मान सेकंड में देरी दर्शाता है। पढ़ें **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffect](./)\> [get_Effect](./get_effect/)(**int32_t**) | निर्दिष्ट इंडेक्स पर क्रम के प्रभाव को लौटाता है। |
| virtual [EffectPresetClassType](../effectpresetclasstype/) [get_PresetClassType](./get_presetclasstype/)() | प्रभाव की क्लास निर्धारित करता है। पढ़ें [EffectPresetClassType](../effectpresetclasstype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISequence](../isequence/)\> [get_Sequence](./get_sequence/)() | प्रभाव के लिए क्रम लौटाता है। केवल-पढ़ने योग्य [ISequence](../isequence/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() | प्रभाव के लिए एम्बेडेड साउंड निर्धारित किया गया। पढ़ें [IAudio](../../aspose.slides/iaudio/)। |
| virtual **bool** [get_StopPreviousSound](./get_stopprevioussound/)() | यह गुण निर्दिष्ट करता है कि क्या एनीमेशन प्रभाव पिछले साउंड को रोकता है। पढ़ें **bool**। |
| virtual [EffectSubtype](../effectsubtype/) [get_Subtype](./get_subtype/)() | प्रभाव का उपप्रकार निर्धारित करता है। पढ़ें [EffectSubtype](../effectsubtype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [get_TargetShape](./get_targetshape/)() | प्रभाव के लिए लक्ष्य आकार लौटाता है। केवल-पढ़ने योग्य [IShape](../../aspose.slides/ishape/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextAnimation](../itextanimation/)\> [get_TextAnimation](./get_textanimation/)() | टेक्स्ट एनीमेशन लौटाता है। केवल-पढ़ने योग्य [ITextAnimation](../itextanimation/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](./get_timing/)() | प्रभाव के लिए टाइमिंग मान निर्धारित करता है। पढ़ें [ITiming](../itiming/)। |
| virtual [EffectType](../effecttype/) [get_Type](./get_type/)() | प्रभाव का प्रकार निर्धारित करता है। पढ़ें [EffectType](../effecttype/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| virtual void [set_AfterAnimationColor](./set_afteranimationcolor/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) | प्रभाव के लिए बाद की एनीमेशन रंग निर्धारित किया गया। लिखें [IColorFormat](../../aspose.slides/icolorformat/)। |
| virtual void [set_AfterAnimationType](./set_afteranimationtype/)([Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/)) | प्रभाव के लिए बाद की एनीमेशन प्रकार निर्धारित किया गया। लिखें [AfterAnimationType](../afteranimationtype/)। |
| virtual void [set_AnimateTextType](./set_animatetexttype/)([Aspose::Slides::Animation::AnimateTextType](../animatetexttype/)) | प्रभाव के लिए एनीमेट टेक्स्ट प्रकार निर्धारित करता है। आकार का टेक्स्ट अक्षर, शब्द, या सभी एक साथ एनीमेट किया जा सकता है। लिखें [AnimateTextType](../animatetexttype/)। |
| virtual void [set_Behavior](./set_behavior/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\>) | निर्दिष्ट इंडेक्स पर एनीमेशन व्यवहार निर्धारित करें। |
| virtual void [set_Behaviors](./set_behaviors/)([System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\>) | प्रभाव के लिए व्यवहार का संग्रह लौटाता है। लिखें [IBehaviorCollection](../ibehaviorcollection/)। |
| virtual void [set_DelayBetweenTextParts](./set_delaybetweentextparts/)(**float**) | एनीमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच देरी निर्धारित करता है। एक सकारात्मक मान प्रभाव की अवधि का प्रतिशत दर्शाता है। एक नकारात्मक मान सेकंड में देरी दर्शाता है। लिखें **float**। |
| virtual void [set_PresetClassType](./set_presetclasstype/)([EffectPresetClassType](../effectpresetclasstype/)) | प्रभाव की क्लास निर्धारित करता है। लिखें [EffectPresetClassType](../effectpresetclasstype/)। |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) | प्रभाव के लिए एम्बेडेड साउंड निर्धारित किया गया। लिखें [IAudio](../../aspose.slides/iaudio/)। |
| virtual void [set_StopPreviousSound](./set_stopprevioussound/)(**bool**) | यह गुण निर्दिष्ट करता है कि क्या एनीमेशन प्रभाव पिछले साउंड को रोकता है। लिखें **bool**। |
| virtual void [set_Subtype](./set_subtype/)([EffectSubtype](../effectsubtype/)) | प्रभाव का उपप्रकार निर्धारित करता है। लिखें [EffectSubtype](../effectsubtype/)। |
| virtual void [set_Timing](./set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) | प्रभाव के लिए टाइमिंग मान निर्धारित करता है। लिखें [ITiming](../itiming/)। |
| virtual void [set_Type](./set_type/)([EffectType](../effecttype/)) | प्रभाव का प्रकार निर्धारित करता है। लिखें [EffectType](../effecttype/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | टेम्पलेट के n'th आर्ग्यूमेंट को कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंटर बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंटर घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [Object](../../system/object/)
* नामस्थान [Aspose::Slides::Animation](../)
* लाइब्रेरी [Aspose.Slides](../../)