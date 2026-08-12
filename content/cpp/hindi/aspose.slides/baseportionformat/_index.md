---
title: BasePortionFormat
second_title: Aspose.Slides for C++ API संदर्भ
description: सामान्य टेक्स्ट भाग फॉर्मेटिंग प्रॉपर्टीज़।
type: docs
weight: 144
url: /hi/aspose.slides/baseportionformat/
---
## BasePortionFormat क्लास


सामान्य टेक्स्ट भाग फॉर्मेटिंग प्रॉपर्टीज़।

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## विधियां

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्दिष्ट वस्तु के साथ तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | वैकल्पिक भाषा का Id वापस करता है। पढ़ें [System::String](../../system/string/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी वापस करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से प्राप्त किया जाना चाहिए। पढ़ें [IFontData](../ifontdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | ईस्ट एशियन फ़ॉन्ट जानकारी वापस करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से प्राप्त किया जाना चाहिए। पढ़ें [IFontData](../ifontdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | टेक्स्ट [EffectFormat](../effectformat/) गुण वापस करता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| **float** [get_Escapement](./get_escapement/)() override | सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट वापस करता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अपरिभाषित है और इसे मास्टर से प्राप्त किया जाना चाहिए। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | टेक्स्ट [FillFormat](../fillformat/) गुण वापस करता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत लागू नहीं होती। पढ़ें [NullableBool](../nullablebool/)। |
| **float** [get_FontHeight](./get_fontheight/)() override | एक भाग का फ़ॉन्ट ऊँचाई वापस करता है। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है ऊँचाई अपरिभाषित है और इसे मास्टर से प्राप्त किया जाना चाहिए। पढ़ें **float**। |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। कोई विरासत लागू नहीं होती। पढ़ें [NullableBool](../nullablebool/)। |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | टेक्स्ट अंडरलाइन प्रकार वापस करता है। कोई विरासत लागू नहीं होती। पढ़ें [TextUnderlineType](../textunderlinetype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | टेक्स्ट को हाइलाइट करने के लिए उपयोग किया गया रंग वापस करता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [IColorFormat](../icolorformat/)। |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | निर्धारित करता है कि अंडरलाइन शैली की अपनी [FillFormat](../fillformat/) विशेषताएँ हैं या वह टेक्स्ट के [FillFormat](../fillformat/) विशेषताओं से विरासत में प्राप्त करती है। पढ़ें [NullableBool](../nullablebool/)। |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | निर्धारित करता है कि अंडरलाइन शैली की अपनी [LineFormat](../lineformat/) विशेषताएँ हैं या वह टेक्स्ट के [LineFormat](../lineformat/) विशेषताओं से विरासत में प्राप्त करती है। पढ़ें [NullableBool](../nullablebool/)। |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | न्यूनतम फ़ॉन्ट आकार वापस करता है, जिसके लिए करनिंग सक्रिय होनी चाहिए। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अपरिभाषित है और इसे मास्टर से प्राप्त किया जाना चाहिए। पढ़ें **float**। |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | निर्धारित करता है कि संख्याएँ टेक्स्ट के पूर्वी-भाषा-विशिष्ट ऊर्ध्वाधर लेआउट को नजरअंदाज करें। कोई विरासत लागू नहीं होती। पढ़ें [NullableBool](../nullablebool/)। |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | प्रूफ़िंग भाषा का Id वापस करता है। वर्तनी और व्याकरण जांचने के लिए उपयोग किया जाता है। पढ़ें [System::String](../../system/string/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | लैटिन फ़ॉन्ट जानकारी वापस करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से प्राप्त किया जाना चाहिए। पढ़ें [IFontData](../ifontdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | टेक्स्ट आउटलाइनिंग के लिए [LineFormat](../lineformat/) गुण वापस करता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | निर्धारित करता है कि टेक्स्ट की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं होती। पढ़ें [NullableBool](../nullablebool/)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate ऑब्जेक्ट वापस करता है। केवल-पढ़ने योग्य [IDOMObject](../idomobject/)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | पैरेंट [IPresentationComponent](../ipresentationcomponent/) वापस करता है। केवल-पढ़ने योग्य [IPresentationComponent](../ipresentationcomponent/)। |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | निर्धारित करता है कि टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए। कोई विरासत लागू नहीं होती। पढ़ें [NullableBool](../nullablebool/)। |
| **float** [get_Spacing](./get_spacing/)() override | अक्षर-अक्षर अंतर वृद्धि वापस करता है। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अपरिभाषित है और इसे मास्टर से प्राप्त किया जाना चाहिए। पढ़ें **float**। |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | प्राप्त करता है कि क्या टेक्स्ट भाग के लिए स्पेल-चेकिंग सक्षम है। जब यह प्रॉपर्टी false पर सेट होती है, तो टेक्स्ट तत्वों के लिए वर्तनी जाँच दमन की जाती है। जब true पर सेट होती है, तो स्पेल-चेकिंग अनुमति देती है। डिफ़ॉल्ट मान **false** है। |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | टेक्स्ट का स्ट्राइकथ्रू प्रकार वापस करता है। कोई विरासत लागू नहीं होती। पढ़ें [TextStrikethroughType](../textstrikethroughtype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | प्रतीकात्मक फ़ॉन्ट जानकारी वापस करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से प्राप्त किया जाना चाहिए। पढ़ें [IFontData](../ifontdata/)। |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | टेक्स्ट कैपिटलाइज़ेशन प्रकार वापस करता है। कोई विरासत लागू नहीं होती। पढ़ें [Slides::TextCapType](../textcaptype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | अंडरलाइन लाइन [FillFormat](../fillformat/) गुण वापस करता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | अंडरलाइन लाइन को आउटलाइन करने के लिए उपयोग किए गए [LineFormat](../lineformat/) गुण वापस करता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | हैश कोड वापस करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट प्रयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | मूल‍्य प्रकार के ऑब्जेक्ट को nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | वैकल्पिक भाषा का Id सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से प्राप्त किया जाना चाहिए। लिखें [IFontData](../ifontdata/)। |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | ईस्ट एशियन फ़ॉन्ट जानकारी सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से प्राप्त किया जाना चाहिए। लिखें [IFontData](../ifontdata/)। |
| void [set_Escapement](./set_escapement/)(**float**) override | सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट सेट करता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अपरिभाषित है और इसे मास्टर से प्राप्त किया जाना चाहिए। लिखें **float**। |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत लागू नहीं होती। लिखें [NullableBool](../nullablebool/)। |
| void [set_FontHeight](./set_fontheight/)(**float**) override | एक भाग का फ़ॉन्ट ऊँचाई सेट करता है। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है ऊँचाई अपरिभाषित है और इसे मास्टर से प्राप्त किया जाना चाहिए। लिखें **float**। |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। कोई विरासत लागू नहीं होती। लिखें [NullableBool](../nullablebool/)। |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | टेक्स्ट अंडरलाइन प्रकार सेट करता है। कोई विरासत लागू नहीं होती। लिखें [TextUnderlineType](../textunderlinetype/)। |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि अंडरलाइन शैली की अपनी [FillFormat](../fillformat/) विशेषताएँ हैं या वह टेक्स्ट के [FillFormat](../fillformat/) विशेषताओं से विरासत में प्राप्त करती है। लिखें [NullableBool](../nullablebool/)। |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि अंडरलाइन शैली की अपनी [LineFormat](../lineformat/) विशेषताएँ हैं या वह टेक्स्ट के [LineFormat](../lineformat/) विशेषताओं से विरासत में प्राप्त करती है। लिखें [NullableBool](../nullablebool/)। |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | न्यूनतम फ़ॉन्ट आकार सेट करता है, जिसके लिए करनिंग सक्रिय होनी चाहिए। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अपरिभाषित है और इसे मास्टर से प्राप्त किया जाना चाहिए। लिखें **float**। |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि संख्याएँ टेक्स्ट के पूर्वी-भाषा-विशिष्ट ऊर्ध्वाधर लेआउट को नजरअंदाज करें। कोई विरासत लागू नहीं होती। लिखें [NullableBool](../nullablebool/)। |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | प्रूफ़िंग भाषा का Id सेट करता है। वर्तनी और व्याकरण जांचने के लिए उपयोग किया जाता है। लिखें [System::String](../../system/string/)। |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | लैटिन फ़ॉन्ट जानकारी सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से प्राप्त किया जाना चाहिए। लिखें [IFontData](../ifontdata/)। |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि टेक्स्ट की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं होती। लिखें [NullableBool](../nullablebool/)। |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए। कोई विरासत लागू नहीं होती। लिखें [NullableBool](../nullablebool/)। |
| void [set_Spacing](./set_spacing/)(**float**) override | अक्षर-अक्षर अंतर वृद्धि सेट करता है। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अपरिभाषित है और इसे मास्टर से प्राप्त किया जाना चाहिए। लिखें **float**। |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | टेक्स्ट भाग के लिए स्पेल-चेकिंग सक्षम होने का मान सेट करता है। जब यह प्रॉपर्टी false पर सेट होती है, तो टेक्स्ट तत्वों के लिए वर्तनी जाँच दमन की जाती है। जब true पर सेट होती है, तो स्पेल-चेकिंग अनुमति देती है। डिफ़ॉल्ट मान **false** है। |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | टेक्स्ट का स्ट्राइकथ्रू प्रकार सेट करता है। कोई विरासत लागू नहीं होती। लिखें [TextStrikethroughType](../textstrikethroughtype/)। |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | प्रतीकात्मक फ़ॉन्ट जानकारी सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से प्राप्त किया जाना चाहिए। लिखें [IFontData](../ifontdata/)। |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | टेक्स्ट कैपिटलाइज़ेशन प्रकार सेट करता है। कोई विरासत लागू नहीं होती। लिखें [Slides::TextCapType](../textcaptype/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वाँ टेम्पलेट आर्ग्यूमेंट एक कमजोर पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और वापस करता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट प्रयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट बढ़ाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट घटाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर मुक्त करता है। |
## संबंधित देखें

* क्लास [PVIObject](../pviobject/)
* क्लास [IBasePortionFormat](../ibaseportionformat/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)