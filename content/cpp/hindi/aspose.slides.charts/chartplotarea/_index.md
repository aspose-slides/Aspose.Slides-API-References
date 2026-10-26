---
title: ChartPlotArea
second_title: Aspose.Slides for C++ API संदर्भ
description: वह आयत दर्शाता है जहाँ चार्ट प्लॉट किया जाना चाहिए।
type: docs
weight: 248
url: /hi/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea वर्ग


Represents rectangle where chart should be plotted.

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **float** [get_ActualHeight](./get_actualheight/)() override | चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। **float** पढ़ें। |
| **float** [get_ActualWidth](./get_actualwidth/)() override | चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। **float** पढ़ें। |
| **float** [get_ActualX](./get_actualx/)() override | चार्ट तत्व का वास्तविक x स्थान (बायां) चार्ट के बाएँ ऊपर कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। **float** पढ़ें। |
| **float** [get_ActualY](./get_actualy/)() override | चार्ट तत्व का वास्तविक शीर्ष चार्ट के बाएँ ऊपर कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। **float** पढ़ें। |
| **float** [get_Bottom](./get_bottom/)() override | निचला। केवल-पढ़ने योग्य **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/). केवल-पढ़ने योग्य [IChart](../ichart/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | प्लॉट एरिया का फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IFormat](../iformat/)। |
| **float** [get_Height](./get_height/)() override | प्लॉट एरिया बाउंडिंग बॉक्स की ऊँचाई को चार्ट की ऊँचाई के अनुपात (0 से 1) के रूप में लौटाता है। **float** पढ़ें। |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | निर्धारित करता है कि स्थान कैसे गणना किया जाना चाहिए: true – स्वतः गणना किया गया; X, Y, Width, Height प्रॉपर्टीज़ द्वारा परिभाषित। केवल-पढ़ने योग्य **bool**। |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | यदि प्लॉट एरिया का लेआउट मैन्युअल रूप से परिभाषित है, तो यह प्रॉपर्टी निर्धारित करती है कि प्लॉट एरिया को उसके अंदर (एक्सिस और लेबल को छोड़कर) या बाहर (एक्सिस और लेबल सहित) लेआउट किया जाए। पढ़ें [LayoutTargetType](../layouttargettype/)। |
| **float** [get_Right](./get_right/)() override | दायां। केवल-पढ़ने योग्य **float**। |
| **float** [get_Width](./get_width/)() override | प्लॉट एरिया बाउंडिंग बॉक्स की चौड़ाई को चार्ट की चौड़ाई के अनुपात (0 से 1) के रूप में लौटाता है। **float** पढ़ें। |
| **float** [get_X](./get_x/)() override | प्लॉट एरिया बाउंडिंग बॉक्स के ऊपर बाएँ कोने का x समन्वय को चार्ट की चौड़ाई के अनुपात (0 से 1) के रूप में लौटाता है। **float** पढ़ें। |
| **float** [get_Y](./get_y/)() override | प्लॉट एरिया बाउंडिंग बॉक्स के ऊपर बाएँ कोने का y समन्वय को चार्ट की ऊँचाई के अनुपात (0 से 1) के रूप में लौटाता है। **float** पढ़ें। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानरूप। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानरूप। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचें कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानरूप। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानरूप। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। कुछ नहीं कॉपी करता, बल्कि नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम बनाता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। कुछ नहीं कॉपी करता, बल्कि नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम बनाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्धारित मान द्वारा साझा रेफ़रेंस काउंट को कम करता है। |
| void [set_Height](./set_height/)(**float**) override | प्लॉट एरिया बाउंडिंग बॉक्स की ऊँचाई को चार्ट की ऊँचाई के अनुपात (0 से 1) के रूप में सेट करता है। **float** लिखें। |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | यदि प्लॉट एरिया का लेआउट मैन्युअल रूप से परिभाषित है, तो यह प्रॉपर्टी निर्धारित करती है कि प्लॉट एरिया को उसके अंदर (एक्सिस और लेबल को छोड़कर) या बाहर (एक्सिस और लेबल सहित) लेआउट किया जाए। [LayoutTargetType](../layouttargettype/) लिखें। |
| void [set_Width](./set_width/)(**float**) override | प्लॉट एरिया बाउंडिंग बॉक्स की चौड़ाई को चार्ट की चौड़ाई के अनुपात (0 से 1) के रूप में सेट करता है। **float** लिखें। |
| void [set_X](./set_x/)(**float**) override | प्लॉट एरिया बाउंडिंग बॉक्स के ऊपर बाएँ कोने का x समन्वय को चार्ट की चौड़ाई के अनुपात (0 से 1) के रूप में सेट करता है। **float** लिखें। |
| void [set_Y](./set_y/)(**float**) override | प्लॉट एरिया बाउंडिंग बॉक्स के ऊपर बाएँ कोने का y समन्वय को चार्ट की ऊँचाई के अनुपात (0 से 1) के रूप में सेट करता है। **float** लिखें। |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n'th टेम्पलेट आर्ग्युमेंट को एक weak पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनर में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानरूप। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## संबंधित देखें

* क्लास [DomObject](../../aspose.slides/domobject/)
* क्लास [IChartPlotArea](../ichartplotarea/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)