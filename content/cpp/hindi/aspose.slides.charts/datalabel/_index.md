---
title: DataLabel
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: एक श्रृंखला लेबल्स का प्रतिनिधित्व करता है।
type: docs
weight: 365
url: /hi/aspose.slides.charts/datalabel/
---
## DataLabel वर्ग

एक श्रृंखला लेबल्स का प्रतिनिधित्व करता है।

```cpp
class DataLabel : public Aspose::Slides::Charts::IDataLabel,
                  public Aspose::Slides::IDOMObject
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | TextFrameForOverriding को पैरामीटर \"text\" में दिए गए टेक्स्ट के साथ प्रारंभ करता है। यदि TextFrameForOverriding पहले से ही प्रारंभ किया गया है तो केवल उसका टेक्स्ट बदल देता है। |
|  [DataLabel](./datalabel/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) | एक नया [DataLabel](./) वर्ग बनाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में संदर्भ प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मूल्य के बराबर नहीं होता, इसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मूल्य के बराबर नहीं होता, इसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| **float** [get_ActualHeight](./get_actualheight/)() override | चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) मेथड को कॉल करें। पढ़ें **float**। |
| **float** [get_ActualWidth](./get_actualwidth/)() override | चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) मेथड को कॉल करें। पढ़ें **float**। |
| **float** [get_ActualX](./get_actualx/)() override | चार्ट तत्व के बाएँ शीर्ष कोने के सापेक्ष चार्ट तत्व के वास्तविक x स्थान (बायाँ) को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) मेथड को कॉल करें। पढ़ें **float**। |
| **float** [get_ActualY](./get_actualy/)() override | चार्ट तत्व के बाएँ शीर्ष कोने के सापेक्ष चार्ट तत्व की वास्तविक शीर्ष स्थिति को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिये पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) मेथड को कॉल करें। पढ़ें **float**। |
| **float** [get_Bottom](./get_bottom/)() override | निचला भाग। केवल-रीड **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | पैरेंट चार्ट लौटाता है। केवल-रीड [IChart](../ichart/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() override | डेटा लेबल फॉर्मेट लौटाता है। केवल-रीड [IDataLabelFormat](../idatalabelformat/)। |
| **float** [get_Height](./get_height/)() override | शीर्षक की ऊँचाई को चार्ट की ऊँचाई के अनुपात में लौटाता है। पढ़ें **float**। |
| **bool** [get_IsVisible](./get_isvisible/)() override | False का मतलब है कि डेटा लेबल दृश्यमान नहीं है (और इसलिए सभी Show*-फ़्लैग्स (ShowValue, ...) false होते हैं)। केवल-रीड **bool**। |
| **float** [get_Right](./get_right/)() override | दाएँ। केवल-रीड **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | टेक्स्ट फॉर्मेट लौटाता है। केवल-रीड [IChartTextFormat](../icharttextformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | रिच फ़ॉर्मेटेड टेक्स्ट रख सकता है। यदि यह प्रॉपर्टी null नहीं है तो यह फ़ॉर्मेटेड टेक्स्ट मान डेटा लेबल के स्वचालित उत्पन्न टेक्स्ट को ओवरराइड करता है। डेटा लेबल का स्वचालित उत्पन्न टेक्स्ट का मतलब है वह टेक्स्ट जो ShowSeriesName, ShowValue, ... प्रॉपर्टीज़ द्वारा प्रबंधित होता है और TextFormatManager.TextFormat प्रॉपर्टी से फ़ॉर्मेट किया जाता है। केवल-रीड [ITextFrame](../../aspose.slides/itextframe/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() override | वर्कबुक डेटा सेल प्राप्त करता है। लागू किया जाता है यदि IDataLabelFormat::get(set)_ShowLabelValueFromCell प्रॉपर्टी true के बराबर है। |
| **float** [get_Width](./get_width/)() override | शीर्षक की चौड़ाई को चार्ट की चौड़ाई के अनुपात में लौटाता है। पढ़ें **float**। |
| **float** [get_X](./get_x/)() override | शीर्षक के x समन्वय को चार्ट की चौड़ाई के अनुपात में लौटाता है। पढ़ें **float**। |
| **float** [get_Y](./get_y/)() override | शीर्षक के y समन्वय को चार्ट की ऊँचाई के अनुपात में लौटाता है। पढ़ें **float**। |
| [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() override | [DataLabelFormat](../datalabelformat/) सेटिंग्स या [get_TextFrameForOverriding()](./get_textframeforoverriding/)->get(set)_Text() मान के आधार पर वास्तविक लेबल टेक्स्ट लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| void [Hide](./hide/)() override | सभी Show*-फ़्लैग्स (ShowValue, ...) को false सेट करके डेटा लेबल को छिपा देता है। इसके बाद IsVisible false होगा। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँच करता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार के इंस्टेंस को दर्शाता है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | नल पॉइंटर के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और नल पॉइंटर के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Height](./set_height/)(**float**) override | शीर्षक की ऊँचाई को चार्ट की ऊँचाई के अनुपात में सेट करता है। **float** लिखें। |
| void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | वर्कबुक डेटा सेल सेट करता है। लागू किया जाता है यदि IDataLabelFormat::get(set)_ShowLabelValueFromCell प्रॉपर्टी true के बराबर है। |
| void [set_Width](./set_width/)(**float**) override | शीर्षक की चौड़ाई को चार्ट की चौड़ाई के अनुपात में सेट करता है। **float** लिखें। |
| void [set_X](./set_x/)(**float**) override | शीर्षक के x समन्वय को चार्ट की चौड़ाई के अनुपात में सेट करता है। **float** लिखें। |
| void [set_Y](./set_y/)(**float**) override | शीर्षक के y समन्वय को चार्ट की ऊँचाई के अनुपात में सेट करता है। **float** लिखें। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का प्रयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का प्रयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉक करना लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का प्रयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का प्रयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* वर्ग [IDataLabel](../idatalabel/)
* वर्ग [IDOMObject](../../aspose.slides/idomobject/)
* नामस्थान [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)