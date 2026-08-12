---
title: IBasePortionFormat
second_title: Aspose.Slides for C++ API संदर्भ
description: यह क्लास टेक्स्ट पोर्शन फ़ॉर्मेटिंग प्रॉपर्टीज़ को शामिल करती है। IPortionFormatEffectiveData के विपरीत, इस क्लास की सभी प्रॉपर्टीज़ लिखने योग्य हैं।
type: docs
weight: 1457
url: /hi/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat क्लास

यह क्लास टेक्स्ट पोर्शन फ़ॉर्मेटिंग प्रॉपर्टीज़ को शामिल करती है। [IPortionFormatEffectiveData](../iportionformateffectivedata/) के विपरीत, इस क्लास की सभी प्रॉपर्टीज़ लिखने योग्य हैं।

```cpp
class IBasePortionFormat : public virtual System::Object
```

## विधियाँ

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिमेंटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है, फिर भी दो NaN को बराबर मानते हुए C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है, फिर भी दो NaN को बराबर मानते हुए C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | एक वैकल्पिक भाषा की Id लौटाता है। [System::String](../../system/string/) पढ़ें। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी लौटाता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। [IFontData](../ifontdata/) पढ़ें। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | ईस्ट एशियन फ़ॉन्ट जानकारी लौटाता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। [IFontData](../ifontdata/) पढ़ें। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | पाठ [EffectFormat](../effectformat/) प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| virtual **float** [get_Escapement](./get_escapement/)() | सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट लौटाता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक होता है। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। **float** पढ़ें। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | पाठ [FillFormat](../fillformat/) प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत लागू नहीं होती। [NullableBool](../nullablebool/) पढ़ें। |
| virtual **float** [get_FontHeight](./get_fontheight/)() | एक पोर्शन की फ़ॉन्ट ऊँचाई लौटाता है। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है ऊँचाई अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। **float** पढ़ें। |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | निर्धारित करता है कि फ़ॉन्ट इटालिक है या नहीं। कोई विरासत लागू नहीं होती। [NullableBool](../nullablebool/) पढ़ें। |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | पाठ अंडरलाइन प्रकार लौटाता है। कोई विरासत लागू नहीं होती। [TextUnderlineType](../textunderlinetype/) पढ़ें। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | पाठ को हाइलाइट करने के लिए इस्तेमाल किए गए रंग को लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [IColorFormat](../icolorformat/)। |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | निर्धारित करता है कि अंडरलाइन स्टाइल के अपने [FillFormat](../fillformat/) प्रॉपर्टीज़ हैं या यह पाठ की [FillFormat](../fillformat/) प्रॉपर्टीज़ से विरासत में लेता है। [NullableBool](../nullablebool/) पढ़ें। |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | निर्धारित करता है कि अंडरलाइन स्टाइल के अपने [LineFormat](../lineformat/) प्रॉपर्टीज़ हैं या यह पाठ की [LineFormat](../lineformat/) प्रॉपर्टीज़ से विरासत में लेता है। [NullableBool](../nullablebool/) पढ़ें। |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | न्यूनतम फ़ॉन्ट आकार लौटाता है, जिसके लिए करनिंग सक्रिय होनी चाहिए। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। **float** पढ़ें। |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | निर्धारित करता है कि संख्याएँ टेक्स्ट के पूर्वी भाषा-विशिष्ट वर्टिकल लेआउट को नजरअंदाज़ करें या नहीं। कोई विरासत लागू नहीं होती। [NullableBool](../nullablebool/) पढ़ें। |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | स्पेलिंग और ग्रामर जांच के लिए उपयोग की जाने वाली प्रूफिंग भाषा की Id लौटाता है। [System::String](../../system/string/) पढ़ें। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | लैटिन फ़ॉन्ट जानकारी लौटाता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। [IFontData](../ifontdata/) पढ़ें। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | पाठ आउटलाइनिंग के लिए [LineFormat](../lineformat/) प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | निर्धारित करता है कि पाठ की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं होती। [NullableBool](../nullablebool/) पढ़ें। |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | निर्धारित करता है कि पाठ को प्रूफ नहीं किया जाना चाहिए। कोई विरासत लागू नहीं होती। [NullableBool](../nullablebool/) पढ़ें। |
| virtual **float** [get_Spacing](./get_spacing/)() | अक्षर-अंतर स्पेसिंग वृद्धि लौटाता है। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। **float** पढ़ें। |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | टेक्स्ट पोर्शन के लिए स्पेल-चेकिंग सक्षम है या नहीं, यह दर्शाता है। जब यह प्रॉपर्टी false पर सेट होती है, तो टेक्स्ट एलेमेंट्स के लिए स्पेल-चेकिंग दमनित रहती है। जब true पर सेट होती है, तो स्पेल-चेकिंग अनुमति होती है। डिफ़ॉल्ट मान **false** है। |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | पाठ के स्ट्राइकथ्रू प्रकार लौटाता है। कोई विरासत लागू नहीं होती। [TextStrikethroughType](../textstrikethroughtype/) पढ़ें। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | प्रतीकात्मक फ़ॉन्ट जानकारी लौटाता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। [IFontData](../ifontdata/) पढ़ें। |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | पाठ कैपिटलाइज़ेशन प्रकार लौटाता है। कोई विरासत लागू नहीं होती। [Slides::TextCapType](../textcaptype/) पढ़ें। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | अंडरलाइन लाइन [FillFormat](../fillformat/) प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | अंडरलाइन लाइन को आउटलाइन करने के लिए उपयोग किए गए [LineFormat](../lineformat/) प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट लक्ष्य टाइप द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनेल ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr से रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | वैकल्पिक भाषा की Id सेट करता है। [System::String](../../system/string/) लिखें। |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी सेट करता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। [IFontData](../ifontdata/) लिखें। |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | ईस्ट एशियन फ़ॉन्ट जानकारी सेट करता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। [IFontData](../ifontdata/) लिखें। |
| virtual void [set_Escapement](./set_escapement/)(**float**) | सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट सेट करता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक होता है। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। **float** लिखें। |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत लागू नहीं होती। [NullableBool](../nullablebool/) लिखें। |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | एक पोर्शन की फ़ॉन्ट ऊँचाई सेट करता है। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है ऊँचाई अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। **float** लिखें। |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि फ़ॉन्ट इटालिक है या नहीं। कोई विरासत लागू नहीं होती। [NullableBool](../nullablebool/) लिखें। |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | पाठ अंडरलाइन प्रकार सेट करता है। कोई विरासत लागू नहीं होती। [TextUnderlineType](../textunderlinetype/) लिखें। |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि अंडरलाइन स्टाइल के अपने [FillFormat](../fillformat/) प्रॉपर्टीज़ हैं या यह पाठ की [FillFormat](../fillformat/) प्रॉपर्टीज़ से विरासत में लेता है। [NullableBool](../nullablebool/) लिखें। |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि अंडरलाइन स्टाइल के अपने [LineFormat](../lineformat/) प्रॉपर्टीज़ हैं या यह पाठ की [LineFormat](../lineformat/) प्रॉपर्टीज़ से विरासत में लेता है। [NullableBool](../nullablebool/) लिखें। |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | न्यूनतम फ़ॉन्ट आकार सेट करता है, जिसके लिए करनिंग सक्रिय होनी चाहिए। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। **float** लिखें। |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि संख्याएँ टेक्स्ट के पूर्वी भाषा-विशिष्ट वर्टिकल लेआउट को नजरअंदाज़ करें या नहीं। कोई विरासत लागू नहीं होती। [NullableBool](../nullablebool/) लिखें। |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | प्रूफिंग भाषा की Id सेट करता है। स्पेलिंग और ग्रामर जांच के लिए उपयोग किया जाता है। [System::String](../../system/string/) लिखें। |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | लैटिन फ़ॉन्ट जानकारी सेट करता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। [IFontData](../ifontdata/) लिखें। |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि पाठ की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं होती। [NullableBool](../nullablebool/) लिखें। |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि पाठ को प्रूफ़ नहीं किया जाना चाहिए। कोई विरासत लागू नहीं होती। [NullableBool](../nullablebool/) लिखें। |
| virtual void [set_Spacing](./set_spacing/)(**float**) | अक्षर-अंतर स्पेसिंग वृद्धि सेट करता है। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। **float** लिखें। |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | टेक्स्ट पोर्शन के लिए स्पेल-चेकिंग सक्षम है या नहीं, यह दर्शाता है। जब यह प्रॉपर्टी false पर सेट होती है, तो टेक्स्ट एलेमेंट्स के लिए स्पेल-चेकिंग दमनित रहती है। जब true पर सेट होती है, तो स्पेल-चेकिंग अनुमति होती है। डिफ़ॉल्ट मान **false** है। |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | पाठ के स्ट्राइकथ्रू प्रकार सेट करता है। कोई विरासत लागू नहीं होती। [TextStrikethroughType](../textstrikethroughtype/) लिखें। |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | प्रतीकात्मक फ़ॉन्ट जानकारी सेट करता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। [IFontData](../ifontdata/) लिखें। |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | पाठ कैपिटलाइज़ेशन प्रकार सेट करता है। कोई विरासत लागू नहीं होती। [Slides::TextCapType](../textcaptype/) लिखें। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट तर्क को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में स्विच करना संभव बनाता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनेल ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टिप्पणियाँ

यह क्लास किसी विशेष पोर्शन के लिए परिभाषित टेक्स्ट पोर्शन फ़ॉर्मेटिंग प्रॉपर्टीज़ को लौटाने और उनमें परिवर्तन करने के लिए उपयोग की जाती है। इसका अर्थ है कि मान प्राप्त करने पर कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आप ऐसे मान प्राप्त करेंगे जो \"अनिर्धारित\" का अर्थ देते हैं।

विरासत सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [IPortionFormat::GetEffective](../iportionformat/geteffective/) मेथड का उपयोग करना होगा जो एक [IPortionFormatEffectiveData](../iportionformateffectivedata/) इंस्टेंस लौटाता है।

## देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)