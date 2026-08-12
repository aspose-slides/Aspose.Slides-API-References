---
title: IPortionFormatEffectiveData
second_title: C++ के लिए Aspose.Slides API रेफ़रेंस
description: स्थिर वस्तु जो प्रभावी टेक्स्ट भाग फ़ॉर्मेटिंग गुणों को समाहित करती है।
type: docs
weight: 3342
url: /hi/aspose.slides/iportionformateffectivedata/
---
## IPortionFormatEffectiveData क्लास

स्थिर वस्तु जो प्रभावी टेक्स्ट भाग फ़ॉर्मेटिंग गुणों को समाहित करती है।

```cpp
class IPortionFormatEffectiveData : public virtual Aspose::Slides::IBasePortionFormatEffectiveData
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रिफ़रेंस टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | वैल्यू टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformateffectivedata/get_alternativelanguageid/)() | वैकल्पिक भाषा का Id लौटाता है। केवल-पढ़ने योग्य [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | बुकमार्क पहचानकर्ता लौटाता है। केवल-पढ़ने योग्य [System::String](../../system/string/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformateffectivedata/get_complexscriptfont/)() | जटिल लिपि फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [IFontData](../ifontdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformateffectivedata/get_eastasianfont/)() | ईस्ट एशियन फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [IFontData](../ifontdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [get_EffectFormat](../ibaseportionformateffectivedata/get_effectformat/)() | टेक्स्ट [EffectFormat](../effectformat/) गुण लौटाता है। केवल-पढ़ने योग्य [IEffectFormatEffectiveData](../ieffectformateffectivedata/)। |
| virtual **float** [get_Escapement](../ibaseportionformateffectivedata/get_escapement/)() | सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट लौटाता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक। केवल-पढ़ने योग्य **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_FillFormat](../ibaseportionformateffectivedata/get_fillformat/)() | टेक्स्ट [FillFormat](../fillformat/) गुण लौटाता है। केवल-पढ़ने योग्य [IFillFormatEffectiveData](../ifillformateffectivedata/)। |
| virtual **bool** [get_FontBold](../ibaseportionformateffectivedata/get_fontbold/)() | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। केवल-पढ़ने योग्य **bool**। |
| virtual **float** [get_FontHeight](../ibaseportionformateffectivedata/get_fontheight/)() | टेक्स्ट भाग की फ़ॉन्ट ऊँचाई पॉइंट्स में लौटाता है। केवल-पढ़ने योग्य **float**। |
| virtual **bool** [get_FontItalic](../ibaseportionformateffectivedata/get_fontitalic/)() | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। केवल-पढ़ने योग्य **bool**। |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformateffectivedata/get_fontunderline/)() | टेक्स्ट अंडरलाइन प्रकार लौटाता है। केवल-पढ़ने योग्य [TextUnderlineType](../textunderlinetype/)। |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_HighlightColor](../ibaseportionformateffectivedata/get_highlightcolor/)() | टेक्स्ट को हाइलाइट करने के लिए प्रयुक्त रंग लौटाता है। केवल-पढ़ने योग्य [System::Drawing::Color](../../system.drawing/color/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। केवल-पढ़ने योग्य [IHyperlink](../ihyperlink/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। केवल-पढ़ने योग्य [IHyperlink](../ihyperlink/)। |
| virtual **bool** [get_IsHardUnderlineFill](../ibaseportionformateffectivedata/get_ishardunderlinefill/)() | निर्धारित करता है कि अंडरलाइन शैली के अपने [FillFormat](../fillformat/) गुण हैं या वह टेक्स्ट के [FillFormat](../fillformat/) गुणों से विरासत में मिलते हैं। केवल-पढ़ने योग्य **bool**। |
| virtual **bool** [get_IsHardUnderlineLine](../ibaseportionformateffectivedata/get_ishardunderlineline/)() | निर्धारित करता है कि अंडरलाइन शैली के अपने [LineFormat](../lineformat/) गुण हैं या वह टेक्स्ट के [LineFormat](../lineformat/) गुणों से विरासत में मिलते हैं। केवल-पढ़ने योग्य **bool**। |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformateffectivedata/get_kerningminimalsize/)() | न्यूनतम फ़ॉन्ट आकार लौटाता है, जिसके लिए करनिंग चालू किया जाना चाहिए। केवल-पढ़ने योग्य **float**। |
| virtual **bool** [get_Kumimoji](../ibaseportionformateffectivedata/get_kumimoji/)() | निर्धारित करता है कि संख्याएँ टेक्स्ट के पूर्वी भाषा-विशिष्ट वर्टिकल लेआउट को अनदेखा करें। केवल-पढ़ने योग्य **bool**। |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformateffectivedata/get_languageid/)() | भाषा का Id लौटाता है। केवल-पढ़ने योग्य [System::String](../../system/string/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformateffectivedata/get_latinfont/)() | लैटिन फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [IFontData](../ifontdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_LineFormat](../ibaseportionformateffectivedata/get_lineformat/)() | टेक्स्ट आउटलाइनिंग के लिए [LineFormat](../lineformat/) गुण लौटाता है। केवल-पढ़ने योग्य [ILineFormatEffectiveData](../ilineformateffectivedata/)। |
| virtual **bool** [get_NormaliseHeight](../ibaseportionformateffectivedata/get_normaliseheight/)() | निर्धारित करता है कि टेक्स्ट की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। केवल-पढ़ने योग्य **bool**। |
| virtual **bool** [get_ProofDisabled](../ibaseportionformateffectivedata/get_proofdisabled/)() | निर्धारित करता है कि टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए। केवल-पढ़ने योग्य **bool**। |
| virtual **bool** [get_SmartTagClean](../ibaseportionformateffectivedata/get_smarttagclean/)() | निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए। केवल-पढ़ने योग्य **bool**। |
| virtual **float** [get_Spacing](../ibaseportionformateffectivedata/get_spacing/)() | इंटरकैरेक्टर स्पेसिंग इन्क्रिमेंट पॉइंट्स में लौटाता है। केवल-पढ़ने योग्य **float**। |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformateffectivedata/get_strikethroughtype/)() | टेक्स्ट के स्ट्राइकथ्रू प्रकार लौटाता है। केवल-पढ़ने योग्य [TextStrikethroughType](../textstrikethroughtype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformateffectivedata/get_symbolfont/)() | सिंबॉलिक फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [IFontData](../ifontdata/)। |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformateffectivedata/get_textcaptype/)() | टेक्स्ट कैपिटलाइज़ेशन का प्रकार लौटाता है। केवल-पढ़ने योग्य [Slides::TextCapType](../textcaptype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_UnderlineFillFormat](../ibaseportionformateffectivedata/get_underlinefillformat/)() | अंडरलाइन लाइन [FillFormat](../fillformat/) गुण लौटाता है। केवल-पढ़ने योग्य [IFillFormatEffectiveData](../ifillformateffectivedata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_UnderlineLineFormat](../ibaseportionformateffectivedata/get_underlinelineformat/)() | अंडरलाइन लाइन को आउटलाइन करने के लिए प्रयुक्त [LineFormat](../lineformat/) गुण लौटाता है। केवल-पढ़ने योग्य [ILineFormatEffectiveData](../ilineformateffectivedata/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानरूप। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानरूप। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानरूप। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानरूप। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रिफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्युमेंट को वीक पॉइंटर (शेयरड के बजाय) सेट करता है। कंटेनर्स में पॉइंटर को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानरूप। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टिप्पणी

यह इंटरफ़ेस [IPortionFormat](../iportionformat/) इंटरफ़ेस के साथ मिलकर प्रभावी फ़ॉर्मेटिंग मानों को विरासत लागू करके लौटाने के लिए उपयोग किया जाता है।

## देखें

* क्लास [IBasePortionFormatEffectiveData](../ibaseportionformateffectivedata/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)