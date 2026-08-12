---
title: IPortionFormat
second_title: Aspose.Slides for C++ API संदर्भ
description: यह क्लास पाठ भाग फ़ॉर्मेटिंग गुणों को समाहित करती है। IPortionFormatEffectiveData के विपरीत, इस क्लास की सभी गुण लिखने योग्य हैं।
type: docs
weight: 3329
url: /hi/aspose.slides/iportionformat/
---
## IPortionFormat क्लास

यह क्लास टेक्स्ट हिस्से के फ़ॉर्मेटिंग गुणों को समाहित करती है। [IPortionFormatEffectiveData](../iportionformateffectivedata/) के विपरीत, इस क्लास की सभी गुण लिखने योग्य हैं।

```cpp
class IPortionFormat : public virtual Aspose::Slides::IBasePortionFormat,
                       public Aspose::Slides::IHyperlinkContainer
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformat/get_alternativelanguageid/)() | वैकल्पिक भाषा का Id लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | बुकमार्क पहचानकर्ता लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformat/get_complexscriptfont/)() | जटिल स्क्रिप्ट फॉन्ट जानकारी लौटाता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ें [IFontData](../ifontdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformat/get_eastasianfont/)() | ईस्ट एशियाई फ़ॉन्ट जानकारी लौटाता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ें [IFontData](../ifontdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ibaseportionformat/get_effectformat/)() | पाठ [EffectFormat](../effectformat/) गुण लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| virtual **float** [get_Escapement](../ibaseportionformat/get_escapement/)() | सुपरस्क्रिप्ट या सबस्क्रिप्ट पाठ लौटाता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ें **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ibaseportionformat/get_fillformat/)() | पाठ [FillFormat](../fillformat/) गुण लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| virtual [NullableBool](../nullablebool/) [get_FontBold](../ibaseportionformat/get_fontbold/)() | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत लागू नहीं। पढ़ें [NullableBool](../nullablebool/)। |
| virtual **float** [get_FontHeight](../ibaseportionformat/get_fontheight/)() | एक भाग की फ़ॉन्ट ऊँचाई लौटाता है। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है ऊँचाई अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ें **float**। |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](../ibaseportionformat/get_fontitalic/)() | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। कोई विरासत लागू नहीं। पढ़ें [NullableBool](../nullablebool/)। |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformat/get_fontunderline/)() | पाठ अंडरलाइन प्रकार लौटाता है। कोई विरासत लागू नहीं। पढ़ें [TextUnderlineType](../textunderlinetype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../ibaseportionformat/get_highlightcolor/)() | पाठ को हाईलाइट करने के लिए उपयोग किया गया रंग लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [IColorFormat](../icolorformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | हाइपरलिंक प्रबंधक केवल पढ़ने योग्य [IHyperlinkManager](../ihyperlinkmanager/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../ibaseportionformat/get_ishardunderlinefill/)() | निर्धारित करता है कि अंडरलाइन शैली की अपनी [FillFormat](../fillformat/) गुण हैं या यह पाठ के [FillFormat](../fillformat/) गुणों से विरासत में मिली है। पढ़ें [NullableBool](../nullablebool/)। |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../ibaseportionformat/get_ishardunderlineline/)() | निर्धारित करता है कि अंडरलाइन शैली की अपनी [LineFormat](../lineformat/) गुण हैं या यह पाठ के [LineFormat](../lineformat/) गुणों से विरासत में मिली है। पढ़ें [NullableBool](../nullablebool/)। |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformat/get_kerningminimalsize/)() | न्यूनतम फ़ॉन्ट आकार लौटाता है, जिसके लिए केरनिंग चालू होनी चाहिए। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ें **float**। |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](../ibaseportionformat/get_kumimoji/)() | निर्धारित करता है कि संख्याएँ पाठ की पूर्वी भाषा-विशिष्ट लंबवत लेआउट को नज़रअंदाज़ करें। कोई विरासत लागू नहीं। पढ़ें [NullableBool](../nullablebool/)। |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformat/get_languageid/)() | प्रूफ़िंग भाषा का Id लौटाता है। वर्तनी और व्याकरण की जांच के लिए उपयोग किया जाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformat/get_latinfont/)() | लैटिन फ़ॉन्ट जानकारी लौटाता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ें [IFontData](../ifontdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ibaseportionformat/get_lineformat/)() | पाठ आउटलाइनिंग के लिए [LineFormat](../lineformat/) गुण लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](../ibaseportionformat/get_normaliseheight/)() | निर्धारित करता है कि पाठ की ऊँचाई सामान्यीकृत होनी चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ें [NullableBool](../nullablebool/)। |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](../ibaseportionformat/get_proofdisabled/)() | निर्धारित करता है कि पाठ को प्रूफ़ नहीं किया जाना चाहिए। कोई विरासत लागू नहीं। पढ़ें [NullableBool](../nullablebool/)। |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए। कोई विरासत लागू नहीं। पढ़ें **bool**। |
| virtual **float** [get_Spacing](../ibaseportionformat/get_spacing/)() | अक्षर अंतर स्पेसिंग वृद्धि लौटाता है। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ें **float**। |
| virtual **bool** [get_SpellCheck](../ibaseportionformat/get_spellcheck/)() | एक मान प्राप्त करता है जो इंगित करता है कि वर्तनी जाँच सक्षम है या नहीं। जब यह प्रॉपर्टी false सेट की जाती है, तो पाठ तत्वों के लिए वर्तनी जाँच दमन किया जाता है। जब true सेट होती है, तो वर्तनी जाँच अनुमति होती है। डिफ़ॉल्ट मान **false** है। |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformat/get_strikethroughtype/)() | पाठ का स्ट्राइकथ्रू प्रकार लौटाता है। कोई विरासत लागू नहीं। पढ़ें [TextStrikethroughType](../textstrikethroughtype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformat/get_symbolfont/)() | सिम्बोलिक फ़ॉन्ट जानकारी लौटाता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ें [IFontData](../ifontdata/)। |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformat/get_textcaptype/)() | पाठ के बड़े अक्षऱीकरण प्रकार को लौटाता है। कोई विरासत लागू नहीं। पढ़ें [Slides::TextCapType](../textcaptype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../ibaseportionformat/get_underlinefillformat/)() | अंडरलाइन लाइन [FillFormat](../fillformat/) गुण लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../ibaseportionformat/get_underlinelineformat/)() | अंडरलाइन लाइन को आउटलाइन करने के लिए उपयोग किए जाने वाले [LineFormat](../lineformat/) गुणों को लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() | विरासत लागू करके प्रभावी भाग फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के मामले के लिए विशिष्टकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशिष्टकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_AlternativeLanguageId](../ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | वैकल्पिक भाषा का Id सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) | बुकमार्क पहचानकर्ता सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_ComplexScriptFont](../ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। लिखें [IFontData](../ifontdata/)। |
| virtual void [set_EastAsianFont](../ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | ईस्ट एशियाई फ़ॉन्ट जानकारी सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। लिखें [IFontData](../ifontdata/)। |
| virtual void [set_Escapement](../ibaseportionformat/set_escapement/)(**float**) | सुपरस्क्रिप्ट या सबस्क्रिप्ट पाठ सेट करता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। लिखें **float**। |
| virtual void [set_FontBold](../ibaseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत लागू नहीं। लिखें [NullableBool](../nullablebool/)। |
| virtual void [set_FontHeight](../ibaseportionformat/set_fontheight/)(**float**) | एक भाग की फ़ॉन्ट ऊँचाई सेट करता है। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है ऊँचाई अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। लिखें **float**। |
| virtual void [set_FontItalic](../ibaseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। कोई विरासत लागू नहीं। लिखें [NullableBool](../nullablebool/)। |
| virtual void [set_FontUnderline](../ibaseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | पाठ अंडरलाइन प्रकार सेट करता है। कोई विरासत लागू नहीं। लिखें [TextUnderlineType](../textunderlinetype/)। |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| virtual void [set_IsHardUnderlineFill](../ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि अंडरलाइन शैली की अपनी [FillFormat](../fillformat/) गुण हैं या यह पाठ के [FillFormat](../fillformat/) गुणों से विरासत में मिली है। लिखें [NullableBool](../nullablebool/)। |
| virtual void [set_IsHardUnderlineLine](../ibaseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि अंडरलाइन शैली की अपनी [LineFormat](../lineformat/) गुण हैं या यह पाठ के [LineFormat](../lineformat/) गुणों से विरासत में मिली है। लिखें [NullableBool](../nullablebool/)। |
| virtual void [set_KerningMinimalSize](../ibaseportionformat/set_kerningminimalsize/)(**float**) | न्यूनतम फ़ॉन्ट आकार सेट करता है, जिसके लिए केरनिंग चालू होनी चाहिए। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। लिखें **float**। |
| virtual void [set_Kumimoji](../ibaseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि संख्याएँ पाठ की पूर्वी भाषा-विशिष्ट लंबवत लेआउट को नज़रअंदाज़ करें। कोई विरासत लागू नहीं। लिखें [NullableBool](../nullablebool/)। |
| virtual void [set_LanguageId](../ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | प्रूफ़िंग भाषा का Id सेट करता है। वर्तनी और व्याकरण की जांच के लिए उपयोग किया जाता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_LatinFont](../ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | लैटिन फ़ॉन्ट जानकारी सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। लिखें [IFontData](../ifontdata/)। |
| virtual void [set_NormaliseHeight](../ibaseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि पाठ की ऊँचाई सामान्यीकृत होनी चाहिए या नहीं। कोई विरासत लागू नहीं। लिखें [NullableBool](../nullablebool/)। |
| virtual void [set_ProofDisabled](../ibaseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि पाठ को प्रूफ़ नहीं किया जाना चाहिए। कोई विरासत लागू नहीं। लिखें [NullableBool](../nullablebool/)। |
| virtual void [set_SmartTagClean](./set_smarttagclean/)(**bool**) | निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए। कोई विरासत लागू नहीं। लिखें **bool**। |
| virtual void [set_Spacing](../ibaseportionformat/set_spacing/)(**float**) | अक्षर अंतर स्पेसिंग वृद्धि सेट करता है। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। लिखें **float**। |
| virtual void [set_SpellCheck](../ibaseportionformat/set_spellcheck/)(**bool**) | एक मान सेट करता है जो इंगित करता है कि वर्तनी जाँच सक्षम है या नहीं। जब यह प्रॉपर्टी false सेट की जाती है, तो पाठ तत्वों के लिए वर्तनी जाँच दमन किया जाता है। जब true सेट होती है, तो वर्तनी जाँच अनुमति होती है। डिफ़ॉल्ट मान **false** है। |
| virtual void [set_StrikethroughType](../ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | पाठ का स्ट्राइकथ्रू प्रकार सेट करता है। कोई विरासत लागू नहीं। लिखें [TextStrikethroughType](../textstrikethroughtype/)। |
| virtual void [set_SymbolFont](../ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | सिम्बोलिक फ़ॉन्ट जानकारी सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। लिखें [IFontData](../ifontdata/)। |
| virtual void [set_TextCapType](../ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | पाठ के बड़े अक्षऱीकरण प्रकार को सेट करता है। कोई विरासत लागू नहीं। लिखें [Slides::TextCapType](../textcaptype/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्युमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टिप्पणियाँ

यह क्लास विशेष भाग के लिए निर्धारित टेक्स्ट हिस्से के फ़ॉर्मेटिंग गुणों को लौटाने और बदलने के लिए उपयोग की जाती है। इसका अर्थ है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको "undefined" अर्थ वाले मान प्राप्त होंगे।

विरासत सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [IPortionFormat::GetEffective](./geteffective/) मेथड का उपयोग करना होगा जो एक [IPortionFormatEffectiveData](../iportionformateffectivedata/) इंस्टेंस लौटाता है।

## संबंधित देखें

* क्लास [IBasePortionFormat](../ibaseportionformat/)
* क्लास [IHyperlinkContainer](../ihyperlinkcontainer/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)