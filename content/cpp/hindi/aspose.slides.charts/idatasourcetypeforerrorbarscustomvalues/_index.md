---
title: IDataSourceTypeForErrorBarsCustomValues
second_title: Aspose.Slides for C++ API संदर्भ
description: ChartDataPoint.ErrorBarsCustomValues प्रॉपर्टी सूची में मानों के प्रकार निर्दिष्ट करता है
type: docs
weight: 976
url: /hi/aspose.slides.charts/idatasourcetypeforerrorbarscustomvalues/
---
## IDataSourceTypeForErrorBarsCustomValues क्लास

ChartDataPoint.ErrorBarsCustomValues प्रॉपर्टी सूची में मानों के प्रकार निर्दिष्ट करता है

```cpp
class IDataSourceTypeForErrorBarsCustomValues : public virtual System::Object
```

## विधियां

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-style फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-style फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXMinusValues](./get_datasourcetypeforxminusvalues/)() | निर्दिष्ट करता है कि AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी त्रुटि बार कस्टम मानों के लिए डेटा पॉइंट्स XMinus प्रॉपर्टी ऑब्जेक्ट में वास्तविक है या नहीं। दूसरे शब्दों में, यह ChartDataPoint.ErrorBarsCustomValues.XMinus.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें [DataSourceType](../datasourcetype/)। |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXPlusValues](./get_datasourcetypeforxplusvalues/)() | निर्दिष्ट करता है कि AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी त्रुटि बार कस्टम मानों के लिए डेटा पॉइंट्स XPlus प्रॉपर्टी ऑब्जेक्ट में वास्तविक है या नहीं। दूसरे शब्दों में, यह ChartDataPoint.ErrorBarsCustomValues.XPlus.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें [DataSourceType](../datasourcetype/)। |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYMinusValues](./get_datasourcetypeforyminusvalues/)() | निर्दिष्ट करता है कि AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी त्रुटि बार कस्टम मानों के लिए डेटा पॉइंट्स YMinus प्रॉपर्टी ऑब्जेक्ट में वास्तविक है या नहीं। दूसरे शब्दों में, यह ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें [DataSourceType](../datasourcetype/)। |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYPlusValues](./get_datasourcetypeforyplusvalues/)() | निर्दिष्ट करता है कि AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी त्रुटि बार कस्टम मानों के लिए डेटा पॉइंट्स YPlus प्रॉपर्टी ऑब्जेक्ट में वास्तविक है या नहीं। दूसरे शब्दों में, यह ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें [DataSourceType](../datasourcetype/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समान। कस्टम ऑब्जेक्ट्स के हैश बनाने को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समान। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | नलपॉइंट के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग और nullptr केस के लिए विशेषीकृत संस्करण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग्स केस के लिए विशेषीकृत संस्करण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_DataSourceTypeForXMinusValues](./set_datasourcetypeforxminusvalues/)([DataSourceType](../datasourcetype/)) | त्रुटि बार कस्टम मानों के लिए डेटा पॉइंट्स XMinus प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। दूसरे शब्दों में, यह ChartDataPoint.ErrorBarsCustomValues.XMinus.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। लिखें [DataSourceType](../datasourcetype/)। |
| virtual void [set_DataSourceTypeForXPlusValues](./set_datasourcetypeforxplusvalues/)([DataSourceType](../datasourcetype/)) | त्रुटि बार कस्टम मानों के लिए डेटा पॉइंट्स XPlus प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। दूसरे शब्दों में, यह ChartDataPoint.ErrorBarsCustomValues.XPlus.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। लिखें [DataSourceType](../datasourcetype/)। |
| virtual void [set_DataSourceTypeForYMinusValues](./set_datasourcetypeforyminusvalues/)([DataSourceType](../datasourcetype/)) | त्रुटि बार कस्टम मानों के लिए डेटा पॉइंट्स YMinus प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। दूसरे शब्दों में, यह ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। लिखें [DataSourceType](../datasourcetype/)। |
| virtual void [set_DataSourceTypeForYPlusValues](./set_datasourcetypeforyplusvalues/)([DataSourceType](../datasourcetype/)) | त्रुटि बार कस्टम मानों के लिए डेटा पॉइंट्स YPlus प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। दूसरे शब्दों में, यह ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। लिखें [DataSourceType](../datasourcetype/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को एक कमजोर पॉइंटर सेट करता है (शेयर्ड की बजाय)। कंटेनरों में पॉइंटर को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समान। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [Object](../../system/object/)
* नामस्थान [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)