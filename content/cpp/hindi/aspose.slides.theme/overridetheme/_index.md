---
title: OverrideTheme
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक ओवरराइडिंग थीम का प्रतिनिधित्व करता है।
type: docs
weight: 547
url: /hi/aspose.slides.theme/overridetheme/
---
## OverrideTheme क्लास

एक ओवरराइडिंग थीम का प्रतिनिधित्व करता है।

```cpp
class OverrideTheme : public Aspose::Slides::Theme::Theme,
                      public Aspose::Slides::Theme::IOverrideTheme
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| void [Clear](./clear/)() override | [ColorScheme](../colorscheme/), [FontScheme](../fontscheme/), [FormatScheme](../formatscheme/) को null सेट करें ताकि इस थीम ऑब्जेक्ट के साथ कोई भी ओवरराइडिंग निष्क्रिय हो सके। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ColorFormat](./get_colorformat/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\> [get_ColorScheme](./get_colorscheme/)() override | रंग योजना लौटाता है। केवल पढ़ने योग्य [IColorScheme](../icolorscheme/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\> [get_FontScheme](./get_fontscheme/)() override | फ़ॉन्ट योजना लौटाता है। केवल पढ़ने योग्य [IFontScheme](../ifontscheme/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\> [get_FormatScheme](./get_formatscheme/)() override | शेप फ़ॉर्मेट योजना लौटाता है। केवल पढ़ने योग्य [IFormatScheme](../iformatscheme/)। |
| **bool** [get_IsEmpty](./get_isempty/)() override | सत्य मान का अर्थ है कि [ColorScheme](../colorscheme/), [FontScheme](../fontscheme/), [FormatScheme](../formatscheme/) null हैं और इस थीम ऑब्जेक्ट के साथ कोई भी ओवरराइडिंग निष्क्रिय है। केवल पढ़ने योग्य **bool**। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | पैरेंट [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) लौटाता है। केवल पढ़ने योग्य [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../theme/get_presentation/)() override | पैरेंट प्रेजेंटेशन लौटाता है। केवल पढ़ने योग्य [IPresentation](../../aspose.slides/ipresentation/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../ithemeeffectivedata/)\> [GetEffective](../theme/geteffective/)() override | इनहेरिटेंस लागू होने के साथ प्रभावी थीम डेटा प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| void [InitColorScheme](./initcolorscheme/)() override | InheritedTheme के [ColorScheme](../colorscheme/) को ओवरराइड करने के लिए नए ऑब्जेक्ट के साथ [ColorScheme](../colorscheme/) को इनिशियलाइज़ करें। |
| void [InitColorSchemeFrom](./initcolorschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\>) override | InheritedTheme के [ColorScheme](../colorscheme/) को ओवरराइड करने के लिए नए ऑब्जेक्ट के साथ [ColorScheme](../colorscheme/) को इनिशियलाइज़ करें। |
| void [InitColorSchemeFromInherited](./initcolorschemefrominherited/)() override | InheritedTheme के [ColorScheme](../colorscheme/) को ओवरराइड करने के लिए नए ऑब्जेक्ट के साथ [ColorScheme](../colorscheme/) को इनिशियलाइज़ करें। और इस नए ऑब्जेक्ट का डेटा InheritedTheme के [ColorScheme](../colorscheme/) के डेटा से इनिशियलाइज़ करें। |
| void [InitFontScheme](./initfontscheme/)() override | InheritedTheme के [FontScheme](../fontscheme/) को ओवरराइड करने के लिए नए ऑब्जेक्ट के साथ [FontScheme](../fontscheme/) को इनिशियलाइज़ करें। |
| void [InitFontSchemeFrom](./initfontschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\>) override | InheritedTheme के [FontScheme](../fontscheme/) को ओवरराइड करने के लिए नए ऑब्जेक्ट के साथ [FontScheme](../fontscheme/) को इनिशियलाइज़ करें। |
| void [InitFontSchemeFromInherited](./initfontschemefrominherited/)() override | InheritedTheme के [FontScheme](../fontscheme/) को ओवरराइड करने के लिए नए ऑब्जेक्ट के साथ [FontScheme](../fontscheme/) को इनिशियलाइज़ करें। और इस नए ऑब्जेक्ट का डेटा InheritedTheme के [FontScheme](../fontscheme/) के डेटा से इनिशियलाइज़ करें। |
| void [InitFormatScheme](./initformatscheme/)() override | InheritedTheme के [FormatScheme](../formatscheme/) को ओवरराइड करने के लिए नए ऑब्जेक्ट के साथ [FormatScheme](../formatscheme/) को इनिशियलाइज़ करें। |
| void [InitFormatSchemeFrom](./initformatschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\>) override | InheritedTheme के [FormatScheme](../formatscheme/) को ओवरराइड करने के लिए नए ऑब्जेक्ट के साथ [FormatScheme](../formatscheme/) को इनिशियलाइज़ करें। |
| void [InitFormatSchemeFromInherited](./initformatschemefrominherited/)() override | InheritedTheme के [FormatScheme](../formatscheme/) को ओवरराइड करने के लिए नए ऑब्जेक्ट के साथ [FormatScheme](../formatscheme/) को इनिशियलाइज़ करें। और इस नए ऑब्जेक्ट का डेटा InheritedTheme के [FormatScheme](../formatscheme/) के डेटा से इनिशियलाइज़ करें। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस-तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण, स्ट्रिंग और nullptr के केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण, स्ट्रिंग्स के केस के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कॉन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें भी

* क्लास [Theme](../theme/)
* क्लास [IOverrideTheme](../ioverridetheme/)
* नेमस्पेस [Aspose::Slides::Theme](../)
* लाइब्रेरी [Aspose.Slides](../../)