---
title: IEffectFormat
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: आकार के प्रभाव गुणों का प्रतिनिधित्व करता है।
type: docs
weight: 2029
url: /hi/aspose.slides/ieffectformat/
---
## IEffectFormat वर्ग


आकार के प्रभाव गुणों का प्रतिनिधित्व करता है।

```cpp
class IEffectFormat : public Aspose::Slides::IEffectParamSource
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual void [DisableBlurEffect](./disableblureffect/)() | ब्लर प्रभाव को निष्क्रिय करता है। |
| virtual void [DisableFillOverlayEffect](./disablefilloverlayeffect/)() | फ़िल ओवरले प्रभाव को निष्क्रिय करता है। |
| virtual void [DisableGlowEffect](./disablegloweffect/)() | ग्लो प्रभाव को निष्क्रिय करता है। |
| virtual void [DisableInnerShadowEffect](./disableinnershadoweffect/)() | इनर शैडो प्रभाव को निष्क्रिय करता है। |
| virtual void [DisableOuterShadowEffect](./disableoutershadoweffect/)() | आउटर शैडो प्रभाव को निष्क्रिय करता है। |
| virtual void [DisablePresetShadowEffect](./disablepresetshadoweffect/)() | प्रीसेट शैडो प्रभाव को निष्क्रिय करता है। |
| virtual void [DisableReflectionEffect](./disablereflectioneffect/)() | रिफ्लेक्शन प्रभाव को निष्क्रिय करता है। |
| virtual void [DisableSoftEdgeEffect](./disablesoftedgeeffect/)() | सॉफ़्ट एज प्रभाव को निष्क्रिय करता है। |
| virtual void [EnableFillOverlayEffect](./enablefilloverlayeffect/)() | फ़िल ओवरले प्रभाव को सक्रिय करता है। |
| virtual void [EnableGlowEffect](./enablegloweffect/)() | ग्लो प्रभाव को सक्रिय करता है। |
| virtual void [EnableInnerShadowEffect](./enableinnershadoweffect/)() | इनर शैडो प्रभाव को सक्रिय करता है। |
| virtual void [EnableOuterShadowEffect](./enableoutershadoweffect/)() | आउटर शैडो प्रभाव को सक्रिय करता है। |
| virtual void [EnablePresetShadowEffect](./enablepresetshadoweffect/)() | प्रीसेट शैडो प्रभाव को सक्रिय करता है। |
| virtual void [EnableReflectionEffect](./enablereflectioneffect/)() | रिफ्लेक्शन प्रभाव को सक्रिय करता है। |
| virtual void [EnableSoftEdgeEffect](./enablesoftedgeeffect/)() | सॉफ़्ट एज प्रभाव को सक्रिय करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) विश्लेषण का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\> [get_BlurEffect](./get_blureffect/)() | ब्लर प्रभाव। पढ़ें [Effects::IBlur](../../aspose.slides.effects/iblur/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() | फ़िल ओवरले प्रभाव। पढ़ें [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\> [get_GlowEffect](./get_gloweffect/)() | ग्लो प्रभाव। पढ़ें [Effects::IGlow](../../aspose.slides.effects/iglow/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() | इनर शैडो। पढ़ें [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)। |
| virtual **bool** [get_IsNoEffects](./get_isnoeffects/)() | यदि सभी प्रभाव निष्क्रिय हैं (जैसे अभी बनाया गया, डिफ़ॉल्ट [EffectFormat](../effectformat/) वस्तु) तो true लौटाता है। केवल-पढ़ने योग्य **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() | आउटर शैडो। पढ़ें [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() | प्रीसेट शैडो। पढ़ें [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\> [get_ReflectionEffect](./get_reflectioneffect/)() | रिफ्लेक्शन। पढ़ें [Effects::IReflection](../../aspose.slides.effects/ireflection/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() | सॉफ़्ट एज। पढ़ें [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [GetEffective](./geteffective/)() | इनहेरिटेंस लागू होकर प्रभाव फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समान। कस्टम वस्तुओं की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि वस्तु लक्ष्य प्रकार द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समान। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, सिर्फ नया ऑब्जेक्ट आरंभ करता है और सब-क्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, सिर्फ नया ऑब्जेक्ट आरंभ करता है और सब-क्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार की वस्तु की nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_BlurEffect](./set_blureffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\>) | ब्लर प्रभाव। लिखें [Effects::IBlur](../../aspose.slides.effects/iblur/)। |
| virtual void [set_FillOverlayEffect](./set_filloverlayeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\>) | फ़िल ओवरले प्रभाव। लिखें [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)। |
| virtual void [set_GlowEffect](./set_gloweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\>) | ग्लो प्रभाव। लिखें [Effects::IGlow](../../aspose.slides.effects/iglow/)। |
| virtual void [set_InnerShadowEffect](./set_innershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\>) | इनर शैडो। लिखें [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)। |
| virtual void [set_OuterShadowEffect](./set_outershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\>) | आउटर शैडो। लिखें [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)। |
| virtual void [set_PresetShadowEffect](./set_presetshadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\>) | प्रीसेट शैडो। लिखें [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)। |
| virtual void [set_ReflectionEffect](./set_reflectioneffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\>) | रिफ्लेक्शन। लिखें [Effects::IReflection](../../aspose.slides.effects/ireflection/)। |
| virtual void [set_SoftEdgeEffect](./set_softedgeeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\>) | सॉफ़्ट एज। लिखें [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)। |
| virtual void [SetBlurEffect](./setblureffect/)(**double**, **bool**) | ब्लर प्रभाव सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को वैक पॉइंटर (शेर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर को वैक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान साझा रेफ़रेंस काउंटर मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का प्रयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का प्रयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समान। कस्टम वस्तुओं को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन को अन-लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वैक रेफ़रेंस काउंट बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का प्रयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वैक रेफ़रेंस काउंट घटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का प्रयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## संबंधित देखें

* वर्ग [IEffectParamSource](../ieffectparamsource/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)