---
title: PortionFormat
second_title: Aspose.Slides for C++ API संदर्भ
description: यह वर्ग पाठ खंड फ़ॉर्मेटिंग गुणों को शामिल करता है। IPortionFormatEffectiveData के विपरीत, इस वर्ग की सभी गुण लिखने योग्य हैं।
type: docs
weight: 4811
url: /hi/aspose.slides/portionformat/
---
## PortionFormat वर्ग


यह वर्ग पाठ खंड फ़ॉर्मेटिंग गुणों को शामिल करता है। [IPortionFormatEffectiveData](../iportionformateffectivedata/) के विपरीत, इस वर्ग की सभी गुण लिखने योग्य हैं।

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्दिष्ट वस्तु के साथ तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) पारस्परिक अर्थ का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में संदर्भ प्रकार वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, इसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, इसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | वैकल्पिक भाषा का Id लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | बुकमार्क पहचानकर्ता लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | जटिल लिपि फ़ॉन्ट जानकारी लौटाता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें [IFontData](../ifontdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | ईस्ट एशियन फ़ॉन्ट जानकारी लौटाता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें [IFontData](../ifontdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | पाठ [EffectFormat](../effectformat/) गुणों को लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | उपरिलेख या अधिलेख पाठ लौटाता है। मान -100 % (अधिलेख) से 100 % (उपरिलेख) तक। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | पाठ [FillFormat](../fillformat/) गुणों को लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत लागू नहीं। पढ़ें [NullableBool](../nullablebool/)। |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | खंड की फ़ॉन्ट ऊँचाई लौटाता है। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है ऊँचाई अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें **float**। |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। कोई विरासत लागू नहीं। पढ़ें [NullableBool](../nullablebool/)। |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | पाठ अंडरलाइन प्रकार लौटाता है। कोई विरासत लागू नहीं। पढ़ें [TextUnderlineType](../textunderlinetype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | टेक्स्ट को हाईलाइट करने के लिए उपयोग किए जाने वाले रंग को लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [IColorFormat](../icolorformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | हाइपरलिंक प्रबंधक। केवल-पढ़ने योग्य [IHyperlinkManager](../ihyperlinkmanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | निर्धारित करता है कि अंडरलाइन शैली के अपने [FillFormat](../fillformat/) गुण हैं या पाठ के [FillFormat](../fillformat/) गुणों से विरासत में लेती है। पढ़ें [NullableBool](../nullablebool/)। |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | निर्धारित करता है कि अंडरलाइन शैली के अपने [LineFormat](../lineformat/) गुण हैं या पाठ के [LineFormat](../lineformat/) गुणों से विरासत में लेती है। पढ़ें [NullableBool](../nullablebool/)। |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | न्यूनतम फ़ॉन्ट आकार लौटाता है, जिसके लिए केरनिंग सक्रिय किया जाना चाहिए। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें **float**। |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | निर्धारित करता है कि संख्याएँ टेक्स्ट की पूर्वी भाषा-विशिष्ट ऊर्ध्वाधर लेआउट को अनदेखा करेंगी या नहीं। कोई विरासत लागू नहीं। पढ़ें [NullableBool](../nullablebool/)। |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | प्रूफ़िंग भाषा का Id लौटाता है। वर्तनी और व्याकरण जांच के लिए उपयोग किया जाता है। पढ़ें [System::String](../../system/string/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | लैटिन फ़ॉन्ट जानकारी लौटाता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें [IFontData](../ifontdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | पाठ आउटलाइनिंग के लिए [LineFormat](../lineformat/) गुणों को लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | निर्धारित करता है कि टेक्स्ट की ऊँचाई सामान्यीकृत होनी चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ें [NullableBool](../nullablebool/)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IDOMObject](../idomobject/)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | पैरेंट [IPresentationComponent](../ipresentationcomponent/) लौटाता है। केवल-पढ़ने योग्य [IPresentationComponent](../ipresentationcomponent/)। |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | निर्धारित करता है कि पाठ को प्रूफ़ नहीं किया जाना चाहिए। कोई विरासत लागू नहीं। पढ़ें [NullableBool](../nullablebool/)। |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | निर्धारित करता है कि स्मार्ट टैग को साफ किया जाना चाहिए। कोई विरासत लागू नहीं। पढ़ें **bool**। |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | अक्षरांतर अंतराल वृद्धि लौटाता है। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें **float**। |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | यह निर्धारित करने वाला मान लौटाता है कि टेक्स्ट हिस्से के लिए वर्तनी जांच सक्षम है या नहीं। जब यह गुण false पर सेट होता है, तो टेक्स्ट तत्वों की वर्तनी जांच दबा दी जाती है। जब true पर सेट होता है, तो वर्तनी जांच अनुमति देती है। डिफ़ॉल्ट मान **false** है। |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | टेक्स्ट के स्ट्राइकथ्रू प्रकार को लौटाता है। कोई विरासत लागू नहीं। पढ़ें [TextStrikethroughType](../textstrikethroughtype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | प्रतीकात्मक फ़ॉन्ट जानकारी लौटाता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें [IFontData](../ifontdata/)। |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | टेक्स्ट कैपिटलाइज़ेशन प्रकार लौटाता है। कोई विरासत लागू नहीं। पढ़ें [Slides::TextCapType](../textcaptype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | अंडरलाइन लाइन [FillFormat](../fillformat/) गुणों को लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | अंडरलाइन लाइन को आउटलाइन करने के लिए उपयोग किए जाने वाले [LineFormat](../lineformat/) गुणों को लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से सम्बंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | विरासत लागू होने के साथ प्रभावी भाग फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | हैश कोड लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल के समान। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट लक्ष्य प्रकार द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# ‘is’ ऑपरेटर के समान। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन को लॉक करने को कार्यान्वित करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड के समान। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरम्भ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | प्रतिलिपि निर्माता। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरम्भ करता है और उपवर्गों के लिए कॉपी निर्माण सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरम्भ करता है और उपवर्गों के लिए कॉपी निर्माण सक्षम करता है। |
|  [PortionFormat](./portionformat/)() | [PortionFormat](./) वर्ग की नई इंस्टेंस आरम्भ करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | मान प्रकार ऑब्जेक्ट की nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | वैकल्पिक भाषा का Id सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | बुकमार्क पहचानकर्ता सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | जटिल लिपि फ़ॉन्ट जानकारी सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। लिखें [IFontData](../ifontdata/)। |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | ईस्ट एशियन फ़ॉन्ट जानकारी सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। लिखें [IFontData](../ifontdata/)। |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | उपरिलेख या अधिलेख पाठ सेट करता है। मान -100 % (अधिलेख) से 100 % (उपरिलेख) तक। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। लिखें **float**। |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत लागू नहीं। लिखें [NullableBool](../nullablebool/)। |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | खंड की फ़ॉन्ट ऊँचाई सेट करता है। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है ऊँचाई अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। लिखें **float**। |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। कोई विरासत लागू नहीं। लिखें [NullableBool](../nullablebool/)। |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | पाठ अंडरलाइन प्रकार सेट करता है। कोई विरासत लागू नहीं। लिखें [TextUnderlineType](../textunderlinetype/)। |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि अंडरलाइन शैली के अपने [FillFormat](../fillformat/) गुण हैं या पाठ के [FillFormat](../fillformat/) गुणों से विरासत में लेती है। लिखें [NullableBool](../nullablebool/)। |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि अंडरलाइन शैली के अपने [LineFormat](../lineformat/) गुण हैं या पाठ के [LineFormat](../lineformat/) गुणों से विरासत में लेती है। लिखें [NullableBool](../nullablebool/)। |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | न्यूनतम फ़ॉन्ट आकार सेट करता है, जिसके लिए केरनिंग सक्रिय किया जाना चाहिए। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। लिखें **float**। |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि संख्याएँ टेक्स्ट की पूर्वी भाषा-विशिष्ट ऊर्ध्वाधर लेआउट को अनदेखा करेंगी या नहीं। कोई विरासत लागू नहीं। लिखें [NullableBool](../nullablebool/)। |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | प्रूफ़िंग भाषा का Id सेट करता है। वर्तनी और व्याकरण जांच के लिए उपयोग किया जाता है। लिखें [System::String](../../system/string/)। |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | लैटिन फ़ॉन्ट जानकारी सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। लिखें [IFontData](../ifontdata/)। |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि टेक्स्ट की ऊँचाई सामान्यीकृत होनी चाहिए या नहीं। कोई विरासत लागू नहीं। लिखें [NullableBool](../nullablebool/)। |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि पाठ को प्रूफ़ नहीं किया जाना चाहिए। कोई विरासत लागू नहीं। लिखें [NullableBool](../nullablebool/)। |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | निर्धारित करता है कि स्मार्ट टैग को साफ किया जाना चाहिए। कोई विरासत लागू नहीं। लिखें **bool**। |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | अक्षरांतर अंतराल वृद्धि सेट करता है। **std::numeric_limits<float>::quiet_NaN()** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। लिखें **float**। |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | टेक्स्ट हिस्से के लिए वर्तनी जांच सक्षम या निष्क्रिय करने वाला मान सेट करता है। जब यह गुण false पर सेट होता है, तो टेक्स्ट तत्वों की वर्तनी जांच दबा दी जाती है। जब true पर सेट होता है, तो वर्तनी जांच अनुमति देती है। डिफ़ॉल्ट मान **false** है। |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | टेक्स्ट के स्ट्राइकथ्रू प्रकार को सेट करता है। कोई विरासत लागू नहीं। लिखें [TextStrikethroughType](../textstrikethroughtype/)। |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | प्रतीकात्मक फ़ॉन्ट जानकारी सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। लिखें [IFontData](../ifontdata/)। |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | टेक्स्ट कैपिटलाइज़ेशन प्रकार सेट करता है। कोई विरासत लागू नहीं। लिखें [Slides::TextCapType](../textcaptype/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्प्लेट आर्ग्यूमेंट को कमजोर पॉइंटर सेट करता है (शेयर्ड के बजाय)। कंटेनर में पॉइंटर्स को कमजोर मोड में बदलना संभव बनाता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता और लौटाता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड के समान। कस्टम ऑब्जेक्ट को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को कार्यान्वित करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन को अनलॉक करने को कार्यान्वित करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंटर को घटाता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टिप्पणी


यह वर्ग विशेष खंड के लिए परिभाषित पाठ खंड फ़ॉर्मेटिंग गुणों को लौटाने और संशोधित करने के लिए उपयोग किया जाता है। इसका अर्थ है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको मान “अपरिभाषित” मिलेंगे।

विरासत सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [PortionFormat::GetEffective](./geteffective/) मेथड का उपयोग करना होगा, जो एक [IPortionFormatEffectiveData](../iportionformateffectivedata/) इंस्टेंस लौटाता है।

निम्न उदाहरण दिखाते हैं कि कैसे लैटिन फ़ॉन्ट को PowerPoint [Presentation](../presentation/) के [Paragraph](../paragraph/) के भाग पर सौंपें। 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Aspose.Slides इन विशेष पहचानकर्ताओं का उपयोग करता है (PowerPoint में उपयोग किए जाने वाले समान):
// +mn-lt - बॉडी फ़ॉन्ट लैटिन (माइनर लैटिन फ़ॉन्ट)
// +mj-lt -Heading फ़ॉन्ट लैटिन (मैजोर लैटिन फ़ॉन्ट)
// +mn-ea - बॉडी फ़ॉन्ट ईस्ट एशियन (माइनर ईस्ट एशियन फ़ॉन्ट)
// +mj-ea - बॉडी फ़ॉन्ट ईस्ट एशियन (माइनर ईस्ट एशियन फ़ॉन्ट)
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## देखें

* वर्ग [BasePortionFormat](../baseportionformat/)
* वर्ग [IPortionFormat](../iportionformat/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)