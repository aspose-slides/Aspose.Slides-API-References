---
title: IOverrideTheme
second_title: Aspose.Slides for C++ API संदर्भ
description: एक ओवरराइडिंग थीम को दर्शाता है।
type: docs
weight: 391
url: /hi/aspose.slides.theme/ioverridetheme/
---
## IOverrideTheme क्लास

एक ओवरराइडिंग थीम को दर्शाता है।

```cpp
class IOverrideTheme : public virtual Aspose::Slides::Theme::ITheme
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual void [Clear](./clear/)() | [ColorScheme](../colorscheme/), [FontScheme](../fontscheme/), [FormatScheme](../formatscheme/) को null सेट करें ताकि इस थीम ऑब्जेक्ट के साथ कोई ओवरराइडिंग निष्क्रिय हो जाए। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ColorFormat](../itheme/get_colorformat/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\> [get_ColorScheme](../itheme/get_colorscheme/)() | कलर स्कीम लौटाता है। केवल-पढ़ने योग्य [IColorScheme](../icolorscheme/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\> [get_FontScheme](../itheme/get_fontscheme/)() | फ़ॉन्ट स्कीम लौटाता है। केवल-पढ़ने योग्य [IFontScheme](../ifontscheme/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\> [get_FormatScheme](../itheme/get_formatscheme/)() | शेप फ़ॉर्मेट स्कीम लौटाता है। केवल-पढ़ने योग्य [IFormatScheme](../iformatscheme/)। |
| virtual **bool** [get_IsEmpty](./get_isempty/)() | सही मूल्य का अर्थ है कि [ColorScheme](../colorscheme/), [FontScheme](../fontscheme/), [FormatScheme](../formatscheme/) null है और इस थीम ऑब्जेक्ट के साथ कोई ओवरराइडिंग निष्क्रिय है। केवल-पढ़ने योग्य **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | प्रेज़ेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../aspose.slides/ipresentation/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../ithemeeffectivedata/)\> [GetEffective](../itheme/geteffective/)() | इनहेरिटेंस लागू किए हुए प्रभावी थीम डेटा प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual void [InitColorScheme](./initcolorscheme/)() | InheritedTheme के [ColorScheme](../colorscheme/) को ओवरराइड करने के लिए नए ऑब्जेक्ट के साथ [ColorScheme](../colorscheme/) को इनिशियलाइज़ करें। |
| virtual void [InitColorSchemeFrom](./initcolorschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\>) | InheritedTheme के [ColorScheme](../colorscheme/) को ओवरराइड करने के लिए नए ऑब्जेक्ट के साथ [ColorScheme](../colorscheme/) को इनिशियलाइज़ करें। |
| virtual void [InitColorSchemeFromInherited](./initcolorschemefrominherited/)() | InheritedTheme के [ColorScheme](../colorscheme/) को ओवरराइड करने के लिए नए ऑब्जेक्ट के साथ [ColorScheme](../colorscheme/) को इनिशियलाइज़ करें। और इस नए ऑब्जेक्ट के डेटा को InheritedTheme के [ColorScheme](../colorscheme/) के डेटा से इनिशियलाइज़ करें। |
| virtual void [InitFontScheme](./initfontscheme/)() | InheritedTheme के [FontScheme](../fontscheme/) को ओवरराइड करने के लिए नए ऑब्जेक्ट के साथ [FontScheme](../fontscheme/) को इनिशियलाइज़ करें। |
| virtual void [InitFontSchemeFrom](./initfontschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\>) | InheritedTheme के [FontScheme](../fontscheme/) को ओवरराइड करने के लिए नए ऑब्जेक्ट के साथ [FontScheme](../fontscheme/) को इनिशियलाइज़ करें। |
| virtual void [InitFontSchemeFromInherited](./initfontschemefrominherited/)() | InheritedTheme के [FontScheme](../fontscheme/) को ओवरराइड करने के लिए नए ऑब्जेक्ट के साथ [FontScheme](../fontscheme/) को इनिशियलाइज़ करें। और इस नए ऑब्जेक्ट के डेटा को InheritedTheme के [FontScheme](../fontscheme/) के डेटा से इनिशियलाइज़ करें। |
| virtual void [InitFormatScheme](./initformatscheme/)() | InheritedTheme के [FormatScheme](../formatscheme/) को ओवरराइड करने के लिए नए ऑब्जेक्ट के साथ [FormatScheme](../formatscheme/) को इनिशियलाइज़ करें। |
| virtual void [InitFormatSchemeFrom](./initformatschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\>) | InheritedTheme के [FormatScheme](../formatscheme/) को ओवरराइड करने के लिए नए ऑब्जेक्ट के साथ [FormatScheme](../formatscheme/) को इनिशियलाइज़ करें। |
| virtual void [InitFormatSchemeFromInherited](./initformatschemefrominherited/)() | InheritedTheme के [FormatScheme](../formatscheme/) को ओवरराइड करने के लिए नए ऑब्जेक्ट के साथ [FormatScheme](../formatscheme/) को इनिशियलाइज़ करें। और इस नए ऑब्जेक्ट के डेटा को InheritedTheme के [FormatScheme](../formatscheme/) के डेटा से इनिशियलाइज़ करें। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचें कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीरी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर्स को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | string और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा शेयरड रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को एक वीक पॉइंटर सेट करता है (शेयरड के बजाय)। कंटेनर्स में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयरड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयरड रेफ़रेंस काउंट को इन्क्रिमेंट करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयरड रेफ़रेंस काउंट को डिक्रिमेंट करता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में कन्वर्ट करना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीरी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को इन्क्रिमेंट करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को डिक्रिमेंट करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स और ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर्स को मुक्त करता है। |

## संबंधित देखें

* क्लास [ITheme](../itheme/)
* नेमस्पेस [Aspose::Slides::Theme](../)
* लाइब्रेरी [Aspose.Slides](../../)