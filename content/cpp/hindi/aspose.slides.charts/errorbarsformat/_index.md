---
title: ErrorBarsFormat
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "चार्ट सीरीज़ की एरर बार्स का प्रतिनिधित्व करता है। ErrorBars कस्टम वैल्यूज़ IChartDataPointCollection में हैं (IChartDataPoint::get_ErrorBarsCustomValues() प्रॉपर्टी में)।"
type: docs
weight: 482
url: /hi/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat क्लास

Represents error bars of chart series. ErrorBars कस्टम वैल्यूज़ [IChartDataPointCollection](../ichartdatapointcollection/) में हैं ([IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) प्रॉपर्टी में)।

```cpp
class ErrorBarsFormat : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::ChartSeries>>,
                        public Aspose::Slides::Charts::IErrorBarsFormat
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | सिर्फ़ आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | पैरेंट चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../ichart/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | एरर बार्स के फॉर्मेट का प्रतिनिधित्व करता है। पढ़ें [IFormat](../iformat/)। |
| **bool** [get_HasEndCap](./get_hasendcap/)() override | निर्दिष्ट करता है कि एरर बार्स पर एंड कैप नहीं बनाया गया है। पढ़ें **bool**। |
| **bool** [get_IsVisible](./get_isvisible/)() override | एरर बार्स की दृश्यता प्राप्त करता है। पढ़ें **bool**। |
| [ErrorBarType](../errorbartype/) [get_Type](./get_type/)() override | एरर बार्स का प्रकार प्राप्त करता है। पढ़ें [ErrorBarType](../errorbartype/)। |
| **float** [get_Value](./get_value/)() override | फ़िक्स्ड, प्रतिशत और स्टैंडर्ड डिविएशन वैल्यू टाइप्स के साथ उपयोग की जाने वाली मान प्राप्त करता है जिससे एरर बार्स की लंबाई निर्धारित की जाती है। किसी भी अन्य केस में NaN लौटाता है। पढ़ें **float**। |
| [ErrorBarValueType](../errorbarvaluetype/) [get_ValueType](./get_valuetype/)() override | एरर बार्स की लंबाई निर्धारित करने के संभावित तरीकों का प्रतिनिधित्व करता है। कस्टम वैल्यू टाइप के मामले में मान निर्दिष्ट करने के लिए सीरीज़ की DataPoints कलेक्शन में विशिष्ट डेटा पॉइंट की [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) प्रॉपर्टी का उपयोग करें। Fixed, Percentage या StandardDeviation वैल्यू टाइप के मामले में मान निर्दिष्ट करने के लिए Value प्रॉपर्टी का उपयोग करें। 

पढ़ें [ErrorBarValueType](../errorbarvaluetype/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का अनालॉग। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का अनालॉग। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप की एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का अनालॉग। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का अनालॉग। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | एरर बार्स के फॉर्मेट का प्रतिनिधित्व करता है। लिखें [IFormat](../iformat/)। |
| void [set_HasEndCap](./set_hasendcap/)(**bool**) override | निर्दिष्ट करता है कि एरर बार्स पर एंड कैप नहीं बनाया गया है। लिखें **bool**। |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | एरर बार्स की दृश्यता सेट करता है। लिखें **bool**। |
| void [set_Type](./set_type/)([ErrorBarType](../errorbartype/)) override | एरर बार्स का प्रकार सेट करता है। लिखें [ErrorBarType](../errorbartype/)। |
| void [set_Value](./set_value/)(**float**) override | फ़िक्स्ड, प्रतिशत और स्टैंडर्ड डिविएशन वैल्यू टाइप्स के साथ उपयोग की जाने वाली मान सेट करता है जिससे एरर बार्स की लंबाई निर्धारित होती है। किसी भी अन्य केस में NaN लौटाता है। लिखें **float**। |
| void [set_ValueType](./set_valuetype/)([ErrorBarValueType](../errorbarvaluetype/)) override | एरर बार्स की लंबाई निर्धारित करने के संभावित तरीकों का प्रतिनिधित्व करता है। कस्टम वैल्यू टाइप के मामले में मान निर्दिष्ट करने के लिए सीरीज़ की DataPoints कलेक्शन में विशिष्ट डेटा पॉइंट की [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) प्रॉपर्टी का उपयोग करें। Fixed, Percentage या StandardDeviation वैल्यू टाइप के मामले में मान निर्दिष्ट करने के लिए Value प्रॉपर्टी का उपयोग करें। 

लिखें [ErrorBarValueType](../errorbarvaluetype/)। |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n'th टेम्पलेट आर्ग्यूमेंट को वीक पॉइंटर (शेयर किए जाने के बजाय) सेट करता है। कंटेनर में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का मौजूदा मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं होना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं होना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का अनालॉग। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं होना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं होना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें भी

* क्लास [DomObject](../../aspose.slides/domobject/)
* क्लास [IErrorBarsFormat](../ierrorbarsformat/)
* नामस्थान [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)