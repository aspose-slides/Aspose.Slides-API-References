---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: स्थिर वस्तुओं के लिए बेस इंटरफ़ेस जो प्रभावी टेक्स्ट पोर्शन फ़ॉर्मेटिंग गुणों को सम्मिलित करती हैं।
type: docs
weight: 1470
url: /hi/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData क्लास

स्थिर वस्तुओं के लिए बेस इंटरफ़ेस जो प्रभावी पाठ हिस्से फॉर्मेटिंग गुणों को सम्मिलित करती हैं।

```cpp
class IBasePortionFormatEffectiveData : public virtual System::Object
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | वैकल्पिक भाषा का Id लौटाता है। केवल-पढ़ने योग्य [System::String](../../system/string/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [IFontData](../ifontdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | ईस्ट एशियन फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [IFontData](../ifontdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [get_EffectFormat](./get_effectformat/)() | पाठ [EffectFormat](../effectformat/) गुण लौटाता है। केवल-पढ़ने योग्य [IEffectFormatEffectiveData](../ieffectformateffectivedata/)। |
| virtual **float** [get_Escapement](./get_escapement/)() | सुपरस्क्रिप्ट या सबस्क्रिप्ट पाठ लौटाता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक। केवल-पढ़ने योग्य **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_FillFormat](./get_fillformat/)() | पाठ [FillFormat](../fillformat/) गुण लौटाता है। केवल-पढ़ने योग्य [IFillFormatEffectiveData](../ifillformateffectivedata/)। |
| virtual **bool** [get_FontBold](./get_fontbold/)() | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। केवल-पढ़ने योग्य **bool**। |
| virtual **float** [get_FontHeight](./get_fontheight/)() | पॉइंट्स में पाठ भाग की फ़ॉन्ट ऊँचाई लौटाता है। केवल-पढ़ने योग्य **float**। |
| virtual **bool** [get_FontItalic](./get_fontitalic/)() | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। केवल-पढ़ने योग्य **bool**। |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | पाठ अंडरलाइन प्रकार लौटाता है। केवल-पढ़ने योग्य [TextUnderlineType](../textunderlinetype/)। |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_HighlightColor](./get_highlightcolor/)() | पाठ को हाईलाइट करने के लिए उपयोग किए जाने वाले रंग को लौटाता है। केवल-पढ़ने योग्य [System::Drawing::Color](../../system.drawing/color/)। |
| virtual **bool** [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | निर्धारित करता है कि अंडरलाइन शैली के अपने [FillFormat](../fillformat/) गुण हैं या वह पाठ के [FillFormat](../fillformat/) गुणों से विरासत में लेती है। केवल-पढ़ने योग्य **bool**। |
| virtual **bool** [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | निर्धारित करता है कि अंडरलाइन शैली के अपने [LineFormat](../lineformat/) गुण हैं या वह पाठ के [LineFormat](../lineformat/) गुणों से विरासत में लेती है। केवल-पढ़ने योग्य **bool**। |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | न्यूनतम फ़ॉन्ट आकार लौटाता है, जिसके लिए करनिंग सक्रिय होनी चाहिए। केवल-पढ़ने योग्य **float**। |
| virtual **bool** [get_Kumimoji](./get_kumimoji/)() | निर्धारित करता है कि संख्याएँ पाठ के पूर्व-पूर्वी-भाषा-विशिष्ट लंबवत लेआउट को अनदेखा करें। केवल-पढ़ने योग्य **bool**। |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | भाषा का Id लौटाता है। केवल-पढ़ने योग्य [System::String](../../system/string/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | लैटिन फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [IFontData](../ifontdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_LineFormat](./get_lineformat/)() | पाठ आउटलाइनिंग के लिए [LineFormat](../lineformat/) गुण लौटाता है। केवल-पढ़ने योग्य [ILineFormatEffectiveData](../ilineformateffectivedata/)। |
| virtual **bool** [get_NormaliseHeight](./get_normaliseheight/)() | निर्धारित करता है कि पाठ की ऊँचाई का सामान्यीकरण होना चाहिए या नहीं। केवल-पढ़ने योग्य **bool**। |
| virtual **bool** [get_ProofDisabled](./get_proofdisabled/)() | निर्धारित करता है कि पाठ को प्रूफ़ नहीं किया जाना चाहिए। केवल-पढ़ने योग्य **bool**। |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए। केवल-पढ़ने योग्य **bool**। |
| virtual **float** [get_Spacing](./get_spacing/)() | पॉइंट्स में अक्षर-अंतराल वृद्धि लौटाता है। केवल-पढ़ने योग्य **float**। |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | पाठ का स्ट्राइकथ्रू प्रकार लौटाता है। केवल-पढ़ने योग्य [TextStrikethroughType](../textstrikethroughtype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | प्रतीकात्मक फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [IFontData](../ifontdata/)। |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | पाठ के कैपिटलाइज़ेशन प्रकार को लौटाता है। केवल-पढ़ने योग्य [Slides::TextCapType](../textcaptype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | अंडरलाइन लाइन [FillFormat](../fillformat/) गुणों को लौटाता है। केवल-पढ़ने योग्य [IFillFormatEffectiveData](../ifillformateffectivedata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | अंडरलाइन लाइन को आउटलाइन करने के लिए उपयोग किए जाने वाले [LineFormat](../lineformat/) गुण लौटाता है। केवल-पढ़ने योग्य [ILineFormatEffectiveData](../ilineformateffectivedata/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समतुल्य। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समतुल्य। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समतुल्य। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समतुल्य। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारम्भ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, सिर्फ नया ऑब्जेक्ट initialise करता है और सब-क्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, सिर्फ नया ऑब्जेक्ट initialise करता है और सब-क्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामलों के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनर में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान साझा रेफ़रेंस काउंटर का मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समतुल्य। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)