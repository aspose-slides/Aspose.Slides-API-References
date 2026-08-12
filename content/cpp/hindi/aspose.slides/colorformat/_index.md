---
title: ColorFormat
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रस्तुति में उपयोग किए जाने वाले रंग का प्रतिनिधित्व करता है।
type: docs
weight: 339
url: /hi/aspose.slides/colorformat/
---
## ColorFormat क्लास

एक प्रस्तुति में उपयोग किए जाने वाले रंग का प्रतिनिधित्व करता है।

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## विधियाँ

| विधि | वर्णन |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | \"color\" से रंग स्वरूप की प्रतिलिपि बनाता है। |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्दिष्ट ऑब्जेक्ट के साथ समानता की जाँच करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-style फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान (NaN सहित) के बराबर नहीं है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-style फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान (NaN सहित) के बराबर नहीं है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **uint8_t** [get_B](./get_b/)() override | एक रंग का नीला घटक लौटाता है। सभी रंग रूपांतरणों को नजरअंदाज किया जाता है। **uint8_t** पढ़ें। |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | परिणामी रंग लौटाता है (सभी रंग रूपांतरण लागू किए हुए)। RGB रंग सेट करता है और सभी रंग रूपांतरण हटाता है। [System::Drawing::Color](../../system.drawing/color/) पढ़ें। |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर रंग पर लागू रंग रूपांतरण ऑपरेशन लौटाता है। पढ़ें/लिखें [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | एक रंग पर लागू सभी रंग रूपांतरणों का संग्रह लौटाता है। केवल पढ़ने योग्य [IColorOperationCollection](../icoloroperationcollection/)। |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | रंग परिभाषा विधि लौटाता है। [Slides::ColorType](../colortype/) पढ़ें। |
| **float** [get_FloatB](./get_floatb/)() override | एक रंग का नीला घटक लौटाता है। सभी रंग रूपांतरणों को नजरअंदाज किया जाता है। **float** पढ़ें। |
| **float** [get_FloatG](./get_floatg/)() override | एक रंग का हरा घटक लौटाता है। सभी रंग रूपांतरणों को नजरअंदाज किया जाता है। **float** पढ़ें। |
| **float** [get_FloatR](./get_floatr/)() override | एक रंग का लाल घटक लौटाता है। सभी रंग रूपांतरणों को नजरअंदाज किया जाता है। **float** पढ़ें। |
| **uint8_t** [get_G](./get_g/)() override | एक रंग का हरा घटक लौटाता है। सभी रंग रूपांतरणों को नजरअंदाज किया जाता है। |
| **float** [get_Hue](./get_hue/)() override | HSL प्रतिनिधित्व में रंग का ह्यू घटक लौटाता है। सभी रंग रूपांतरणों को नजरअंदाज किया जाता है। **float** पढ़ें। |
| **float** [get_Luminance](./get_luminance/)() override | HSL प्रतिनिधित्व में रंग की चमक (luminance) घटक लौटाता है। सभी रंग रूपांतरणों को नजरअंदाज किया जाता है। **float** पढ़ें। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [IDOMObject](../idomobject/)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | पैरेंट [IPresentationComponent](../ipresentationcomponent/) लौटाता है। केवल पढ़ने योग्य [IPresentationComponent](../ipresentationcomponent/)। |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | रंग प्रीसेट लौटाता है। [Slides::PresetColor](../presetcolor/) पढ़ें। |
| **uint8_t** [get_R](./get_r/)() override | एक रंग का लाल घटक लौटाता है। सभी रंग रूपांतरणों को नजरअंदाज किया जाता है। **uint8_t** पढ़ें। |
| **float** [get_Saturation](./get_saturation/)() override | HSL प्रतिनिधित्व में रंग की संतृप्ति (saturation) घटक लौटाता है। सभी रंग रूपांतरणों को नजरअंदाज किया जाता है। **float** पढ़ें। |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | एक रंग योजना द्वारा पहचाने गए रंग को लौटाता है। [Slides::SchemeColor](../schemecolor/) पढ़ें। |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | सिस्टम कलर टेबल द्वारा पहचाने गए रंग को लौटाता है। [Slides::SystemColor](../systemcolor/) पढ़ें। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| **int32_t** [GetHashCode](./gethashcode/)() const override | हैश कोड लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँच करता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंत्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट आरंभ करता है और सबक्लासेज़ के कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट आरंभ करता है और सबक्लासेज़ के कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_B](./set_b/)(**uint8_t**) override | एक रंग का नीला घटक सेट करता है। सभी रंग रूपांतरणों को नजरअंदाज किया जाता है। **uint8_t** लिखें। |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | परिणामी रंग लौटाता है (सभी रंग रूपांतरण लागू किए हुए)। RGB रंग सेट करता है और सभी रंग रूपांतरण हटाता है। [System::Drawing::Color](../../system.drawing/color/) लिखें। |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | निर्दिष्ट इंडेक्स पर रंग पर लागू रंग रूपांतरण ऑपरेशन सेट करता है। पढ़ें/लिखें [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | रंग परिभाषा विधि सेट करता है। [Slides::ColorType](../colortype/) लिखें। |
| void [set_FloatB](./set_floatb/)(**float**) override | एक रंग का नीला घटक सेट करता है। सभी रंग रूपांतरणों को नजरअंदाज किया जाता है। **float** लिखें। |
| void [set_FloatG](./set_floatg/)(**float**) override | एक रंग का हरा घटक सेट करता है। सभी रंग रूपांतरणों को नजरअंदाज किया जाता है। **float** लिखें। |
| void [set_FloatR](./set_floatr/)(**float**) override | एक रंग का लाल घटक सेट करता है। सभी रंग रूपांतरणों को नजरअंदाज किया जाता है। **float** लिखें। |
| void [set_G](./set_g/)(**uint8_t**) override | एक रंग का हरा घटक सेट करता है। सभी रंग रूपांतरणों को नजरअंदाज किया जाता है। |
| void [set_Hue](./set_hue/)(**float**) override | HSL प्रतिनिधित्व में रंग का ह्यू घटक सेट करता है। सभी रंग रूपांतरणों को नजरअंदाज किया जाता है। **float** लिखें। |
| void [set_Luminance](./set_luminance/)(**float**) override | HSL प्रतिनिधित्व में रंग की चमक (luminance) घटक सेट करता है। सभी रंग रूपांतरणों को नजरअंदाज किया जाता है। **float** लिखें। |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | रंग प्रीसेट सेट करता है। [Slides::PresetColor](../presetcolor/) लिखें। |
| void [set_R](./set_r/)(**uint8_t**) override | एक रंग का लाल घटक सेट करता है। सभी रंग रूपांतरणों को नजरअंदाज किया जाता है। **uint8_t** लिखें। |
| void [set_Saturation](./set_saturation/)(**float**) override | HSL प्रतिनिधित्व में रंग की संतृप्ति घटक सेट करता है। सभी रंग रूपांतरणों को नजरअंदाज किया जाता है। **float** लिखें। |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | एक रंग योजना द्वारा पहचाने गए रंग को सेट करता है। [Slides::SchemeColor](../schemecolor/) लिखें। |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | सिस्टम कलर टेबल द्वारा पहचाने गए रंग को सेट करता है। [Slides::SystemColor](../systemcolor/) लिखें। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को weak पॉइंटर (shared नहीं) सेट करता है। कंटेनर्स में पॉइंटर्स को weak मोड में बदलने को सक्षम करता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान साझा रेफ़रेंस काउंटर मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | वर्तमान रंग स्वरूप का प्रतिनिधित्व करने वाला [System::String](../../system/string/) लौटाता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंत्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संबंधित देखें

* क्लास [PVIObject](../pviobject/)
* क्लास [IColorFormat](../icolorformat/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)