---
title: IDataLabelFormat
second_title: Aspose.Slides for C++ API संदर्भ
description: DataLabel के लिए फॉर्मेटिंग विकल्पों का प्रतिनिधित्व करता है।
type: docs
weight: 963
url: /hi/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat क्लास


Represents formatting options for [DataLabel](../datalabel/).

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## मेथड्स

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | संदर्भ प्रकार के ऑब्जेक्ट्स की C# शैली में तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | मान प्रकार के ऑब्जेक्ट्स की C# शैली में तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के समान नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के समान नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | चार्ट को लौटाता है। केवल पढ़ने योग्य [IChart](../ichart/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | डेटा लेबल का फॉर्मेट दर्शाता है। केवल पढ़ने योग्य [IFormat](../iformat/)। |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | पढ़ें **bool**। |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग दर्शाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | डेटा लेबल की स्थिति दर्शाता है। पढ़ें [LegendDataLabelPosition](../legenddatalabelposition/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | प्रेजेंटेशन को लौटाता है। केवल पढ़ने योग्य [IPresentation](../../aspose.slides/ipresentation/)। |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | चार्ट के डेटा लेबल के लिए उपयोग किए जाने वाले विभाजक को दर्शाने वाला Variant सेट या लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मान प्रदर्शन व्यवहार को दर्शाता है। True बबल आकार मान दिखाता है। False छुपाता है। पढ़ें **bool**। |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | निर्दिष्ट चार्ट के डेटा लेबल श्रेणी नाम प्रदर्शन व्यवहार को दर्शाता है। True श्रेणी नाम दिखाता है। False छुपाता है। पढ़ें **bool**। |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट या डेटा लेबल रूप में दिखाया जाएगा। |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | निर्दिष्ट चार्ट के डेटा लेबल सेल मान प्रदर्शन व्यवहार को दर्शाता है। True सेल मान दिखाता है। False छुपाता है। पढ़ें **bool**। |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइन्स प्रदर्शन व्यवहार को दर्शाता है। True लीडर लाइन्स दिखाता है। False छुपाता है। पढ़ें **bool**। |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी प्रदर्शन व्यवहार को दर्शाता है। True यदि लेजेंड कुंजी दृश्य है। पढ़ें **bool**। |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को दर्शाता है। True प्रतिशत मान दिखाता है। False छुपाता है। पढ़ें **bool**। |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | एक Boolean लौटाता है जो चार्ट के डेटा लेबल के लिए श्रृंखला नाम प्रदर्शन व्यवहार दर्शाता है। True श्रृंखला नाम दिखाता है। False छुपाता है। पढ़ें **bool**। |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को दर्शाता है। True प्रतिशत मान दिखाता है। False छुपाता है। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | बेस स्लाइड को लौटाता है। केवल पढ़ने योग्य [IBaseSlide](../../aspose.slides/ibaseslide/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | चार्ट टेक्स्ट फॉर्मेट को लौटाता है। केवल पढ़ने योग्य [IChartTextFormat](../icharttextformat/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम बनाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम प्रकारों की क्लोनिंग को सक्षम बनाता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग और nullptr केस के लिए स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग्स केस के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | लिखें **bool**। |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग दर्शाता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | डेटा लेबल की स्थिति दर्शाता है। लिखें [LegendDataLabelPosition](../legenddatalabelposition/)। |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | चार्ट के डेटा लेबल के लिए उपयोग किए जाने वाले विभाजक को दर्शाने वाला Variant सेट या लौटाता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मान प्रदर्शन व्यवहार को दर्शाता है। True बबल आकार मान दिखाता है। False छुपाता है। लिखें **bool**। |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | निर्दिष्ट चार्ट के डेटा लेबल श्रेणी नाम प्रदर्शन व्यवहार को दर्शाता है। True श्रेणी नाम दिखाता है। False छुपाता है। लिखें **bool**। |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट या डेटा लेबल रूप में दिखाया जाएगा। |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | निर्दिष्ट चार्ट के डेटा लेबल सेल मान प्रदर्शन व्यवहार को दर्शाता है। True सेल मान दिखाता है। False छुपाता है। लिखें **bool**। |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइन्स प्रदर्शन व्यवहार को दर्शाता है। True लीडर लाइन्स दिखाता है। False छुपाता है। लिखें **bool**। |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी प्रदर्शन व्यवहार को दर्शाता है। True यदि लेजेंड कुंजी दृश्य है। लिखें **bool**। |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को दर्शाता है। True प्रतिशत मान दिखाता है। False छुपाता है। लिखें **bool**। |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | एक Boolean सेट करता है जो चार्ट के डेटा लेबल के लिए श्रृंखला नाम प्रदर्शन व्यवहार दर्शाता है। True श्रृंखला नाम दिखाता है। False छुपाता है। लिखें **bool**। |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को दर्शाता है। True प्रतिशत मान दिखाता है। False छुपाता है। लिखें **bool**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्पलेट आर्ग्यूमेंट को शैड पॉइंटर (साझा नहीं) के रूप में सेट करें। कंटेनरों में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [IFormattedTextContainer](../iformattedtextcontainer/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)