---
title: ICell
second_title: Aspose.Slides for C++ API संदर्भ
description: टेबल में एक सेल का प्रतिनिधित्व करता है।
type: docs
weight: 1639
url: /hi/aspose.slides/icell/
---
## ICell क्लास

एक टेबल में सेल का प्रतिनिधित्व करता है।

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलनात्मक को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलनात्मक को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | निर्धारित करता है कि क्या टेक्स्ट बॉक्स सेल के अंदर केंद्रित है या नहीं। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | इस सेल के फ़ॉर्मेटिंग प्रॉपर्टीज़ वाले [CellFormat](../cellformat/) ऑब्जेक्ट को वापस करता है। केवल-रीड [ICellFormat](../icellformat/)। |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | पैरेंट टेबल की टेबल ग्रिड में ग्रिड कॉलमों की संख्या लौटाता है जिसे वर्तमान सेल द्वारा विस्तारित किया जाना चाहिए। यह प्रॉपर्टी सेल को मर्ज्ड जैसा दिखने देता है, क्योंकि यह टेबल में अन्य सेल्स की वर्टिकल सीमा को कवर करता है। केवल-रीड **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | सेल का पहला कॉलम प्राप्त करता है। केवल-रीड [IColumn](../icolumn/)। |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | सेल द्वारा कवर किए गए पहले कॉलम का इंडेक्स लौटाता है। केवल-रीड **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | सेल की पहली पंक्ति प्राप्त करता है। केवल-रीड [IRow](../irow/)। |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | सेल द्वारा कवर की गई पहली पंक्ति का इंडेक्स लौटाता है। केवल-रीड **int32_t**। |
| virtual **double** [get_Height](./get_height/)() | सेल की ऊँचाई लौटाता है। केवल-रीड **double**। |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | यदि सेल किसी समायोजित सेल के साथ मर्ज्ड है तो true लौटाता है, अन्यथा false। केवल-रीड **bool**। |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | [TextFrame](../textframe/) में निचला मार्जिन लौटाता है। पढ़ें **double**। |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | [TextFrame](../textframe/) में बायाँ मार्जिन लौटाता है। पढ़ें **double**। |
| virtual **double** [get_MarginRight](./get_marginright/)() | [TextFrame](../textframe/) में दायाँ मार्जिन लौटाता है। पढ़ें **double**। |
| virtual **double** [get_MarginTop](./get_margintop/)() | [TextFrame](../textframe/) में ऊपर की मार्जिन लौटाता है। पढ़ें **double**। |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | सेल की न्यूनतम ऊँचाई लौटाता है। यह सेल द्वारा कवर की गई सभी पंक्तियों की न्यूनतम ऊँचाइयों का योग है। केवल-रीड **double**। |
| virtual **double** [get_OffsetX](./get_offsetx/)() | टेबल के बाएँ किनारे से सेल के बाएँ किनारे तक की दूरी लौटाता है। केवल-रीड **double**। |
| virtual **double** [get_OffsetY](./get_offsety/)() | टेबल के ऊपर किनारे से सेल के ऊपर किनारे तक की दूरी लौटाता है। केवल-रीड **double**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | प्रेज़ेंटेशन लौटाता है। केवल-रीड [IPresentation](../ipresentation/)। |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | एक मर्ज्ड सेल द्वारा कवर की गई पंक्तियों की संख्या लौटाता है। यह अन्य सेल्स पर vMerge एट्रिब्यूट के साथ मिलकर क्षैतिज मर्ज की शुरुआत वाले सेल को निर्दिष्ट करने के लिए उपयोग किया जाता है। केवल-रीड **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल-रीड [IBaseSlide](../ibaseslide/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | सेल के लिए पैरेंट [Table](../table/) ऑब्जेक्ट को लौटाता है। केवल-रीड [ITable](../itable/)। |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | टेक्स्ट एंकर टाइप लौटाता है। पढ़ें [Slides::TextAnchorType](../textanchortype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | सेल का टेक्स्ट फ्रेम लौटाता है। केवल-रीड [ITextFrame](../itextframe/)। |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | वर्टिकल टेक्स्ट का प्रकार लौटाता है। पढ़ें [Slides::TextVerticalType](../textverticaltype/)। |
| virtual **double** [get_Width](./get_width/)() | सेल की चौड़ाई लौटाता है। केवल-रीड **double**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबद्ध रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड की समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल की समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है। C# 'is' ऑपरेटर की समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड की समानांतर। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज को कॉपी कंस्ट्रक्ट करने में सक्षम बनाता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज को कॉपी कंस्ट्रक्ट करने में सक्षम बनाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | string और nullptr केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मूल्य द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | निर्धारित करता है कि क्या टेक्स्ट बॉक्स सेल के अंदर केंद्रित है या नहीं। लिखें **bool**। |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | [TextFrame](../textframe/) में निचला मार्जिन सेट करता है। लिखें **double**। |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | [TextFrame](../textframe/) में बायाँ मार्जिन सेट करता है। लिखें **double**। |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | [TextFrame](../textframe/) में दायाँ मार्जिन सेट करता है। लिखें **double**। |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | [TextFrame](../textframe/) में ऊपर का मार्जिन सेट करता है। लिखें **double**। |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | टेक्स्ट एंकर टाइप सेट करता है। लिखें [Slides::TextAnchorType](../textanchortype/)। |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | वर्टिकल टेक्स्ट का प्रकार सेट करता है। लिखें [Slides::TextVerticalType](../textverticaltype/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्यूमेंट को वीक पॉइंटर (शेयर्ड की बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाकर लौटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | कॉलम इंडेक्स के आधार पर सेल को दो सेल्स में विभाजित करता है। |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | सेल को ऊँचाई के आधार पर विभाजित करता है। |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | पंक्ति इंडेक्स के आधार पर सेल को दो सेल्स में विभाजित करता है। |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | सेल को चौड़ाई के आधार पर विभाजित करता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड की समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में कन्वर्ट करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कॉन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट की अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## संबंधित देखें

* क्लास [ISlideComponent](../islidecomponent/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)