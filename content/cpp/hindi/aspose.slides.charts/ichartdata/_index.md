---
title: IChartData
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक चार्ट प्लॉटिंग के लिए उपयोग किए जाने वाले डेटा को दर्शाता है।
type: docs
weight: 651
url: /hi/aspose.slides.charts/ichartdata/
---
## IChartData वर्ग

एक चार्ट प्लॉटिंग के लिए उपयोग किए जाने वाले डेटा को दर्शाता है।

```cpp
class IChartData : public virtual System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() | प्राथमिक श्रेणियों को प्राप्त करता है (या दोनों प्राथमिक और द्वितीयक श्रेणियों को यदि [IChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) को false सेट किया गया है)। केवल-पढ़ने योग्य [IChartCategoryCollection](../ichartcategorycollection/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) | निर्दिष्ट सूचकांक पर प्राथमिक श्रेणी को लौटाता है। यदि [get_UseSecondaryCategories](./get_usesecondarycategories/) false है, तो सभी श्रेणियों में से प्राप्त करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किए जाने वाले सेल्स बनाने के लिए सेल्स फैक्ट्री को प्राप्त करता है। केवल-पढ़ने योग्य [IChartDataWorkbook](../ichartdataworkbook/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | निर्दिष्ट सूचकांक पर श्रृंखला को लौटाता है। |
| virtual [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() | चार्ट के डेटा स्रोत को दर्शाता है। |
| virtual [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() | एम्बेडेड वर्कबुक का प्रकार प्राप्त करता है। यदि [IChartData::get_DataSourceType](./get_datasourcetype/) [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/) है तो [WorkbookType::NotDefined](../workbooktype/) लौटाता है। केवल-पढ़ने योग्य [WorkbookType](../workbooktype/)। |
| virtual [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() | यदि डेटा स्रोत बाह्य है तो बाह्य वर्कबुक पथ को दर्शाता है, अन्यथा null। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() | यदि [IChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) true है तो द्वितीयक श्रेणियों को प्राप्त करता है। केवल-पढ़ने योग्य [IChartCategoryCollection](../ichartcategorycollection/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) | निर्दिष्ट सूचकांक पर द्वितीयक श्रेणी को लौटाता है। यदि [get_UseSecondaryCategories](./get_usesecondarycategories/) false है, तो [IChartData::get_SecondaryCategories](./get_secondarycategories/) null होता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() | श्रृंखला को प्राप्त करता है। केवल-पढ़ने योग्य [IChartSeriesCollection](../ichartseriescollection/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) | निर्दिष्ट सूचकांक पर श्रृंखलाओं के समूह को लौटाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() | श्रृंखलाओं के समूह को प्राप्त करता है। केवल-पढ़ने योग्य [IChartSeriesGroupCollection](../ichartseriesgroupcollection/)। |
| virtual **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() | यदि false सेट किया गया है तो [IChartData::get_SecondaryCategories](./get_secondarycategories/) null लौटाता है और [IChartData::get_Categories](./get_categories/) में डेटा दोनों प्राथमिक और द्वितीयक श्रृंखलाओं के लिए उपयोग होता है। यदि true सेट किया गया है तो [IChartData::get_SecondaryCategories](./get_secondarycategories/) में डेटा द्वितीयक श्रृंखलाओं के लिए और [IChartData::get_Categories](./get_categories/) में डेटा प्राथमिक श्रृंखलाओं के लिए उपयोग होता है। पढ़ें **bool**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual [System::String](../../system/string/) [GetRange](./getrange/)() | चार्ट डेटा रेंज को प्राप्त करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस दर्शाता है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेस की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेस की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() | आंतरिक रूप से निहित [Excel](../../aspose.slides.excel/) वर्कबुक को मेमोरी स्ट्रीम में लिखता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार की वस्तु की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण, स्ट्रिंग और nullptr केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण, स्ट्रिंग्स केस के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
| virtual void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) | यदि false सेट किया गया है तो [IChartData::get_SecondaryCategories](./get_secondarycategories/) null लौटाता है और [IChartData::get_Categories](./get_categories/) में डेटा दोनों प्राथमिक और द्वितीयक श्रृंखलाओं के लिए उपयोग होता है। यदि true सेट किया गया है तो [IChartData::get_SecondaryCategories](./get_secondarycategories/) में डेटा द्वितीयक श्रृंखलाओं के लिए और [IChartData::get_Categories](./get_categories/) में डेटा प्राथमिक श्रृंखलाओं के लिए उपयोग होता है। लिखें **bool**। |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) | बाहर के वर्कबुक को चार्ट के डेटा स्रोत के रूप में सेट करता है। [Chart](../chart/) डेटा लक्ष्य वर्कबुक से अपडेट किया जाएगा। |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) | बाहर के वर्कबुक को चार्ट के डेटा स्रोत के रूप में सेट करता है। |
| virtual void [SetRange](./setrange/)([System::String](../../system/string/)) | चार्ट डेटा रेंज सेट करता है। नई डेटा रेंज के आधार पर श्रृंखलाएँ और श्रेणियाँ अपडेट होंगी। यदि डेटा रेंज में श्रृंखलाओं की संख्या चार्ट डेटा में श्रृंखलाओं की गिनती से अधिक है तो वर्तमान संग्रह की अंतिम श्रृंखला के समान प्रकार की अतिरिक्त श्रृंखलाएँ संग्रह के अंत में जोड़ दी जाएँगी। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्गुमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [SwitchRowColumn](./switchrowcolumn/)() | डेटा को अक्ष के ऊपर स्वैप करता है। X अक्ष पर चार्ट किया गया डेटा Y अक्ष पर चलेगा और इसके विपरीत। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कॉन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंटर को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) | उपयोगकर्ता-निर्दिष्ट मान के साथ आंतरिक रूप से निहित [Excel](../../aspose.slides.excel/) वर्कबुक को प्रारंभ करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* वर्ग [Object](../../system/object/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)