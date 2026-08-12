---
title: BoxedValue< ValueTuple< Args... > >
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वैल्यू ट्यूपल का बॉक्स्ड संस्करण।
type: docs
weight: 118
url: /hi/system/boxedvalue_tmpl_valuetuple_tmpl_args_dots__end_tmpl__end_tmpl/
---
## BoxedValue< ValueTuple< Args... > > क्लास


वैल्यू ट्यूपल का बॉक्स्ड संस्करण।

```cpp
template<typename...>class BoxedValue< ValueTuple< Args... > > : public System::Runtime::CompilerServices::ITuple
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| name | Args ट्यूपल तत्व प्रकार। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  [BoxedValue](./boxedvalue/)(const [ValueT](../valuetuple/)\&) | एक [BoxedValue](../boxedvalue/) ऑब्जेक्ट बनाता है जो निर्दिष्ट मान को बॉक्स्ड प्रस्तुत करता है। |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | वर्तमान और निर्दिष्ट ऑब्जेक्ट्स द्वारा दर्शाए गए बॉक्स्ड मानों की समानता निर्धारित करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस प्रकार के ऑब्जेक्ट्स की C# शैली में तुलना करता है। |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-शैली वाले फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-शैली वाले फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| int [GetHashCode](./gethashcode/)() const override | वर्तमान ऑब्जेक्ट के लिए हैश कोड लौटाता है। |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। |
| virtual [SharedPtr](../sharedptr/)\<[Object](../object/)\> [idx_get](../../system.runtime.compilerservices/ituple/idx_get/)(**int32_t**) const | इंडेक्स स्थिति पर तत्व लौटाता है। |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# के 'is' ऑपरेटर के समान। |
| **bool** [is](./is/)() const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए बॉक्स्ड मान का प्रकार **V** है या नहीं। |
| void [Lock](../object/lock/)() | C# lock() कथन के लॉक को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) मेथड के समान। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरम्भ करता है। |
|  [Object](../object/object/)([Object](../object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरम्भ करता है और सबक्लासों की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरम्भ करता है और सबक्लासों की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | मान प्रकार ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्यूमेंट को एक कमजोर पोइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [String](../string/) [ToString](./tostring/)() const override | बॉक्स्ड मान का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) निर्माण को लागू करता है। |
| const [ValueT](../valuetuple/)\& [unbox](./unbox/)() const | बॉक्स्ड मान को अनबॉक्स करता है। |
| void [Unlock](../object/unlock/)() | C# lock() कथन के अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संबंधित देखें

* क्लास [ITuple](../../system.runtime.compilerservices/ituple/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)