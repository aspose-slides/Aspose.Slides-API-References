---
title: IErrorBarsFormat
second_title: Aspose.Slides for C++ API संदर्भ
description: "चार्ट सीरीज़ की त्रुटि बार को दर्शाता है। ErrorBars कस्टम मान IChartDataPointCollection में होते हैं (IChartDataPoint::get_ErrorBarsCustomValues() प्रॉपर्टी में)।"
type: docs
weight: 1028
url: /hi/aspose.slides.charts/ierrorbarsformat/
---
## IErrorBarsFormat वर्ग


चार्ट सीरीज़ की त्रुटि बार को दर्शाता है। ErrorBars कस्टम मान [IChartDataPointCollection](../ichartdatapointcollection/) में होते हैं ([IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) प्रॉपर्टी में)।  

```cpp
class IErrorBarsFormat : public Aspose::Slides::Charts::IChartComponent
```

## विधियाँ

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक का उपयोग करके ऑब्जेक्ट की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../ichart/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | त्रुटि बार के स्वरूप को दर्शाता है। पढ़ें [IFormat](../iformat/)। |
| virtual **bool** [get_HasEndCap](./get_hasendcap/)() | निर्दर्श करता है कि त्रुटि बार पर एंड कैप नहीं खींचा गया है। पढ़ें **bool**। |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | त्रुटि बार की दृश्यमानता प्राप्त करता है। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../aspose.slides/ipresentation/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../../aspose.slides/ibaseslide/)। |
| virtual [ErrorBarType](../errorbartype/) [get_Type](./get_type/)() | त्रुटि बार का प्रकार प्राप्त करता है। पढ़ें [ErrorBarType](../errorbartype/)। |
| virtual **float** [get_Value](./get_value/)() | त्रुटि बार की लंबाई निर्धारित करने के लिए Fixed, Percentage और StandardDeviation वैल्यू टाइप के साथ उपयोग किया जाने वाला मान प्राप्त करता है। पढ़ें **float**। |
| virtual [ErrorBarValueType](../errorbarvaluetype/) [get_ValueType](./get_valuetype/)() | त्रुटि बार की लंबाई निर्धारित करने के संभावित तरीकों को दर्शाता है। कस्टम वैल्यू टाइप के मामले में मान निर्दिष्ट करने के लिए सीरीज़ के DataPoints संग्रह में विशिष्ट डेटा पॉइंट की [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) प्रॉपर्टी का उपयोग करें।\n\n पढ़ें [ErrorBarValueType](../errorbarvaluetype/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग और nullptr के मामले के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग्स के मामले के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | त्रुटि बार के स्वरूप को दर्शाता है। लिखें [IFormat](../iformat/)। |
| virtual void [set_HasEndCap](./set_hasendcap/)(**bool**) | निर्दर्श करता है कि त्रुटि बार पर एंड कैप नहीं खींचा गया है। लिखें **bool**। |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | त्रुटि बार की दृश्यमानता सेट करता है। लिखें **bool**। |
| virtual void [set_Type](./set_type/)([ErrorBarType](../errorbartype/)) | त्रुटि बार का प्रकार सेट करता है। लिखें [ErrorBarType](../errorbartype/)। |
| virtual void [set_Value](./set_value/)(**float**) | त्रुटि बार की लंबाई निर्धारित करने के लिए Fixed, Percentage और StandardDeviation वैल्यू टाइप के साथ उपयोग किया जाने वाला मान सेट करता है। लिखें **float**। |
| virtual void [set_ValueType](./set_valuetype/)([ErrorBarValueType](../errorbarvaluetype/)) | त्रुटि बार की लंबाई निर्धारित करने के संभावित तरीकों को दर्शाता है। कस्टम वैल्यू टाइप के मामले में मान निर्दिष्ट करने के लिए सीरीज़ के DataPoints संग्रह में विशिष्ट डेटा पॉइंट की [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) प्रॉपर्टी का उपयोग करें।\n\n लिखें [ErrorBarValueType](../errorbarvaluetype/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) |  n'th टेम्प्लेट आर्ग्युमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कॉन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Weak रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Weak रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संबंधित देखें

* वर्ग [IChartComponent](../ichartcomponent/)
* नामस्थान [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)