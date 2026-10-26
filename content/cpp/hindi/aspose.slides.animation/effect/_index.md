---
title: Effect
second_title: Aspose.Slides for C++ API संदर्भ
description: एनीमेशन इफ़ेक्ट को दर्शाता है।
type: docs
weight: 118
url: /hi/aspose.slides.animation/effect/
---
## प्रभाव वर्ग


एनिमेशन प्रभाव का प्रतिनिधित्व करता है।

```cpp
class Effect : public Aspose::Slides::Animation::IEffect,
               public Aspose::Slides::IDOMObject
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantics का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में संदर्भ प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में मान प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_AfterAnimationColor](./get_afteranimationcolor/)() override | इफ़ेक्ट के बाद की एनीमेशन रंग को परिभाषित करता है। पढ़ें [IColorFormat](../../aspose.slides/icolorformat/)। |
| [Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/) [get_AfterAnimationType](./get_afteranimationtype/)() override | इफ़ेक्ट के बाद की एनीमेशन प्रकार को परिभाषित करता है। पढ़ें [AfterAnimationType](../afteranimationtype/)। |
| [Aspose::Slides::Animation::AnimateTextType](../animatetexttype/) [get_AnimateTextType](./get_animatetexttype/)() override | इफ़ेक्ट के लिए एनीमेट टेक्स्ट प्रकार को परिभाषित करता है। शेप टेक्स्ट को अक्षर द्वारा, शब्द द्वारा या एक साथ एनीमेट किया जा सकता है। पढ़ें [AnimateTextType](../animatetexttype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\> [get_Behavior](./get_behavior/)(**int32_t**) override | निर्दिष्ट अनुक्रमणिका पर एनीमेशन व्यवहार लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\> [get_Behaviors](./get_behaviors/)() override | इफ़ेक्ट के लिए व्यवहार का संग्रह लौटाता है। पढ़ें [IBehaviorCollection](../ibehaviorcollection/)। |
| **float** [get_DelayBetweenTextParts](./get_delaybetweentextparts/)() override | एनीमेटेड टेक्स्ट भागों (शब्दों या अक्षरों) के बीच देरी को परिभाषित करता है। एक सकारात्मक मान प्रभाव अवधि का प्रतिशत निर्धारित करता है। एक नकारात्मक मान सेकंड में देरी निर्धारित करता है। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffect](../ieffect/)\> [get_Effect](./get_effect/)(**int32_t**) override | निर्दिष्ट अनुक्रमणिका पर अनुक्रम के प्रभाव को लौटाता है। |
| [EffectPresetClassType](../effectpresetclasstype/) [get_PresetClassType](./get_presetclasstype/)() override | इफ़ेक्ट का वर्ग परिभाषित करता है। पढ़ें [EffectPresetClassType](../effectpresetclasstype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISequence](../isequence/)\> [get_Sequence](./get_sequence/)() override | इफ़ेक्ट के लिए एक अनुक्रम लौटाता है। केवल-पढ़ने योग्य [ISequence](../isequence/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | इफ़ेक्ट के लिए एम्बेडेड साउंड को परिभाषित करता है। पढ़ें [IAudio](../../aspose.slides/iaudio/)। |
| **bool** [get_StopPreviousSound](./get_stopprevioussound/)() override | यह विशेषता निर्दिष्ट करती है कि एनीमेशन इफ़ेक्ट पिछले साउंड को रोकता है या नहीं। पढ़ें **bool**। |
| [EffectSubtype](../effectsubtype/) [get_Subtype](./get_subtype/)() override | इफ़ेक्ट का उपप्रकार परिभाषित करता है। पढ़ें [EffectSubtype](../effectsubtype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [get_TargetShape](./get_targetshape/)() override | इफ़ेक्ट के लिए लक्ष्य शेप लौटाता है। केवल-पढ़ने योग्य [IShape](../../aspose.slides/ishape/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextAnimation](../itextanimation/)\> [get_TextAnimation](./get_textanimation/)() override | [TextAnimation](../textanimation/) केवल-पढ़ने योग्य [ITextAnimation](../itextanimation/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](./get_timing/)() override | इफ़ेक्ट के लिए टाइमिंग मान परिभाषित करता है। पढ़ें [ITiming](../itiming/)। |
| [EffectType](../effecttype/) [get_Type](./get_type/)() override | इफ़ेक्ट का प्रकार परिभाषित करता है। पढ़ें [EffectType](../effecttype/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समतुल्य। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समतुल्य। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समतुल्य। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समतुल्य। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कॉन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास के कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास के कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | मान प्रकार के ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा शेयर्ड रेफ़रेंस काउंट को घटाता है। |
| void [set_AfterAnimationColor](./set_afteranimationcolor/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) override | इफ़ेक्ट के बाद की एनीमेशन रंग को परिभाषित करता है। लिखें [IColorFormat](../../aspose.slides/icolorformat/)। |
| void [set_AfterAnimationType](./set_afteranimationtype/)([Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/)) override | इफ़ेक्ट के बाद की एनीमेशन प्रकार को परिभाषित करता है। लिखें [AfterAnimationType](../afteranimationtype/)। |
| void [set_AnimateTextType](./set_animatetexttype/)([Aspose::Slides::Animation::AnimateTextType](../animatetexttype/)) override | इफ़ेक्ट के लिए एनीमेट टेक्स्ट प्रकार को परिभाषित करता है। शेप टेक्स्ट को अक्षर द्वारा, शब्द द्वारा या एक साथ एनीमेट किया जा सकता है। लिखें [AnimateTextType](../animatetexttype/)। |
| void [set_Behavior](./set_behavior/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\>) override | निर्दिष्ट अनुक्रमणिका पर एनीमेशन व्यवहार सेट करता है। |
| void [set_Behaviors](./set_behaviors/)([System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\>) override | इफ़ेक्ट के लिए व्यवहार का संग्रह लौटाता है। लिखें [IBehaviorCollection](../ibehaviorcollection/)। |
| void [set_DelayBetweenTextParts](./set_delaybetweentextparts/)(**float**) override | एनीमेटेड टेक्स्ट भागों (शब्दों या अक्षरों) के बीच देरी को परिभाषित करता है। एक सकारात्मक मान प्रभाव अवधि का प्रतिशत निर्धारित करता है। एक नकारात्मक मान सेकंड में देरी निर्धारित करता है। लिखें **float**। |
| void [set_PresetClassType](./set_presetclasstype/)([EffectPresetClassType](../effectpresetclasstype/)) override | इफ़ेक्ट का वर्ग परिभाषित करता है। लिखें [EffectPresetClassType](../effectpresetclasstype/)। |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | इफ़ेक्ट के लिए एम्बेडेड साउंड को परिभाषित करता है। लिखें [IAudio](../../aspose.slides/iaudio/)। |
| void [set_StopPreviousSound](./set_stopprevioussound/)(**bool**) override | यह विशेषता निर्दिष्ट करती है कि एनीमेशन इफ़ेक्ट पिछले साउंड को रोकता है या नहीं। लिखें **bool**। |
| void [set_Subtype](./set_subtype/)([EffectSubtype](../effectsubtype/)) override | इफ़ेक्ट का उपप्रकार परिभाषित करता है। लिखें [EffectSubtype](../effectsubtype/)। |
| void [set_Timing](./set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | इफ़ेक्ट के लिए टाइमिंग मान परिभाषित करता है। लिखें [ITiming](../itiming/)। |
| void [set_Type](./set_type/)([EffectType](../effecttype/)) override | इफ़ेक्ट का प्रकार परिभाषित करता है। लिखें [EffectType](../effecttype/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्यूमेंट को एक कमजोर पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समतुल्य। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* वर्ग [IEffect](../ieffect/)
* वर्ग [IDOMObject](../../aspose.slides/idomobject/)
* नामस्थान [Aspose::Slides::Animation](../)
* लाइब्रेरी [Aspose.Slides](../../)