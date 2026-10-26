---
title: EffectFormat
second_title: C++ के लिए Aspose.Slides API रेफ़रेंस
description: आकार के प्रभाव गुणों का प्रतिनिधित्व करता है।
type: docs
weight: 846
url: /hi/aspose.slides/effectformat/
---
## EffectFormat क्लास


आकार के प्रभाव गुणों का प्रतिनिधित्व करता है।

```cpp
class EffectFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IEffectFormat
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| void [DisableBlurEffect](./disableblureffect/)() override | ब्लर प्रभाव को निष्क्रिय करता है। |
| void [DisableFillOverlayEffect](./disablefilloverlayeffect/)() override | फ़िल ओवरले प्रभाव को निष्क्रिय करता है। |
| void [DisableGlowEffect](./disablegloweffect/)() override | ग्लो प्रभाव को निष्क्रिय करता है। |
| void [DisableInnerShadowEffect](./disableinnershadoweffect/)() override | आंतरिक शेडो प्रभाव को निष्क्रिय करता है। |
| void [DisableOuterShadowEffect](./disableoutershadoweffect/)() override | बाह्य शेडो प्रभाव को निष्क्रिय करता है। |
| void [DisablePresetShadowEffect](./disablepresetshadoweffect/)() override | प्रीसेट शेडो प्रभाव को निष्क्रिय करता है। |
| void [DisableReflectionEffect](./disablereflectioneffect/)() override | रिफ्लेक्शन प्रभाव को निष्क्रिय करता है। |
| void [DisableSoftEdgeEffect](./disablesoftedgeeffect/)() override | सॉफ्ट एज प्रभाव को निष्क्रिय करता है। |
| void [EnableFillOverlayEffect](./enablefilloverlayeffect/)() override | फ़िल ओवरले प्रभाव को सक्रिय करता है। |
| void [EnableGlowEffect](./enablegloweffect/)() override | ग्लो प्रभाव को सक्रिय करता है। |
| void [EnableInnerShadowEffect](./enableinnershadoweffect/)() override | आंतरिक शेडो प्रभाव को सक्रिय करता है। |
| void [EnableOuterShadowEffect](./enableoutershadoweffect/)() override | बाह्य शेडो प्रभाव को सक्रिय करता है। |
| void [EnablePresetShadowEffect](./enablepresetshadoweffect/)() override | प्रीसेट शेडो प्रभाव को सक्रिय करता है। |
| void [EnableReflectionEffect](./enablereflectioneffect/)() override | रिफ्लेक्शन प्रभाव को सक्रिय करता है। |
| void [EnableSoftEdgeEffect](./enablesoftedgeeffect/)() override | सॉफ्ट एज प्रभाव को सक्रिय करता है। |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिमैंटिक के अनुसार करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\> [get_BlurEffect](./get_blureffect/)() override | ब्लर प्रभाव। पढ़ें [Effects::IBlur](../../aspose.slides.effects/iblur/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() override | फ़िल ओवरले प्रभाव। पढ़ें [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\> [get_GlowEffect](./get_gloweffect/)() override | ग्लो प्रभाव। पढ़ें [Effects::IGlow](../../aspose.slides.effects/iglow/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() override | आंतरिक शेडो। पढ़ें [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)। |
| **bool** [get_IsNoEffects](./get_isnoeffects/)() override | यदि सभी प्रभाव निष्क्रिय हैं तो true लौटाता है (जैसे अभी बनाया गया, डिफ़ॉल्ट [EffectFormat](./) ऑब्जेक्ट)। केवल-पढ़ने योग्य **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() override | बाह्य शेडो। पढ़ें [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IDOMObject](../idomobject/)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | पैरेंट [IPresentationComponent](../ipresentationcomponent/) लौटाता है। केवल-पढ़ने योग्य [IPresentationComponent](../ipresentationcomponent/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() override | प्रीसेट शेडो। पढ़ें [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\> [get_ReflectionEffect](./get_reflectioneffect/)() override | रिफ्लेक्शन। पढ़ें [Effects::IReflection](../../aspose.slides.effects/ireflection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() override | सॉफ्ट एज। पढ़ें [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [GetEffective](./geteffective/)() override | इनहेरिटेंस लागू करते हुए प्रभाव फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | हैश कोड लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना करता है वैल्यू टाइप ऑब्जेक्ट को nullptr से। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) की स्पेशलाइजेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग केस के लिए स्पेशलाइजेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_BlurEffect](./set_blureffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\>) override | ब्लर प्रभाव। लिखें [Effects::IBlur](../../aspose.slides.effects/iblur/)। |
| void [set_FillOverlayEffect](./set_filloverlayeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\>) override | फ़िल ओवरले प्रभाव। लिखें [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)। |
| void [set_GlowEffect](./set_gloweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\>) override | ग्लो प्रभाव। लिखें [Effects::IGlow](../../aspose.slides.effects/iglow/)। |
| void [set_InnerShadowEffect](./set_innershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\>) override | आंतरिक शेडो। लिखें [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)। |
| void [set_OuterShadowEffect](./set_outershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\>) override | बाह्य शेडो। लिखें [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)। |
| void [set_PresetShadowEffect](./set_presetshadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\>) override | प्रीसेट शेडो। लिखें [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)। |
| void [set_ReflectionEffect](./set_reflectioneffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\>) override | रिफ्लेक्शन। लिखें [Effects::IReflection](../../aspose.slides.effects/ireflection/)। |
| void [set_SoftEdgeEffect](./set_softedgeeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\>) override | सॉफ्ट एज। लिखें [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)। |
| void [SetBlurEffect](./setblureffect/)(**double**, **bool**) override | ब्लर प्रभाव सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को एक weak पॉइंटर सेट करता है (shared के बजाय)। कंटेनरों में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं होना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं होना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को इम्प्लीमेंट करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वी़क रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं होना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वी़क रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं होना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## देखें भी

* क्लास [PVIObject](../pviobject/)
* क्लास [IEffectFormat](../ieffectformat/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)