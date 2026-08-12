---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for C++ API संदर्भ
description: एक अपरिवर्तनीय ऑब्जेक्ट जो प्रभावी टेक्स्ट फ्रेम फ़ॉर्मेटिंग गुणों को सम्मिलित करता है।
type: docs
weight: 4096
url: /hi/aspose.slides/itextframeformateffectivedata/
---
## ITextFrameFormatEffectiveData क्लास

एक अपरिवर्तनीय ऑब्जेक्ट जो प्रभावी टेक्स्ट फ्रेम फ़ॉर्मेटिंग गुणों को सम्मिलित करता है।

```cpp
class ITextFrameFormatEffectiveData : public virtual System::Object
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिमेंटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | एक [TextFrame](../textframe/) में लंबवत एंकर टेक्स्ट लौटाता है। केवल पढ़ने योग्य [TextAnchorType](../textanchortype/)। |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | टेक्स्ट ऑटॉफिट मोड लौटाता है। केवल पढ़ने योग्य [TextAutofitType](../textautofittype/)। |
| virtual **bool** [get_CenterText](./get_centertext/)() | बॉक्स में टेक्स्ट को क्षैतिज रूप से केंद्रित करना चाहिए या नहीं लौटाता है। केवल पढ़ने योग्य **bool**। |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | बाउंडिंग रेक्टेंगल में टेक्स्ट कॉलमों की संख्या निर्दिष्ट करता है। केवल पढ़ने योग्य **int32_t**। |
| virtual **float** [get_ColumnSpacing](./get_columnspacing/)() | टेक्स्ट क्षेत्र में टेक्स्ट कॉलमों के बीच की दूरी (पॉइंट्स में) निर्दिष्ट करता है। केवल पढ़ने योग्य **float**। |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | [TextFrame](../textframe/) में नीचे की मार्जिन (पॉइंट्स) लौटाता है। केवल पढ़ने योग्य **double**। |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | [TextFrame](../textframe/) में बाईं मार्जिन (पॉइंट्स) लौटाता है। केवल पढ़ने योग्य **double**। |
| virtual **double** [get_MarginRight](./get_marginright/)() | [TextFrame](../textframe/) में दाईं मार्जिन (पॉइंट्स) लौटाता है। केवल पढ़ने योग्य **double**। |
| virtual **double** [get_MarginTop](./get_margintop/)() | [TextFrame](../textframe/) में ऊपर की मार्जिन (पॉइंट्स) लौटाता है। केवल पढ़ने योग्य **double**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyleEffectiveData](../itextstyleeffectivedata/)\> [get_TextStyle](./get_textstyle/)() | प्रभावी टेक्स्ट की शैली लौटाता है। केवल पढ़ने योग्य [ITextStyleEffectiveData](../itextstyleeffectivedata/)। |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | टेक्स्ट अभिविन्यास लौटाता है। केवल पढ़ने योग्य [Slides::TextVerticalType](../textverticaltype/)। |
| virtual **bool** [get_WrapText](./get_wraptext/)() | [TextFrame](../textframe/) की मार्जिन पर टेक्स्ट रैप किया गया है या नहीं लौटाता है। केवल पढ़ने योग्य **bool**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबद्ध रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ ही कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस की तुलना nullptr से करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्युमेंट को एक वीक पॉइंटर (शेयर किए हुए के बजाय) सेट करता है। कंटेनरों में पॉइंटर को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और वापस देता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## टिप्पणी

यह इंटरफ़ेस [ITextFrameFormat](../itextframeformat/) इंटरफ़ेस के साथ मिलकर प्रभावी फ़ॉर्मेटिंग मान लौटाने के लिए उपयोग किया जाता है, जिसमें वंशानुगतता लागू होती है।

## देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्ररी [Aspose.Slides](../../)