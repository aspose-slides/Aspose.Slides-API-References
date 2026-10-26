---
title: IChartPlotArea
second_title: Aspose.Slides for C++ API संदर्भ
description: चार्ट शीर्षक गुणों का प्रतिनिधित्व करता है।
type: docs
weight: 794
url: /hi/aspose.slides.charts/ichartplotarea/
---
## IChartPlotArea क्लास

चार्ट शीर्षक गुणों का प्रतिनिधित्व करता है।

```cpp
class IChartPlotArea : public Aspose::Slides::Charts::ILayoutable,
                       public Aspose::Slides::Charts::IActualLayout
```

## विधियाँ

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) मेथड को कॉल करें। पढ़ें **float**। |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) मेथड को कॉल करें। पढ़ें **float**। |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | चार्ट तत्व के बाएँ-ऊपरी कोने के सापेक्ष चार्ट तत्व का वास्तविक x स्थान (बायाँ) निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) मेथड को कॉल करें। पढ़ें **float**। |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | चार्ट तत्व के बाएँ-ऊपरी कोने के सापेक्ष चार्ट तत्व के वास्तविक शीर्ष को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) मेथड को कॉल करें। पढ़ें **float**। |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | चार्ट की ऊँचाई के अंश के रूप में चार्ट तत्व के शीर्ष को प्राप्त करता है। केवल पढ़ने योग्य **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | चार्ट लौटाता है। केवल पढ़ने योग्य [IChart](../ichart/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | प्लॉट एरिया का फ़ॉर्मेट लौटाता है। केवल पढ़ने योग्य [IFormat](../iformat/)। |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | चार्ट की ऊँचाई के अंश के रूप में चार्ट तत्व की ऊँचाई निर्दिष्ट करता है। पढ़ें **float**। |
| virtual [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() | यदि प्लॉट एरिया की लेआउट मैन्युअल रूप से परिभाषित है, तो यह गुण यह निर्दिष्ट करता है कि प्लॉट एरिया को उसकी अंदरूनी (अक्ष और अक्ष लेबल सहित नहीं) या बाहरी (अक्ष और अक्ष लेबल सहित) भाग के अनुसार व्यवस्थित किया जाए। पढ़ें [LayoutTargetType](../layouttargettype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | प्रेजेंटेशन लौटाता है। केवल पढ़ने योग्य [IPresentation](../../aspose.slides/ipresentation/)। |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | चार्ट की चौड़ाई के अंश के रूप में चार्ट तत्व के दाएँ भाग को प्राप्त करता है। केवल पढ़ने योग्य **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल पढ़ने योग्य [IBaseSlide](../../aspose.slides/ibaseslide/)। |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | चार्ट की चौड़ाई के अंश के रूप में चार्ट तत्व की चौड़ाई निर्दिष्ट करता है। पढ़ें **float**। |
| virtual **float** [get_X](../ilayoutable/get_x/)() | चार्ट की चौड़ाई के अंश के रूप में चार्ट तत्व के x स्थान (बायाँ) को निर्दिष्ट करता है। पढ़ें **float**। |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | चार्ट की ऊँचाई के अंश के रूप में चार्ट तत्व के शीर्ष को निर्दिष्ट करता है। पढ़ें **float**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफरेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स का क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्टिंग सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्टिंग सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | चार्ट की ऊँचाई के अंश के रूप में चार्ट तत्व की ऊँचाई निर्दिष्ट करता है। लिखें **float**। |
| virtual void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) | यदि प्लॉट एरिया की लेआउट मैन्युअल रूप से परिभाषित है, तो यह गुण यह निर्दिष्ट करता है कि प्लॉट एरिया को उसकी अंदरूनी (अक्ष और अक्ष लेबल शामिल नहीं) या बाहरी (अक्ष और अक्ष लेबल सहित) भाग के अनुसार व्यवस्थित किया जाए। लिखें [LayoutTargetType](../layouttargettype/)। |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | चार्ट की चौड़ाई के अंश के रूप में चार्ट तत्व की चौड़ाई निर्दिष्ट करता है। लिखें **float**। |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | चार्ट की चौड़ाई के अंश के रूप में चार्ट तत्व के x स्थान (बायाँ) को निर्दिष्ट करता है। लिखें **float**। |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | चार्ट की ऊँचाई के अंश के रूप में चार्ट तत्व के शीर्ष को निर्दिष्ट करता है। लिखें **float**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्युमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [ILayoutable](../ilayoutable/)
* क्लास [IActualLayout](../iactuallayout/)
* नामस्थान [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)