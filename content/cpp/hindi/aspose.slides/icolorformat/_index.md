---
title: IColorFormat
second_title: Aspose.Slides for C++ API संदर्भ
description: एक प्रस्तुति में उपयोग किए जाने वाले रंग का प्रतिनिधित्व करता है।
type: docs
weight: 1691
url: /hi/aspose.slides/icolorformat/
---
## IColorFormat वर्ग

एक प्रस्तुति में उपयोग किए जाने वाले रंग का प्रतिनिधित्व करता है।

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | \"color\" से रंग स्वरूप की नकल करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में संदर्भ प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में मान प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual **uint8_t** [get_B](./get_b/)() | रंग के नीले घटक को लौटाता है। सभी रंग रूपांतरणों को अनदेखा किया जाता है। पढ़ें **uint8_t**। |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | सभी रंग रूपांतरण लागू होने के साथ परिणामी रंग लौटाता है। RGB रंग सेट करता है और सभी रंग रूपांतरण को साफ़ करता है। पढ़ें [System::Drawing::Color](../../system.drawing/color/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | निर्दिष्ट अनुक्रमांक पर लागू रंग रूपांतरण कार्य को लौटाता है। पढ़ें/लिखें [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | रंग पर लागू सभी रंग रूपांतरणों का संग्रह लौटाता है। केवल पढ़ने योग्य [IColorOperationCollection](../icoloroperationcollection/)। |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | रंग परिभाषा विधि को लौटाता है। पढ़ें [Slides::ColorType](../colortype/)। |
| virtual **float** [get_FloatB](./get_floatb/)() | रंग के नीले घटक को लौटाता है। सभी रंग रूपांतरणों को अनदेखा किया जाता है। पढ़ें **float**। |
| virtual **float** [get_FloatG](./get_floatg/)() | रंग के हरे घटक को लौटाता है। सभी रंग रूपांतरणों को अनदेखा किया जाता है। पढ़ें **float**। |
| virtual **float** [get_FloatR](./get_floatr/)() | रंग के लाल घटक को लौटाता है। सभी रंग रूपांतरणों को अनदेखा किया जाता है। पढ़ें **float**। |
| virtual **uint8_t** [get_G](./get_g/)() | रंग के हरे घटक को लौटाता है। सभी रंग रूपांतरणों को अनदेखा किया जाता है। पढ़ें **uint8_t**। |
| virtual **float** [get_Hue](./get_hue/)() | HSL प्रतिनिधित्व में रंग के hue घटक को लौटाता है। सभी रंग रूपांतरणों को अनदेखा किया जाता है। पढ़ें **float**। |
| virtual **float** [get_Luminance](./get_luminance/)() | HSL प्रतिनिधित्व में रंग की luminance घटक को लौटाता है। सभी रंग रूपांतरणों को अनदेखा किया जाता है। पढ़ें **float**। |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | रंग प्रीसेट को लौटाता है। पढ़ें [Slides::PresetColor](../presetcolor/)। |
| virtual **uint8_t** [get_R](./get_r/)() | रंग के लाल घटक को लौटाता है। सभी रंग रूपांतरणों को अनदेखा किया जाता है। पढ़ें **uint8_t**। |
| virtual **float** [get_Saturation](./get_saturation/)() | HSL प्रतिनिधित्व में रंग के saturation घटक को लौटाता है। सभी रंग रूपांतरणों को अनदेखा किया जाता है। पढ़ें **float**। |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | रंग योजना द्वारा पहचाने गए रंग को लौटाता है। पढ़ें [Slides::SchemeColor](../schemecolor/)। |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | सिस्टम रंग तालिका द्वारा पहचाने गए रंग को लौटाता है। पढ़ें [Slides::SystemColor](../systemcolor/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी संदर्भ काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) विधि का समकक्ष। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) विधि का समकक्ष। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासों की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासों की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की संदर्भ द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की संदर्भ द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रिफ़रेंस के साथ मान प्रकार ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशिष्टकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशिष्टकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा संदर्भ काउंटर को घटाता है। |
| virtual void [set_B](./set_b/)(**uint8_t**) | रंग के नीले घटक को सेट करता है। सभी रंग रूपांतरणों को अनदेखा किया जाता है। लिखें **uint8_t**। |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | सभी रंग रूपांतरण लागू होने के साथ परिणामी रंग लौटाता है। RGB रंग सेट करता है और सभी रंग रूपांतरण को साफ़ करता है। लिखें [System::Drawing::Color](../../system.drawing/color/)। |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | निर्दिष्ट अनुक्रमांक पर लागू रंग रूपांतरण कार्य को सेट करता है। पढ़ें/लिखें [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | रंग परिभाषा विधि को सेट करता है। लिखें [Slides::ColorType](../colortype/)। |
| virtual void [set_FloatB](./set_floatb/)(**float**) | रंग के नीले घटक को सेट करता है। सभी रंग रूपांतरणों को अनदेखा किया जाता है। लिखें **float**। |
| virtual void [set_FloatG](./set_floatg/)(**float**) | रंग के हरे घटक को सेट करता है। सभी रंग रूपांतरणों को अनदेखा किया जाता है। लिखें **float**। |
| virtual void [set_FloatR](./set_floatr/)(**float**) | रंग के लाल घटक को सेट करता है। सभी रंग रूपांतरणों को अनदेखा किया जाता है। लिखें **float**। |
| virtual void [set_G](./set_g/)(**uint8_t**) | रंग के हरे घटक को सेट करता है। सभी रंग रूपांतरणों को अनदेखा किया जाता है। लिखें **uint8_t**। |
| virtual void [set_Hue](./set_hue/)(**float**) | HSL प्रतिनिधित्व में रंग के hue घटक को सेट करता है। सभी रंग रूपांतरणों को अनदेखा किया जाता है। लिखें **float**। |
| virtual void [set_Luminance](./set_luminance/)(**float**) | HSL प्रतिनिधित्व में रंग की luminance घटक को सेट करता है। सभी रंग रूपांतरणों को अनदेखा किया जाता है। लिखें **float**। |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | रंग प्रीसेट को सेट करता है। लिखें [Slides::PresetColor](../presetcolor/)। |
| virtual void [set_R](./set_r/)(**uint8_t**) | रंग के लाल घटक को सेट करता है। सभी रंग रूपांतरणों को अनदेखा किया जाता है। लिखें **uint8_t**। |
| virtual void [set_Saturation](./set_saturation/)(**float**) | HSL प्रतिनिधित्व में रंग के saturation घटक को सेट करता है। सभी रंग रूपांतरणों को अनदेखा किया जाता है। लिखें **float**। |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | रंग योजना द्वारा पहचाने गए रंग को सेट करता है। लिखें [Slides::SchemeColor](../schemecolor/)। |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | सिस्टम रंग तालिका द्वारा पहचाने गए रंग को सेट करता है। लिखें [Slides::SystemColor](../systemcolor/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्युमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा संदर्भ काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा संदर्भ काउंटर को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा संदर्भ काउंटर को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | वर्तमान रंग स्वरूप का प्रतिनिधित्व करने वाला [System::String](../../system/string/) लौटाता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) विधि का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन का अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak संदर्भ काउंटर को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak संदर्भ काउंटर को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* वर्ग [IFillParamSource](../ifillparamsource/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)