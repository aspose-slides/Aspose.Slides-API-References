---
title: ChartTitle
second_title: Aspose.Slides for C++ API संदर्भ
description: चार्ट शीर्षक गुणों का प्रतिनिधित्व करता है।
type: docs
weight: 326
url: /hi/aspose.slides.charts/charttitle/
---
## ChartTitle वर्ग

चार्ट शीर्षक गुणों का प्रतिनिधित्व करता है।

```cpp
class ChartTitle : public Aspose::Slides::Charts::IChartTitle,
                   public Aspose::Slides::IDOMObject
```

## विधियां

| विधि | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | पैरामीटर "text" में दिए गए पाठ के साथ TextFrameForOverriding को प्रारंभ करता है। यदि TextFrameForOverriding पहले से ही प्रारंभ किया गया है तो केवल उसके पाठ को बदलता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **float** [get_ActualHeight](./get_actualheight/)() override | चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। पढ़ें **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। पढ़ें **float**. |
| **float** [get_ActualX](./get_actualx/)() override | चार्ट तत्व का वास्तविक x स्थान (बाएँ) चार्ट के बाएँ शीर्ष कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। पढ़ें **float**. |
| **float** [get_ActualY](./get_actualy/)() override | चार्ट तत्व का वास्तविक शीर्ष चार्ट के बाएँ शीर्ष कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। पढ़ें **float**. |
| **float** [get_Bottom](./get_bottom/)() override | निचला भाग। केवल- पढ़ने योग्य **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | पैरेंट चार्ट लौटाता है। केवल- पढ़ने योग्य [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | शीर्षक की फ़िल, लाइन, इफ़ेक्ट शैलियों को लौटाता है। केवल- पढ़ने योग्य [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | शीर्षक की ऊँचाई को चार्ट की ऊँचाई के अंश के रूप में लौटाता है। पढ़ें **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | निर्धारित करता है कि क्या अन्य चार्ट तत्वों को शीर्षक के ऊपर ओवरलैप करने की अनुमति हो। पढ़ें **bool**. |
| **float** [get_Right](./get_right/)() override | दाएँ। केवल- पढ़ने योग्य **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | पाठ स्वरूप लौटाता है। केवल- पढ़ने योग्य [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | समृद्ध स्वरूपित पाठ रख सकता है। यदि यह गुण null नहीं है तो यह स्वरूपित पाठ मान स्वचालित रूप से उत्पन्न पाठ को ओवरराइड करता है। स्वचालित रूप से उत्पन्न पाठ डेटा लेबल, वैल्यू एक्सिस की डिस्प्ले यूनिट लेबल, एक्सिस शीर्षक, चार्ट शीर्षक, ट्रेंडलाइन की लेबल की अप्रत्यक्ष गुण है। स्वचालित रूप से उत्पन्न पाठ [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) गुण के साथ स्वरूपित किया जाता है। केवल- पढ़ने योग्य [ITextFrame](../../aspose.slides/itextframe/). |
| **float** [get_Width](./get_width/)() override | शीर्षक की चौड़ाई को चार्ट की चौड़ाई के अंश के रूप में लौटाता है। पढ़ें **float**. |
| **float** [get_X](./get_x/)() override | शीर्षक के x निर्देशांक को चार्ट की चौड़ाई के अंश के रूप में लौटाता है। पढ़ें **float**. |
| **float** [get_Y](./get_y/)() override | शीर्षक के y निर्देशांक को चार्ट की ऊँचाई के अंश के रूप में लौटाता है। पढ़ें **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार के ऑब्जेक्ट की रेफ़रेंस तुलना nullptr से करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Height](./set_height/)(**float**) override | शीर्षक की ऊँचाई को चार्ट की ऊँचाई के अंश के रूप में सेट करता है। लिखें **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | निर्धारित करता है कि क्या अन्य चार्ट तत्वों को शीर्षक के ऊपर ओवरलैप करने की अनुमति हो। लिखें **bool**. |
| void [set_Width](./set_width/)(**float**) override | शीर्षक की चौड़ाई को चार्ट की चौड़ाई के अंश के रूप में सेट करता है। लिखें **float**. |
| void [set_X](./set_x/)(**float**) override | शीर्षक के x निर्देशांक को चार्ट की चौड़ाई के अंश के रूप में सेट करता है। लिखें **float**. |
| void [set_Y](./set_y/)(**float**) override | शीर्षक के y निर्देशांक को चार्ट की ऊँचाई के अंश के रूप में सेट करता है। लिखें **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को एक weak पॉइंटर सेट करता है (shared के बजाय)। कंटेनरों में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखिए

* वर्ग [IChartTitle](../icharttitle/)
* वर्ग [IDOMObject](../../aspose.slides/idomobject/)
* नामस्थान [Aspose::Slides::Charts](../)
* पुस्तकालय [Aspose.Slides](../../)