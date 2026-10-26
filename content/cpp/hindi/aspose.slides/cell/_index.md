---
title: Cell
second_title: Aspose.Slides for C++ API संदर्भ
description: तालिका की एक सेल का प्रतिनिधित्व करता है।
type: docs
weight: 300
url: /hi/aspose.slides/cell/
---
## Cell क्लास

Represents a cell of a table.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## विधियाँ

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | निर्धारित करता है कि क्या टेक्स्ट बॉक्स सेल के भीतर केंद्रित है या नहीं। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | वापस करता है [CellFormat](../cellformat/) ऑब्जेक्ट जो इस सेल के फ़ॉर्मेटिंग गुणों को शामिल करता है। केवल-पठन [ICellFormat](../icellformat/)। |
| **int32_t** [get_ColSpan](./get_colspan/)() override | वापस करता है पैरेंट टेबल की टेबल ग्रिड में ग्रिड कॉलमों की संख्या जिसे वर्तमान सेल द्वारा विस्तारित किया जाना है। यह प्रॉपर्टी सेल्स को मर्ज्ड होने जैसा दिखावट देती है, क्योंकि वे टेबल में अन्य सेल्स की लंबवत सीमाओं को कवर करते हैं। केवल-पठन **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | सेल का पहला कॉलम प्राप्त करता है। केवल-पठन [IColumn](../icolumn/)। |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | सेल द्वारा कवर किए गए पहले कॉलम का सूचकांक वापस करता है। केवल-पठन **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | सेल की पहली पंक्ति प्राप्त करता है। केवल-पठन [IRow](../irow/)। |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | सेल द्वारा कवर की गई पहली पंक्ति का सूचकांक वापस करता है। केवल-पठन **int32_t**। |
| **double** [get_Height](./get_height/)() override | सेल की ऊँचाई वापस करता है। केवल-पठन **double**। |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | यदि सेल किसी समायोजित सेल के साथ मर्ज्ड है तो true लौटाता है, अन्यथा false। केवल-पठन **bool**। |
| **double** [get_MarginBottom](./get_marginbottom/)() override | एक [TextFrame](../textframe/) में निचला मार्जिन लौटाता है। पढ़ें **double**। |
| **double** [get_MarginLeft](./get_marginleft/)() override | एक [TextFrame](../textframe/) में बायाँ मार्जिन लौटाता है। पढ़ें **double**। |
| **double** [get_MarginRight](./get_marginright/)() override | एक [TextFrame](../textframe/) में दायाँ मार्जिन लौटाता है। पढ़ें **double**। |
| **double** [get_MarginTop](./get_margintop/)() override | एक [TextFrame](../textframe/) में ऊपर का मार्जिन लौटाता है। पढ़ें **double**। |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | सेल की न्यूनतम ऊँचाई लौटाता है। यह सेल द्वारा कवर की गई सभी पंक्तियों की न्यूनतम ऊँचाइयों का योग है। केवल-पठन **double**। |
| **double** [get_OffsetX](./get_offsetx/)() override | टेबल के बाएँ पक्ष से सेल के बाएँ पक्ष तक की दूरी लौटाता है। केवल-पठन **double**। |
| **double** [get_OffsetY](./get_offsety/)() override | टेबल के ऊपर पक्ष से सेल के ऊपर पक्ष तक की दूरी लौटाता है। केवल-पठन **double**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | सेल की पैरेंट प्रेजेंटेशन लौटाता है। केवल-पठन [IPresentation](../ipresentation/)। |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | मर्ज्ड सेल द्वारा कवर की गई पंक्तियों की संख्या लौटाता है। यह अन्य सेल्स पर vMerge एट्रिब्यूट के साथ मिलकर क्षैतिज मर्ज की शुरुआत सेल को निर्दिष्ट करने के लिए उपयोग किया जाता है। केवल-पठन **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | सेल की पैरेंट स्लाइड लौटाता है। केवल-पठन [IBaseSlide](../ibaseslide/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | सेल के लिए पैरेंट [Table](../table/) ऑब्जेक्ट लौटाता है। केवल-पठन [ITable](../itable/)। |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | टेक्स्ट एंकर प्रकार लौटाता है। पढ़ें [Slides::TextAnchorType](../textanchortype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | सेल का टेक्स्ट फ्रेम लौटाता है। केवल-पठन [ITextFrame](../itextframe/)। |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | वर्टिकल टेक्स्ट का प्रकार लौटाता है। पढ़ें [Slides::TextVerticalType](../textverticaltype/)। |
| **double** [get_Width](./get_width/)() override | सेल की चौड़ाई लौटाता है। केवल-पठन **double**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम बनाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टैंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स को क्लोन करने को सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार ऑब्जेक्ट की रेफ़रेंस की तुलना nullptr से करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषकरण स्ट्रिंग और nullptr के केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषकरण स्ट्रिंग्स के केस के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को कम करता है। |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | निर्धारित करता है कि क्या टेक्स्ट बॉक्स सेल के भीतर केंद्रित है या नहीं। लिखें **bool**। |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | [TextFrame](../textframe/) में निचला मार्जिन सेट करता है। लिखें **double**। |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | [TextFrame](../textframe/) में बायाँ मार्जिन सेट करता है। लिखें **double**। |
| void [set_MarginRight](./set_marginright/)(**double**) override | [TextFrame](../textframe/) में दायाँ मार्जिन सेट करता है। लिखें **double**। |
| void [set_MarginTop](./set_margintop/)(**double**) override | [TextFrame](../textframe/) में ऊपर का मार्जिन सेट करता है। लिखें **double**। |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | टेक्स्ट एंकर प्रकार सेट करता है। लिखें [Slides::TextAnchorType](../textanchortype/)। |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | वर्टिकल टेक्स्ट का प्रकार सेट करता है। लिखें [Slides::TextVerticalType](../textverticaltype/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्यूमेंट को एक वीक पॉइंटर (शेयरड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयरड रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयरड रेफ़रेंस काउंटर घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | कॉलम के सूचकांक द्वारा सेल को दो सेल्स में विभाजित करता है। |
| void [SplitByHeight](./splitbyheight/)(**double**) override | सेल को ऊँचाई के आधार पर विभाजित करता है। |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | पंक्ति के सूचकांक द्वारा सेल को दो सेल्स में विभाजित करता है। |
| void [SplitByWidth](./splitbywidth/)(**double**) override | सेल को चौड़ाई के आधार पर विभाजित करता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कॉन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [IDOMObject](../idomobject/)
* क्लास [ICell](../icell/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)