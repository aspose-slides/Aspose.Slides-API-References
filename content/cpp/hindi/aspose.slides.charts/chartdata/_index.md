---
title: ChartData
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: चार्ट प्लॉटिंग के लिए उपयोग किए जाने वाले डेटा का प्रतिनिधित्व करता है।
type: docs
weight: 118
url: /hi/aspose.slides.charts/chartdata/
---
## ChartData class

एक चार्ट प्लॉटिंग के लिए उपयोग किए जाने वाले डेटा का प्रतिनिधित्व करता है।

```cpp
class ChartData : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                  public Aspose::Slides::Charts::IChartData
```

## मेथड्स

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को एмуляट करता है जहाँ दो NaN को बराबर माना जाता है भले ही IEC 60559:1989 के अनुसार NaN किसी भी मूल्य के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को एмуляट करता है जहाँ दो NaN को बराबर माना जाता है भले ही IEC 60559:1989 के अनुसार NaN किसी भी मूल्य के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() override | मुख्य श्रेणियों को प्राप्त करता है (या यदि [ChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) को false सेट किया गया है तो मुख्य और द्वितीयक दोनों श्रेणियाँ)। केवल-पढ़ने योग्य [IChartCategoryCollection](../ichartcategorycollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर मुख्य श्रेणी लौटाता है। यदि [get_UseSecondaryCategories](./get_usesecondarycategories/) false है, तो सभी श्रेणियों में से प्राप्त करें। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() override | चार्ट सीरीज या श्रेणियों के लिए उपयोग किए जाने वाले सेल्स बनाने के लिए सेल्स फ़ैक्टरी प्राप्त करता है। केवल-पढ़ने योग्य [IChartDataWorkbook](../ichartdataworkbook/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर सीरीज़ लौटाता है। |
| [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() override | यदि बाहरी डेटा स्रोत हो तो बाहरी वर्कबुक पाथ का प्रतिनिधित्व करता है, अन्यथा null। |
| [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() override | एम्बेडेड वर्कबुक का प्रकार प्राप्त करता है। यदि [ChartData::get_DataSourceType](./get_datasourcetype/) [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/) है तो [WorkbookType::NotDefined](../workbooktype/) लौटाता है। केवल-पढ़ने योग्य [WorkbookType](../workbooktype/)। |
| [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() override | चार्ट का डेटा स्रोत दर्शाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() override | यदि [ChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) true है तो द्वितीयक श्रेणियाँ प्राप्त करता है। केवल-पढ़ने योग्य [IChartCategoryCollection](../ichartcategorycollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर द्वितीयक श्रेणी लौटाता है। यदि [get_UseSecondaryCategories](./get_usesecondarycategories/) false है, तो [ChartData::get_SecondaryCategories](./get_secondarycategories/) null है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() override | सीरीज़ प्राप्त करता है। केवल-पढ़ने योग्य [IChartSeriesCollection](../ichartseriescollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर सीरीज़ समूह लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() override | सीरीज़ समूह प्राप्त करता है। केवल-पढ़ने योग्य [IChartSeriesGroupCollection](../ichartseriesgroupcollection/)। |
| **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() override | यदि false सेट किया गया है तो [ChartData::get_SecondaryCategories](./get_secondarycategories/) null लौटाता है और [ChartData::get_Categories](./get_categories/) में डेटा दोनों प्राथमिक और द्वितीयक सीरीज़ के लिए उपयोग किया जाता है। यदि true सेट किया गया है तो [ChartData::get_SecondaryCategories](./get_secondarycategories/) में डेटा द्वितीयक सीरीज़ के लिए और [ChartData::get_Categories](./get_categories/) में डेटा प्राथमिक सीरीज़ के लिए उपयोग किया जाता है। पढ़ें **bool**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का तुल्य। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| [System::String](../../system/string/) [GetRange](./getrange/)() override | चार्ट डेटा रेंज प्राप्त करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का तुल्य। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचें कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का तुल्य। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने के लिए लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का तुल्य। कस्टम टाइप्स को क्लोन करना सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() override | आंतरिक रूप से निहित [Excel](../../aspose.slides.excel/) वर्कबुक को मेमोरी-में-स्ट्रीम में लिखता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की तुलना nullptr से रेफ़रेंस द्वारा करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन स्ट्रिंग और nullptr के केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन स्ट्रिंग्स के केस के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) override | यदि false सेट किया गया है तो [ChartData::get_SecondaryCategories](./get_secondarycategories/) null लौटाता है और [ChartData::get_Categories](./get_categories/) में डेटा दोनों प्राथमिक और द्वितीयक सीरीज़ के लिए उपयोग किया जाता है। यदि true सेट किया गया है तो [ChartData::get_SecondaryCategories](./get_secondarycategories/) में डेटा द्वितीयक सीरीज़ के लिए और [ChartData::get_Categories](./get_categories/) में डेटा प्राथमिक सीरीज़ के लिए उपयोग किया जाता है। लिखें **bool**। |
| void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) override | चार्ट के लिए बाहरी वर्कबुक को डेटा स्रोत के रूप में सेट करता है। [Chart](../chart/) डेटा लक्ष्य वर्कबुक से अपडेट किया जाएगा। |
| void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) override | चार्ट के लिए बाहरी वर्कबुक को डेटा स्रोत के रूप में सेट करता है। |
| void [SetRange](./setrange/)([System::String](../../system/string/)) override | चार्ट डेटा रेंज सेट करें। नई डेटा रेंज के आधार पर सीरीज़ और श्रेणियाँ अपडेट की जाएँगी। यदि डेटा रेंज में सीरीज़ की संख्या चार्ट डेटा में सीरीज़ की गिनती से अधिक है तो वर्तमान संग्रह में अंतिम सीरीज़ के समान प्रकार की अतिरिक्त सीरीज़ को संग्रह के अंत में जोड़ा जाएगा। |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n'th टेम्प्लेट आर्ग्यूमेंट को एक वीक पॉइंटर (शेयर किए गये के बजाय) सेट करें। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [SwitchRowColumn](./switchrowcolumn/)() override | डेटा को अक्ष के पार स्वैप करें। X-अक्ष पर चार्ट किया गया डेटा Y-अक्ष पर जाएगा और इसके विपरीत। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का तुल्य। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने के लिए लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) override | आंतरिक रूप से निहित [Excel](../../aspose.slides.excel/) वर्कबुक को उपयोगकर्ता-निर्दिष्ट मान से इनिशियलाइज़ करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें भी

* क्लास [DomObject](../../aspose.slides/domobject/)
* क्लास [IChartData](../ichartdata/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)