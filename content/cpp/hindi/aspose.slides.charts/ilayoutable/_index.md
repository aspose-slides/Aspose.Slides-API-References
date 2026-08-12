---
title: ILayoutable
second_title: Aspose.Slides for C++ API संदर्भ
description: एक चार्ट तत्व की सटीक स्थिति निर्दिष्ट करता है।
type: docs
weight: 1067
url: /hi/aspose.slides.charts/ilayoutable/
---
## ILayoutable क्लास

एक चार्ट तत्व की सटीक स्थिति निर्दिष्ट करता है।

```cpp
class ILayoutable : public virtual Aspose::Slides::Charts::IChartComponent
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके ऑब्जेक्ट की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है, ऐसी C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है, ऐसी C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual **float** [get_Bottom](./get_bottom/)() | चार्ट तत्व के शीर्ष को चार्ट की ऊँचाई के हिस्से के रूप में प्राप्त करता है। पढ़ने-केवल **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | चार्ट लौटाता है। पढ़ने-केवल [IChart](../ichart/). |
| virtual **float** [get_Height](./get_height/)() | चार्ट तत्व की ऊँचाई को चार्ट की ऊँचाई के हिस्से के रूप में निर्दिष्ट करता है। पढ़ें **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | प्रेज़ेंटेशन लौटाता है। पढ़ने-केवल [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](./get_right/)() | चार्ट तत्व के दाएँ को चार्ट की चौड़ाई के हिस्से के रूप में प्राप्त करता है। पढ़ने-केवल **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। पढ़ने-केवल [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual **float** [get_Width](./get_width/)() | चार्ट तत्व की चौड़ाई को चार्ट की चौड़ाई के हिस्से के रूप में निर्दिष्ट करता है। पढ़ें **float**. |
| virtual **float** [get_X](./get_x/)() | चार्ट तत्व के x स्थान (बाएँ) को चार्ट की चौड़ाई के हिस्से के रूप में निर्दिष्ट करता है। पढ़ें **float**. |
| virtual **float** [get_Y](./get_y/)() | चार्ट तत्व के शीर्ष को चार्ट की ऊँचाई के हिस्से के रूप में निर्दिष्ट करता है। पढ़ें **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचें कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेण्ट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइपों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासों की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासों की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट की रेफ़रेंस के आधार पर तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट की रेफ़रेंस के आधार पर तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्धारित मान द्वारा साझा रेफ़रेंस काउंट को कम करता है। |
| virtual void [set_Height](./set_height/)(**float**) | चार्ट तत्व की ऊँचाई को चार्ट की ऊँचाई के हिस्से के रूप में निर्दिष्ट करता है। लिखें **float**. |
| virtual void [set_Width](./set_width/)(**float**) | चार्ट तत्व की चौड़ाई को चार्ट की चौड़ाई के हिस्से के रूप में निर्दिष्ट करता है। लिखें **float**. |
| virtual void [set_X](./set_x/)(**float**) | चार्ट तत्व के x स्थान (बाएँ) को चार्ट की चौड़ाई के हिस्से के रूप में निर्दिष्ट करता है। लिखें **float**. |
| virtual void [set_Y](./set_y/)(**float**) | चार्ट तत्व के शीर्ष को चार्ट की ऊँचाई के हिस्से के रूप में निर्दिष्ट करता है। लिखें **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्यूमेंट को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और वापस करता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेण्ट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [IChartComponent](../ichartcomponent/)
* नामस्थान [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)